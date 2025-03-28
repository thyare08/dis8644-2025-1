# sesion-03a
### Módulo de la mañana
Sisters with Transistors, el origen de los sintetizadores
Daphne Oram creó una máquina que generaba sonido a partir de un dibujo.
Eliane Radigue tocaba los sintetizadores de la manera más lenta posible.

Vcc: Voltaje de corriente continua, VCC va a positivo.
Las resistencias en serie son equivalentes a r1+r2=Req (resistencia total equivalente).
Resistencia paralela: 1/Req = 1/R1+1/R2.

En donde esté la resistencia, no va a afectar la corriente de diferente manera.

Cubo de resistencia

Cómo sacar resistencias equivalentes

Bill of Materials (BOM)

Vamos a tener 2 proyectos en este semestre.

LDR es la pieza que parece lenteja con sinusoides encima.
Prefijos de notación científica

-1 × 10^9 = 1.000.000.000 G (giga)  
-1 × 10^6 = 1.000.000 M (mega)  
-1 × 10^3 = 1.000 K (kilo)  
-1 × 10^0 = 1 u (unidad)  
-1 × 10^(-3) = 0,0001 m (mili)  
-1 × 10^(-6) = 0,000001 u (micro)  
-1 × 10^(-9) = 0,000000001 n (nano)  
-1 × 10^(-12) = 0,000000000001 p (pico)  

Mi "goomba" es simétrico y cerámico de 474 tiene 470.000 p, ya que los 2 primeros dígitos son dígitos, y el último es la cantidad de 0 (47x10(-4)).
Los capacitores se miden en faradios.
El condensador electrolítico tiene polaridad.


### Módulo después de break

Los condensadores almacenan voltaje.
¿De qué sirve?
Si hay variaciones abruptas en el voltaje, el condensador es como una represa.
La lentitud de disminución de energía depende del tamaño del condensador.



NE555P es el nombre de nuestro chip.
Datasheet es el manual, se pueden ver las utilidades de este chip.
Un chip es un I.C. (Integrated Circuit).
El 555 no es simétrico, ya que cada una de sus patas tiene una función distinta, también es un timer.

Un electrón que parte en la patita 7 tiene que sí o sí llegar a positivo a través de una resistencia, porque si pasa por un cable, llega y se quema.
La pata 3 del chip es output.
Las resistencias tienen un 5% de error.
La tolerancia equivale a un mayor margen de error.

El circuito que logramos hacer va a ser nuestro lugar seguro.


Configuración astable
Existen calculadoras para la configuración en modo astable. https://www.digikey.com/en/resources/conversion-calculators/conversion-calculator-555-timer

El tiempo de encendido y apagado va a depender de 3 cosas.

Vamos a conectar un potenciómetro. WOWOWOW

# encargo06: cultura electrónica europea de los 1980s y 1990s


# encargo07: apuntes sobre digerir, reflexión y expansión del chip 555

En la clase fuimos paso a paso de cómo deberíamos llegar al modo Astable, el cual será nuestro “lugar seguro” de aquí en adelante, ya que si algo no funciona y fue mal, volveremos a esta base.
![20250328_010511](https://github.com/user-attachments/assets/ace6c7b5-b00b-4931-9ff6-cff193c5c763)


Uno de los puntos importantes es que en el lado izquierdo de la protoboard, donde se conecta la pata 2 junto a la pata 7 del 555, ocupamos una resistencia. El condensador electrolítico que ocupamos era de 100uF.

https://github.com/user-attachments/assets/925a2199-b5a6-4152-8ddb-40a6124f903e


Los profesores nos especificaron estas partes para que fuera estable la velocidad de cambio de nuestro led entre prendido y apagado, ya que, una vez que cambiamos estas dos partes, el tiempo de cambio entre prendido y apagado del led cambia drásticamente.


Lo primero que cambiamos fue la resistencia 2 por un potenciómetro, que logra que podamos cambiar la velocidad de parpadeo del LED al girar la perilla, eso sí solo una cantidad determinada por el condensador electrolítico.

Si cambiaba el condensador electrolítico por uno de menor uF, este permitiría que el LED en mi circuito lograra parpadear más rápidamente.

![20250325_121724](https://github.com/user-attachments/assets/b4941e70-9973-4a67-b2c5-b0f87c6b9f83)


https://github.com/user-attachments/assets/a45684e4-1b7b-40c1-8293-106ba3350c2b


https://github.com/user-attachments/assets/bb4a42e4-028a-4280-b3b4-ea1effe2e8a7

El chip NE555P, fabricado por Texas Instruments y creado en el año 1971, es asimétrico, debido a que sus 8 patas tienen una función distinta asignada, la cual no se puede cambiar.

El 555 es un dispositivo altamente estable para generar oscilaciones o demoras de tiempo precisas. Si se necesita, hay terminales adicionales para el activamiento o el reinicio. En el modo de funcionamiento de retraso temporal, el tiempo se controla con precisión mediante una resistencia y un condensador externos. 

Las funciones que tiene cada pata son las siguientes:
1.Ground: Conectado directamente a negativo  
2.Trigger: permite que se active o no se active la señal de la pata  
3.Output: A partir de esta pata se recoge la señal emitida por el chip.  
4.Reset: Para que se resetee, debería estar conectado a VVC cuando no esté en uso.  
5.Control Voltage: Controla el voltaje. Si esta patilla no se utiliza, que ocurre en la mayoría de los casos, se recomienda ponerle un condensador de 0.01 uF o 10 nF para evitar las interferencias.  
6.Threshold: Compara la tensión aplicada al terminal con una tensión de referencia de 2/3 Vcc, se utiliza para poner la salida (pata 3) a nivel bajo.  
7.Discharge: Cambia la salida de alta a baja cuando la tensión alcanza 2/3 de la tensión de alimentación. El condensador de temporización se descarga a través de esta pata.  
8.V+:Conectado directamente a positivo, con un mínimo de 4.5 voltios y un máximo de 16 voltios de alimentación.

Tienen múltiples distintos modos de uso, entre los que se encuentran:

Astable mode
Que no tiene estado estable, el output cambia continuamente de estado entre alto y bajo sin ninguna intervención del usuario, lo que se denomina una onda "cuadrada". Este tipo de circuito puede utilizarse para dar movimiento intermitente a un mecanismo, encendiendo y apagando un motor a intervalos regulares. También puede utilizarse para hacer parpadear lámparas y LED, y es útil como pulso de 'reloj' para otros circuitos integrados y circuitos digitales.

Monostable mode
Un circuito monoestable produce un impulso de una duración determinada en respuesta a una entrada de activación, como un pulsador. La salida del circuito permanece en estado bajo hasta que se produce una entrada de disparo, de ahí el nombre "monoestable", que significa "un estado estable". Este tipo de circuito es ideal para utilizarlo en un sistema de "pulsar para accionar".

Bistable Mode (or Schmitt Trigger)
Un modo biestable o lo que a veces se denomina Schmitt Trigger, tiene dos estados estables, alto y bajo. Si la entrada Trigger está baja, la salida del circuito pasa al estado alto. Tomando la entrada de Reset baja hace que la salida del circuito pase al estado bajo. Este tipo de circuito es ideal para su uso en una maqueta de trenes automatizada en la que el tren debe circular una y otra vez por el mismo tramo de vía. Se colocaría un pulsador (o un interruptor de láminas con un imán en la parte inferior del tren) en cada extremo de la vía, de modo que cuando el tren golpee uno de ellos, se activará o reiniciará el biestable. La salida del 555 controlaría un relay DPDT que se conectaría como un interruptor inversor para invertir la dirección de la corriente a la vía, invirtiendo así la dirección del tren.

Algunas de las maneras en las que son utilizados son:
-Cronometraje de precisión  
- Generación de impulsos  
- Temporización secuencial  
- Desfases de tiempo  
- Modulación de la anchura de los impulsos  


### Referencias:
-https://www.areatecnologia.com/electronica/circuito-integrado-555.html  
-https://www.ti.com/lit/ds/symlink/lm555.pdf?ts=1743051318575&ref_url=https%253A%252F%252Fwww.google.com%252F  
-https://www.jameco.com/Jameco/workshop/TechTip/555-timer-tutorial.html  
-https://www.555-timer-circuits.com/operating-modes.html  
-https://www.555-timer-circuits.com/datasheets/ne555.pdf  
-

