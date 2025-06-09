# sesion-02b

Viernes 21 de marzo, 2025

Parte 1

Revisión de encargos y bitácoras.

Parte 2

Chips, timer 555 y esquemáticos.
  
  Apuntes
  Recomendaciones musicales.
  En Pueblo Nuevo
    El poder corrompe - Daniel Jeffs.
  El ritmo musical puede ser fluido o estructurado, tiene mucho que ver con la escala 4/4 que es la escala en que generalmente se compone música.
    Ejemplo: "1", "2", "3", "4", "5", "6", "7", "8" (cambio)  "1", "2", "3", "4", "5", "6", "7", "8" (cambio) es una estructura musical bien presente en la música electrónica pues varía la utilización de instrumentos.
  F600. Música chilena, quien realiza la música en F600 fue miembro de Pinochet Boys
  Daft Punk es ejemplo de la estructura musical antes mencionada.
  Música inmobiliaria(Colombia).
  Matias Serrano (ayudante) posee el proyecto Tutupá (2016). También tiene música en Pueblo Nuevo como Misaaaaaa.
    Hi Hat 808, un platillo eléctrico.  Hi Hat 303, un TB- 303 bassline.
   "Solenoide" es un dispositivo electromagnético actuador que consiste en una bobina de alambre enrollada alrededor de un núcleo de hierro o acero. Cuando pasa electricidad por la bobina, se crea un campo magnético. Convierte energía eléctrica en energía mecánica. Se utilizan en válvulas de control, interruptores eléctricos, cerraduras electromagnéticas, impresoras y fotocopiadoras, sistemas de inyección de combustible, electrodomésticos, maquinaria industrial, sistemas de seguridad, juguetes y modelos a escala y aplicaciones médicas (para regular el suministro de medicamentos y fluidos).
 Revisar "intro-elec.md" Presentación: Introducción a la electricidad.
   Tales de mileto -> Propiedades electromagnéticas del ámbar. Recuperado por Guillermo Gilberto (William Gilbert) en 1600 (aproximadamente 2000 años después).
 Lenguaje esquemático
   El cómo leer componentes electrónicos.
    Fuente de poder > Batería  Cable > wiring  Resistors > resistencias  Fixed > variable.
    Interruptores.
    LED que singifica DIODO EMISOR DE LUZ.
    El diodo es un semiconductor, recordar que existen los elementos conductivos y aislantes y entremedio están los semiconductores.
    Transistores.
 María Ignacia Valdebenito. Artista visual que con su pensamiento gráfico realiza serigrafía de elementos de circuitos electrónicos.
    Poemas: del latín poema y del griego poiema, etimológicamente singifica "creación", viene de la palabra poiesis que significa "crear".
    Siempre para realizar nuestros circuitos debemos considerar un BOM: (bill of materials): Una lista extensiva de materiales, componentes e instrucciones requeridas para construir, manufacturar o reparar un producto o servicio.
    Para hacer uso del protoboard hacemos uso de de jumpers o cables Depont y clips de batería.
    Si usamos una resistencia de 220 Ω los LEDs llegan a iluminarse más, sin embargo, la resistencia tiende a calentarse.
    Ojo: una resistencia conectada a tierra también puede servir para finalizar el circuito
 ¿Cómo utilizar un multímetro?:
    Conectar negro a tierra y rojo positivo.
    El multímetro mide volts, ohms y miliamperios.
  La resistencia del cuerpo humano es bastante, el margen de error en el multímetro es mínimo.
  Sobre baterías: Las baterías se vencen por fecha indicada en la parte inferior, esto debido a que esta fuente de poder (en caso de no ser recargable) deja electrones paulatinamente y ya en la fecha indicada es probable que un objeto que necesita de dicha fuente de poder no sea muy estable. Esto es irreversible.
  YML es la extensión de archivos escritos en YAML, es un lenguaje de marcado para serializar datos. Permite representar datos estructurados de forma que sea fácil entender para los humanos y que pueda ser interpretado por las máquinas. Independiente de cualquier lenguaje de programación en específico, abierto e interoperable. Se basa en JSON y tiene caracterísitcas de otros lenguajes de programación como Perl, C, XML y HTML.
  Utiliza sangría al estilo Python para determinar la estructura.
  Node.js
  Es un entorno de tiempo de ejecución multiplataforma, de código abierto, para la capa del servidor basado en el lenguaje de programación JavaScript. Con E/S (periférico de entrada y salida o input/output: dispositivo capaz de interactuar con elementos exteros al sistema de forma bidireccional, o sea permite el ingreso de información desde un sistema externo, como emitir información a partir de ese sistema).
  Es decir, Node.js permite la conversación entre computadores.
 David Tudor (1926-1996), estadounidense
Pianista que poseía unas bitácoras interesantes, y que se dedicó a realizar obras electrónicas, hitos de la electrónica en vivo. Revisar Reminded by the instruments: David Tudor's Music. (Tudor, D.) o Composers inside electronics (Tudor, et al.)
Ley de Ohm: menos resistencia igual más corriente, más resistencia igual a menos corriente
Ensayos sobre circuitos con resistencias y LEDs:
  
![alt-text](https://github.com/user-attachments/assets/c1f5055a-e3c0-483e-b907-b171d0b3161e)

![alt-text](https://github.com/user-attachments/assets/2e1bb6dc-c954-4dac-b7e2-f26bcfa111e8)

![alt-text](https://github.com/user-attachments/assets/2e1a6a0c-01c6-489e-880f-5eb70dd34c31)

![alt-text](https://github.com/user-attachments/assets/bf386223-9a29-4f8c-9f81-aac079a32ef3)

![alt-text](https://github.com/user-attachments/assets/dbfbc56e-4b0a-45a6-882d-54952e54d94c)

![alt-text](https://github.com/user-attachments/assets/35aab5d7-0af3-4a7d-a850-1a341506eac4)

![alt-text](https://github.com/user-attachments/assets/da9bcaa3-7d5b-44f6-94f1-6e807662b3fe)

![alt-text](https://github.com/user-attachments/assets/5f176de6-e857-4022-8246-5fb0dc4c3f1b)

![alt-text](https://github.com/user-attachments/assets/49aedc2a-1bbb-468b-a1b4-507c7d73d200)

![alt-text](https://github.com/user-attachments/assets/47cdacf6-385d-4bf1-8de4-9ec7cde0c05d)

Si se tienen dos opciones en el circuito cerrado, los electrones que viajan donde existan menos resistencias, es decir, que se da el caso en el no puedan coexistir LEDs en paralelo que estén en la misma línea de un protoboard si -por ejemplo- uno de estos caminos del circuito posea más resistencias que su contrario, los electrones viajarán al acceso con menos obstáculos: de - a +.

<https://howtomechatronics.com>

Chip 555

Suzanne Ciani, buscar acerca de su sintetizador

Suzanne Ciani (1946), estadounidense

Compositora y pianista, pionera en el campo de la música electrónica, una de las primeras mujeres en hacerse un nombre en el mundo de la música New Age destaca en su utilización del sistema de sonido cuadrafónico el cual es capaz de reproducir audio en cuatro canales, a través de cuatro altavoces independientes. A finales de los años 60s trabajó soldando sintetizadores Buchla. Fue inventora la banda sonora recurrente en comerciales de compañías de la época, entre ellos Coca-Cola, Atari, American Express, etc. En 1980 incluyó su voz en el videojuego pinball Xenon siendo el primer juego con voces femeninas. Durante su vida recibió discriminación por ser mujer y haber aportado en la creación de un sintetizador y fundado una sociedad sin fines de lucro para promocionar música electrónica llamada ECNW (en inglés Centro electrónico para la nueva música), esta fracasó por lo mencionado anteriormente. Sus composiciones discográficas fueron un éxito en Japón y, tiempo después, también en EEUU. Su carrera comprende alrededor de 20 álbumes publicados desde 1982 hasta 2018 (consultado el 23 de marzo de 2025). Reconocimientos a su obra han sido cinco nominaciones a los premios Grammys y un Globo de Oro.
  
Para Mark Down existe un generador de tablas para adjuntar al archivo llamado: Markdown table (buscar en Google).

Bitácora en relación a los apuntes:
  
![alt-text](https://github.com/user-attachments/assets/0b16f6eb-7d28-4164-b517-e21a735d6436)

![alt-text](https://github.com/user-attachments/assets/9a60129d-6d31-47ec-b826-5e3f1680657f)

![alt-text](https://github.com/user-attachments/assets/728ae9fc-d2ff-42ca-981e-a6ed6edfd957)

![alt-text](https://github.com/user-attachments/assets/72350a3e-c84f-4229-ab3b-57bba7912f9f)

![alt-text](https://github.com/user-attachments/assets/9c5b3f58-51a9-4088-aeb0-2de9d8f38f98)

![alt-text](https://github.com/user-attachments/assets/4b09b1fa-985d-4447-a3a4-9dcf26817933)

![alt-text](https://github.com/user-attachments/assets/61c83893-8322-45df-94b1-ed5019cb31eb)

![alt-text]("https://github.com/user-attachments/assets/86676a9a-76d6-4308-873c-120cc6623333)

![alt-text](https://github.com/user-attachments/assets/583b19a9-d4e0-48f1-bc95-732e12a60536)

![alt-text](https://github.com/user-attachments/assets/e4fa7444-4476-4d7a-bee7-66cfa225436a)
