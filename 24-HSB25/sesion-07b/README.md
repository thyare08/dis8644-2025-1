# sesion-07b

# ENCARGO 14: Diseñar Esquematico en KiCad

Diseñar esquemático en Kicad (solamente esquemático, no asignar huellas) de Atari Punk Console con modificaciones que ustedes realizaron en KiCAD, o en su versión base si sus modificaciones no funcionaron al 100%.

![ATARI PUNK CONSOLE](ATARI_PUNK_CONSOLE.png)










# ENCARGO 15: Plantear 2 Dudas o aprendizajes importantes

- **Aprendizaje 1:** Importancia de las huellas (footprints) en el diseño de PCBs

El manual destaca la relevancia de las "huellas" o footprints, que representan el espacio físico y las conexiones utilizadas por un componente electrónico en la placa de circuito impreso (PCB). Comprender y asignar correctamente las huellas es esencial para garantizar que los componentes se monten adecuadamente en la PCB y que el diseño sea funcional.​

- **Aprendizaje 2:** 

Aplicando los conocimientos del manual, es posible emprender el diseño de una consola de videojuegos reconocida, como la **NES** o la **Game Boy**, utilizando **KiCad**. Esto implicaría:​

- Crear el esquema electrónico de la consola, identificando y conectando los componentes clave.

- Organizar el diseño mediante hojas jerárquicas para separar módulos como la CPU, la memoria y la interfaz de video.

- Generar los archivos Gerber necesarios para la fabricación de la placa PCB.​


Este enfoque no solo refuerza los conceptos aprendidos, sino que también proporciona una experiencia práctica en el diseño de sistemas electrónicos complejos.​

Diseñar una consola portátil como el Game Boy implica una serie de pasos en electrónica que se pueden abordar con KiCad, y el Manual de supervivencia es una herramienta perfecta para iniciarte y avanzar con bases sólidas.

# 1. Diseño del esquemático (idea principal)

➤ ¿Qué enseña el manual?
El manual te guía en:

Cómo añadir componentes electrónicos como microcontroladores, resistencias, capacitores, etc.

Cómo conectarlos con cables virtuales para formar un circuito completo.

Cómo organizar tu esquemático de forma clara.

➤ ¿Cómo lo aplico para el Game Boy?
Podrías diseñar un esquema con:

Un microcontrolador como un ESP32, STM32 o incluso Raspberry Pi Pico para manejar entradas y salidas.

Una pantalla LCD o OLED (hay módulos como ILI9341 o SSD1306).

Botones para controles (A, B, Start, Select, D-pad).

Regulador de voltaje para una batería recargable.

Una pequeña tarjeta SD o memoria flash para guardar juegos.

# 2. Asignación de huellas (footprints)

➤ ¿Qué enseña el manual?
El manual explica cómo:

Asignar a cada componente su huella física, es decir, el diseño de pines y pads que tendrá en la PCB.

Seleccionar huellas de librerías estándar o personalizadas.

➤ ¿Cómo lo aplico para el Game Boy?
La pantalla tiene un footprint específico (de 14 a 20 pines).

Los botones tienen footprints tipo SMD o through-hole.

Los puertos USB, ranuras microSD y conectores de batería también deben tener huellas correctas.

Esto es fundamental para asegurarte que cuando mandes a fabricar la placa, los componentes encajen y funcionen.

# 3. Diseño de la PCB

➤ ¿Qué enseña el manual?
Cómo mover los componentes del esquemático a un plano físico.

Cómo usar herramientas para rutar pistas, mover capas y optimizar el diseño.

➤ ¿Cómo lo aplico para el Game Boy?
Organizarás los componentes como si fueran parte de un layout físico de consola.

Podrías colocar la pantalla en el centro, los botones a los lados, la batería abajo, etc.

Es como diseñar el circuito y la carcasa al mismo tiempo.

# 4. Generación de archivos Gerber para fabricar tu Game Boy

➤ ¿Qué enseña el manual?
Cómo generar archivos Gerber, los cuales las fábricas de PCBs necesitan para producir tus placas.

➤ ¿Cómo lo aplico para el Game Boy?
Una vez tengas todo el diseño terminado:

Generas los archivos y los subes a sitios como JLCPCB, PCBWay o OSH Park.

Puedes mandar a hacer una placa personalizada que funcionará como la base de tu consola portátil.

# 5. Pruebas, montaje y carcasa (fuera de KiCad, pero relacionado)

Usas impresora 3D o laser cut para crear una carcasa similar a un Game Boy.

Soldas los componentes en la PCB (guiado por los archivos del proyecto).

Puedes incluso usar software de emulación para correr juegos simples (como Tetris o Pong).

# Ejemplo real:

Hay proyectos similares disponibles en internet. Aquí te dejo uno inspirado en una consola portátil hecha con KiCad:

Proyecto de Game Boy DIY: https://hackaday.io/project/18896-game-boy-zero

PCB para consola portátil con ESP32: https://github.com/biaslab/esp32-game-console




