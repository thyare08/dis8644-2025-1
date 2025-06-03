# sesion-12b

30-05-2025

## Apuntes
<code style="color : magenta">REPASO DE COMPONENTES</code>

**Fuentes de poder**
* Baterías 9V
* Fuente de poder ACDC (voltaje 4,5 - 5 - 7 - 9 - 12 - 15 - 18 - 25 [vcd] )
* Power bank: USB-a / USB-b
* USB-c tiene un chip, <code style="color : darkorange">handshake</code> ojo, trabaja con otro estándar
* USB-c permite que las cosas carguen de manera más rápida
* Pantallas solares
* Pilas 1.5v
* Pilas reloj 3v
Transformador: lo que cambia el voltaje y la frecuencia
Adaptador: solo cambia la forma de conectar

![batería9v](https://github.com/user-attachments/assets/5ee8f0c2-e440-401e-94d3-f760637bd62a)

**Luces**
* LEDS son útiles para saber si algo está funcionando (se pueden quemar)
* Ampolletas domésticas (con relés podemos controlar el paso de la corriente)
* LEDS de 3W (requieren resistencias grandes) (son de alta potencia)
* Tiras LEDS (son muchos LEDS y normalmente son de lata potencia) son programables

![leds-8mm](https://github.com/user-attachments/assets/b4bd4008-b358-46b5-af1f-b7aa7457807b)

**Motores**
* Motores DC 6V
* Si quiero motores DC que giren más lento, deben ser motores <code style="color : darkorange">reductores</code>
* Motor: cada vez que le llega un pulso, avanza un poquito
* Selenoide: genera movimiento lineal. Se usa en percusiones electromecánicas y en chapas electrónicas

![motores](https://github.com/user-attachments/assets/8ee0d2e3-81d1-46c5-9c04-1ab0ab6c1d67)

**Transistores**
* Bipolares y FET (FET: es un tipo de transistor que utiliza un campo eléctrico para controlar el flujo de corriente a través de un canal semiconductor)
* Se utilizan como amplificadores, como switch, como inversor o como compuerta lógica

![transistores](https://github.com/user-attachments/assets/5082b2fb-cb26-462d-ab4e-2eb11175cdc5)

**Sonido**
* Parlantes activos y pasivos (los activos se enchufan y los pasivos no, ya que requieren de amplificación externa) (su intensidad depende de su tamaño [en pulgadas] depende de su potencia [en watt] y de su impedancia [OMH] )
* Buzzers, son parlantes básicos, principalmente usados como señal de alarma o aviso. Pueden sonar muy fuertes
* Reproductor de audio, convierte datos digitales en electricidad sonora
* Micrófonos, convierte el sonido (mecánica) en electricidad. Inverso a un parlante
* Micrófono piezoeléctrico, convierte vibración mecánica en electricidad
* Sintetizadores, generan sonidos a partir de señales eléctricas creadas dentro del mismo aparato

![parlante](https://github.com/user-attachments/assets/0ed1a985-ff29-4bb0-b3cc-223278202b6e)

**Piezoeléctrico**
* Movimiento en electricidad

**Referentes y links**

* Christian Oyarzun
* Sonic PI
* Anillo WEB
* https://www.instagram.com/gijsgieskes/?locale=es_US&hl=en
* https://www.arthurganson.com/concrete-1
* https://www.arthurganson.com/23-scraps-1
* https://gieskes.nl/
* https://lorre-mill.com/spectrabloom
* https://learn.adafruit.com/all-about-stepper-motors/what-is-a-stepper-motor
* https://www.youtube.com/watch?v=Vc2XRVJ9n1o
* https://www.adafruit.com/product/4411
* https://en.wikipedia.org/wiki/Single_coil_guitar_pickup
* https://www.youtube.com/watch?v=70w5TIubMik
* https://polyend.com/legacy/polyend-perc/
* https://www.youtube.com/watch?v=FYSJdrDUpXs
* https://deanmarkley.com/products/transducer-acoustic-guitar-pickups
* https://es.wikipedia.org/wiki/Piezoelectricidad
* https://hackaday.com/2015/02/04/logic-noise-sweet-sweet-oscillator-sounds/
* https://www.youtube.com/watch?v=Xbl1xwFR3eg

## Encargo 24
* Describir de forma textual 3 proyectos de máquinas electrónicas que quieran hacer de forma individual, ordenar por preferencia o interés de que sea desarrollado.

***Proyecto 01***

* _Descripción_: Máquina electrónica diseñada para acompañar a personas que pasan muchas horas sentadas frente a pantallas, recordándoles de hacer pausas activas. Mediante señales sonoras, visuales o vibración.
* _Objetivo_: Diseñar un dispositivo que notifique al usuario cuando hacer una pausa activa, a través de una máquina electrónica.
* _Usuario_: Trabajadores home office o personas que necesiten de un apoyo externo para regular sus tiempos.
* _Interacción con el usuario_: Genera una señal cada 1 hora de inactividad (puede variar el tiempo)

|Color|Función|
|---|---|
|LED Rojo|Realizar trabajo|
|LED Amarillo|Terminará luego la hora de trabajo|
|LED Verde|Comienza Pausa activa|

* _Contexto de uso_: En escritorios personales, co-works, talleres, etc.
* _Metas_: Disminuir el cansancio acumulado, dolores corporales y estrés
* _Componentes_: Buzzer (vibrador/sonido), luces LEDS, resistencias, botón, microcontrolador
* _Decisiones de diseño_: Formato compacto portátil, que se vea como un compañero de escritorio
* _¿De dónde nació esta idea?_: La idea nace porque siempre veo a mi papá pasar horas trabajando en el escritorio, por lo que no se da cuenta que en algún momento debe de realizar una pausa activa.

***Proyecto 02***
* _Descripción_: Máquina electrónica que reproduce sonidos distorsionados cuando un usuario lo toca.
* _Objetivo_: Diseñar un dispositivo de interacción táctil y sonora, que provoque la curiosidad, la exploración intuitiva.
* _Usuario_: Personas que sean curiosas y con ganas de explorar.
* _Interacción con el usuario_: Sin instrucciones de uso, el usuario encuentra una especie de cubo en la mesa. Al tocarlo, se activará los sensores y reproducirá distintos sonidos.
* _Contexto de uso_: Instalación en exposiciones, museos o espacios académicos.
* _Metas_: Generar una interacción que invite a la exploración física y conceptual. Usar el sonido como única interfaz comunicativa.
* _Componentes_: Microcontrolador, resistencias, cables, batería, sensores, speakers 
* _Decisiones de diseño_: Forma cúbica, donde el circuito esté por dentro, como si fuese un cubo rubik.


## Encargo 25
* Dibujar diagrama de comportamiento, flujos de interacción. No específicar chips. Considerar procesos de manera especulativa. ¿Cuánto tiempo se usará? ¿Qué encendidos y apagados tiene? ¿Cómo se interactúa?

1. ![Captura de pantalla](https://github.com/user-attachments/assets/2db5c873-9561-43cf-8086-bbadfa9b8541)

2. ![Captura de pantallaaa](https://github.com/user-attachments/assets/8a9f8482-5929-4ec5-83c6-bb954ab962c3)


