# sesion-04b
poner apuntes clase viernes 4 abril










## encargo 1 - switched on bach (wendy carlos)




## encargo 2 - bajando opacidad a la caja negra

Escoger un aparato electrónico, que no funcione (o este dispuestx a destruir), y abrirlo para explorar su interfaz. Diseccionar. Analizar. OBVIAMENTE APARATO DEBE ESTAR DESCONECTADO Y APAGADO ❗ NI TRABAJAR A PATA PELÁ 🦶

DOCUMENTAR EN FOTOGRAFÍAS





### Reproductor mp3 - Dynatech

![Captura de pantalla 2025-04-08 020016](https://github.com/user-attachments/assets/a205a71a-6b5a-4965-8cc1-980ed474e62f)

El mp3 se puede conectar directamente a un puerto USB para cargar música y/o batería. Al conectar el usb bloquea su uso, los botones no funcionan durante la conexión. La navegación se hace mediante un botón circular multifunción (M, ▶||, ←, →, etc.). Reproduce música por audífonos con salida jack de 3.5 mm y permite conectar un cable auxiliar para conectarse a un parlante. En su costado cuenta con una entrada micro sd para cargar musica y en el otro botón de encendido / apagado. 

¿Cómo me indica esa manera de uso?

Su forma de uso se indica a través de símbolos en el botón circular que señalan funciones como reproducir/pausar, cambiar de canción y acceder al menú. Cuenta con una pantalla pequeña la cual cuenta con iluminación que muestra una interfaz bien básica la verdad, pero funcional. Me gustaría poder mostrar esta interfaz pero la pantalla por algún fallo (al ser tan pequeño en alguna lavada de pantalón este quedo dentro y tuvo su primera ducha, funciona a medias) solo enciende conectado a un usb (funciona a dia de hoy solo como pendrive, esta cuenta con música que escuchaba en 2016). Con los años olvide los menús que tenía, pero deberían ser, carpetas, álbumes, opciones, etc. Su diseño compacto y ergonómico permite manipular los botones fácilmente con el pulgar, lo que refuerza su carácter portátil. En la carcasa hay diversos grabados que indican funciones como donde se conecta los audífonos o encendido / apagado.

![image](https://github.com/user-attachments/assets/6fb79057-2f50-4dc0-b895-b12da567411b)

Gestos, contexto (Función indicativa y simbólica)

Cada botón genera una respuesta directa al tacto, lo que permite que el que lo usa asocie fácilmente una acción con su resultado, como avanzar canciones o pausar la reproducción. La disposición de los botones alrededor del control circular tiene un sistema de navegación en direcciones, con este uno navegaba el menú. Además, el conector USB permite conectar a un computador sin necesidad de un cable (como un pendrive).

El usuario sería una persona interesada en escuchar música de manera portátil, algo que con el tiempo fue reemplazado por los teléfonos (era pre-smartphone). Me da un poco de pena cómo la moda de los MP3 evolucionó hacia eso; a día de hoy resulta difícil ver a alguien con uno. Uno se metía a internet, buscaba la música que quería y la descargaba para llevarla en el día a día. Ando con ganas de volver a llevar un MP3 en el bolsillo, quisiera tener alguno bueno tipo Sony. Ahora se venden en formato walkman con una pantalla, pero los precios no son muy accesibles y sería un lujo tener uno. Antes estos se vendían por montones: ibas al kiosco, supermercado, papelería, y podías conseguir uno. No creo que una persona con discapacidad visual pueda ocuparlo, ya que se debe usar la pantalla para ver los menús; debería usar uno sin pantalla incluida y con relieves en los botones.

¿Qué interacción ofrece desde fuera? 

- Botones físicos: 5 funciones en el control circular.
- Interruptor lateral encendido/apagado.
- Pantalla: interfaz visual.
- Puerto USB , salida de audio 3.5 mm y entrada micro sd.
- No cuenta con perillas

¿Qué grados de control entrega?

Desde el exterior, el dispositivo ofrece varias formas de interacción directa. El control circular permite acceder a cinco funciones principales, como reproducción, pausa, navegación entre pistas y acceso al menú. A un costado, un interruptor deslizante permite encender o apagar el aparato. La pantalla, aunque pequeña, actúa como una interfaz visual que guía al usuario a través de menús y funciones. Se conecta con un puerto USB incorporado para la transferencia de archivos y carga, una salida de audio de 3.5 mm para conectar audífonos, y una entrada para tarjeta micro SD que amplía su capacidad de almacenamiento. En grados de control, es limitado, pero suficiente para su propósito: reproducir y organizar música de forma simple. No permite modificar el ecualizador (que recuerde, solo se podía ver el volumen y brillo de la pantalla), gestionar carpetas complejas desde el propio aparato, solo podías borrar y mover canciones entre carpetas y ver por artista, años, etc.

¿De donde obtiene energía este aparato?

Tiene una bateria de 3,7V y 120 mAh, que duraba a los mas 5 horas, menos si le subias el brillo a su pantallita. Se recarga conectando el usb a un cargado o compu.

![image](https://github.com/user-attachments/assets/08db536d-6c58-4501-802a-cf32a0175f6c) 

¿Hay una PCB principal?

![image](https://github.com/user-attachments/assets/76947516-c6d1-47e6-b830-eacfa1de9b20)

Sí. Una única PCB (placa de circuito impreso) todos los componentes necesarios para el funcionamiento del MP3 estan en esta. La carcasa cierra por ambos lados protegiendola.

¿Cómo se interconectan? 
Los componentes van soldados al PCB. Las interconexiones van a través de las pistas de cobre del circuito. Tiene 2 cables rojo y negro que conectan la batería a la placa (alimentación) y una cinta plana conectando la pantalla al PCB. Estas cintas las había visto una vez cuando desarme un control de ps4, esto conectaba el panel táctil de mando. 


¿Hay números, textos, dibujos?

De lo que logré observar solamente encontré 3 cosas. 
- Dos chips que dicen: SKhynix- H27UCG8T2TR- 432BL y ATJ 3150- ZG82 38A
- Bateria 3,7V y 120 mAh  

# Bill of Materials (BoM) – Reproductor MP3

| Componente                 | Cantidad | Descripción                                                 |
|----------------------------|----------|-------------------------------------------------------------|
| PCB                        | 1        | Soporta todos los componentes electrónicos del dispositivo. |
| controlador                | 1        | Controlador principal, este maneja la reproducción y funciones. |
| Memoria Flash (SK hynix H27UCG8T2ETR) | 1 | Almacena la música, firmware y archivos del sistema.    |
| Pantalla                   | 1        | interfaz grafica                                            |
| Botones físicos (táctiles) | 6        | Control de volumen, navegación de menú, encendido, etc.     |
| Batería  3.7V 120mAh       | 1        | Fuente de energía recargable, conectada por cables.         |
| Puerto USB tipo A          | 1        | Carga de batería y transferencia de archivos.               |
| Jacks de audio 3.5mm       | 2        | Salida de audio                                             |
| Condensadores              | Varios  | Filtrado de voltaje, desacoplamiento.                        |
| Resistencias               | Varios   | Limita la corriente y establece el voltaje.                 |
| Cinta flex (pantalla)      | 1        | Conexión de la pantalla al PCB principal.                   |




