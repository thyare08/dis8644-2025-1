# sesión-12b

*30 de mayo de 2021*

### Fuentes de poder

* Eliminador de batería, al cual se le puede poner un jack del voltaje que necesitamos.
* El voltaje (es algo que disponibiliza la batería) se entrega y  la corriente se pide (ya que es la energía que se necesita).
* siempre usar una fuente de poder de corriente mayor a la que se quiere utilizar.
* En el caso de un motor se puede alimentar con un jack de 5v y 3 amperes (nuestro computador consume más que eso).
* Un adaptador cambia la geometría del conector del aparato y un transformador cambia cómo le llega la energía.
* La transmisión eléctrica es sinusoidal (referente a las ondas sinusoidales que representan una señal oscilante).
* USB de tipo A. 
* No usar  USB tipo C para alimentar circuitos en este curso.
* Pantallas solares, referente (https://gieskes.nl/).
* Pilas de 1.5 o de reloj.

### Iluminación

* Leds.
* Ampolleta domestica (220v) conectada mediante un relé.
* Leds de alta potencia.
* Tira led normal y de neopixel.
* Tiras led recortables.
* Referente SpectraBloom (https://lorre-mill.com/spectrabloom).
  
### Motores

* Todo lo que sea pesado eléctricamente, luz, sonido y movimiento fuerte implica el uso de algún transistor.
* Para el uso de motores requerimos transistores (ya usamos un motor de 6v), se aplica en juguetes, ruedad, ventiladores, etc.
* Si quiero algo que gire más lento debo usar un motorreductor, el cual reduce las revoluciones, mediante los principios de conservación de movimiento angular.
* Referente Arthur Ganson [!faster](https://www.youtube.com/watch?v=JJvK47ncVjU).
* Stepper motor es mucho más lento y preciso, hay bipolares y unipolares.
  [![555 timer stepper motor driver](https://www.youtube.com/watch?v=Vc2XRVJ9n1o).
* Servo motor, es más rápido y menos preciso.
* Puente H, se compone por un motor, 4 interruptores o transistores y una fuente de energía, permite controlar el giro de un motor, cambiando el giro de un motor, por ejemplo este (https://mcielectronics.cl/shop/product/controlador-de-motores-puente-h-l298n-25508/).
* Cuando los componentes están fríos son más conductores.
* Si energizo una bobina se transforma en un imán que genera movimiento
* Referente Javier Bustos Lutería experimental [!Miniatura para miniatura electromagnética](https://www.youtube.com/watch?v=70w5TIubMik)
* Hay muchos artistas convirtiendo la señal midi en música
* Solenoides (ley de Henrry Faraday)
* Bomba de agua o de aire

### Transistores

*Se usan como amplificador, como switch

### Sonido

* Parlantes activos y pasivos
* Buzzers (suenan como las teclas de nuestro computador)

### Reproductor de audio

* Convierte datos en electricidad sonora
* Microfono, es una maquina que convierte el movimiento mecanico en energía
* Electrect microfono presente en diversos aparatos electronicos, como el telefono
  

## Encargo-24: Describir de forma textual 3 proyectos de máquinas electrónicas que quieran hacer de forma individual, ordenar por preferencia o interés de que sea desarrollado.

### Mini proyector de animación análoga.

Consiste en una caja que contenga leds de alta potencia conectados a una variación del circuito sensor de sombra realizado en clase en donde se reemplaza el ldr por un potenciómetro y se liga a un circuito PWM para lograr mover el motor que cambiara los frames de una animación cuadro a cuadro de una figura abstracta plasmada en papel translúcido. contará con un interruptor para apagar y será alimentado por una batería recargable de 9v.

La interacción consiste en posicionar el proyector en la dirección que se desee y presionar el interruptor, de esa forma comenzarán a encender los leds de diferentes colores que proyecten la luz al papel translúcido girando con el motor, dependiendo de la fluidez y rapidez en cambio de color de la luz se debera girar el potenciometro para modificar la frecuencia.

Esta idea surge de la visualización del referente mencionado en clase Spectra Bloom y de la influencia del pensamiento forjado en un curso de animación experimental.

### AtariPies

este circuito consiste en la unión de dos circuitos atari punk que usen sensores de proximidad a modo de resistencia variable, contará con un potenciómetro en cada atari para modificar el tono de los parlantes, será alimentado mediante una batería recargable de 9v y tendrá un interruptor. Tendrá forma de caja a nivel del suelo y los potenciometros irán a las manos mediante cables para interactuar con manos y pies.
 
La experiencia inicia presionando el interruptor, luego debes posicionarte en frente de la caja lo más lejos posible, con las manos se deben ajustar los potenciómetros y al mismo tiempo acercar y alejar los pies para modificar la frecuencia del sonido.

Surge de buscar que todo el cuerpo interactue para generar sonido, lo pense primero para las manos, pero sería mucho más fácil afinar la motricidad en comparacion a la coordinación mano pie.


### Juego para controlar la ansiedad

Este proyecto consiste en un motor conectado a un circuito PWM, cuya resistencia variable sea un potenciómetro. Podrá ser encendido y apagado mediante un interruptor y su fuente de alimentación será una pila de 3v.

La interacción se basa en tomar con una mano el dispositivo y disponer en un dedo de la mano contraria un pequeño palo unido a una especie de anillo elástico que nos permita fijarlo al dedo, para jugar debemos introducir el palo entre las “hélices” sin tocarlas, pudiendo configurar la frecuencia de giro mediante un potenciómetro. Está pensado específicamente en personas con necesidad de hacer movimientos repetitivos para regularse o estar haciendo cualquier cosa con las manos. 

La idea surge en que me muerdo las uñas y debo hacer algo más para evitarlo y tambien esta inspirado en las máquinas usadas en las pruebas psicotécnicas de conducir.


## Encargo-25: Dibujar diagrama de comportamiento, flujos de interacción. No especificar chips. Considerar procesos de manera especulativa. ¿Cuánto tiempo se usará? ¿Qué encendidos y apagados tiene? ¿Cómo se interactúa?

### Categorización
![categorizacion](https://github.com/AlanisMria/dis8644-2025-1/blob/main/27-AlanisMria/sesion-12b/archivos/categorizacion.png)

### Mini proyector de animación análoga.
![miniproyector](https://github.com/AlanisMria/dis8644-2025-1/blob/main/27-AlanisMria/sesion-12b/archivos/Mini%20proyector.png)

### AtariPies
![ataripies](https://github.com/AlanisMria/dis8644-2025-1/blob/main/27-AlanisMria/sesion-12b/archivos/atari%20pies.png)

### Juego para controlar la ansiedad
![juego](https://github.com/AlanisMria/dis8644-2025-1/blob/main/27-AlanisMria/sesion-12b/archivos/juego.png)




   
