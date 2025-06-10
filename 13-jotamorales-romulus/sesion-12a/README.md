# sesion-12a

martes 27 de mayo

## Apuntes
- Llegue tarde devido a que la linea 1 del metro tuvo problemas y termine llegando como a la 9:20 y fue todo un caos, la gente se metia a los vagones aun estos estando llenos y casi ni me pude bajar en republica.

- Me perdí bastante pero de lo que alcancé a entender estábamos viendo nuevamente el chip 4017. Nos dijeron que revisáramos el  [Datasheet 4017](https://www.ti.com/lit/ds/symlink/cd4017b-mil.pdf?ts=1748292720173&ref_url=https%253A%252F%252Fwww.google.com%252F). Un datasheet es la hoja técnica de un componente. Sirve para saber cómo usarlo correctamente: te dice el voltaje que necesita, qué hace cada pin, cuánto mide, cuánta corriente soporta, etc.

- Tenemos plazo hasta el 10 de junio para corregir y subir las bitácoras al repositorio. Me faltan corregir las bitácoras: 10a, 10b, 11a, 11b, 12a y 12b. Para pedir la corrección, hay que abrir un issue indicando cuáles bitácoras se tienen que revisar.
  
- Muchas personas del curso hemos subido mal las imágenes, por eso se nos enseñó cómo subirlas correctamente. Primero, hay que entrar a la carpeta de la sesión correspondiente y subir las fotos dentro de la carpeta llamada archivos, usando el botón Add file. En algunas ocasiones he tenido problemas porque las imágenes no cargaban bien, por eso prefiero subirlas en formato JPG. Después de subirlas, hay que dar Commit changes para guardar los cambios. Para mostrar la imagen en el README, se debe poner la ruta /archivos/nombredearchivo.png. No poner mayusculas ni tildes en el nombre.

## Detector de sombra

El circuito completo es un contador de luz: detecta cuando cambia la cantidad de luz (por ejemplo, al tapar o destapar el LDR) y, por cada cambio, enciende un LED diferente en secuencia. Usa un comparador para saber si hay más o menos luz que un umbral, un temporizador 555 que genera un pulso por cada cambio, y un contador 4017 que avanza y prende los LEDs uno por uno.



Algo que Aarón me recordó y que es algo en lo que sigo profiando constantemente es usar cables negros (o algún color frío) para el negativo, y colores cálidos para el positivo. Eso ayuda mucho a no confundirse al momento de conectar todo.

1. La primera parte del circuito usa un LM324. En esta etapa, conectamos un LDR a una de las entradas y un potenciómetro a la otra, lo que permite fijar un nivel de luz como referencia. Cuando la luz disminuye, la resistencia del LDR cambia, haciendo que el voltaje en esa entrada aumente. Si ese voltaje supera al del potenciómetro, el comparador entrega una señal alta. Esta parte me costó bastante, ya que el circuito no me funcionaba. Le pregunté a Aarón por qué no funcionaba, y aunque estaba todo bien conectado, Misaa al revisarlo se dio cuenta de que yo estaba usando un 4017 por error. Me confundí con las patitas, algo que ya me había pasado antes en otras clases. Es importante leer bien lo que uno está utilizando.

[![registro 1](https://img.youtube.com/vi/Hjm08we3xsU/0.jpg)](https://www.youtube.com/shorts/Hjm08we3xsU)


2. Cada vez que el comparador detecta un cambio, manda un pulso al 555, que responde generando un pulso de duración fija. Ese tiempo depende de un condensador (por ejemplo, 10µF o 100µF). Mientras dura el pulso, se prende un LED que indica que está activo. El de 10µF hace que el LED se apague más rápido, y con 100µF dura un par de segundos. Acá nuevamente tuve problemas para terminar esta parte, pero es cosa de conectar bien las cosas.

[![registro 2](https://img.youtube.com/vi/JcL49nXyNDk/0.jpg)](https://youtu.be/JcL49nXyNDk)


3. En la parte final del circuito no alcancé a terminarlo en clases, pero entendí más o menos lo que hace. El pulso que genera el 555 llega al 4017, que es un contador. Cada vez que le llega un pulso, avanza una salida (como de Q0 a Q5), y con eso se van prendiendo los LEDs uno por uno. Es como una secuencia de luces que responde a los cambios de luz que detecta el LDR. También me dijeron que hay poner un condensador de desacople para que funcione más estable.
