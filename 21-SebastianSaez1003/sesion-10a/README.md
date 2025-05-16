# sesion-10a
## Módulo de la mañana
Tratar de escuchar “Descartes” de Silvio Rodríguez.

Para comenzar, armamos cada uno un circuito PWM en el que el LED era de distinto color, siendo rojo, verde o azul respectivamente.

Para un LED verde tal vez es mucha resistencia una de 1k; la cambiaremos a 220.

El verde es el receptor de luz que tenemos mejor como seres humanos.

Acabamos de construir una rosa cromática, o al menos el funcionamiento de esta, ya que al juntar cada uno de estos LEDs, la luz se podía observar “mezclándose”.

Una pantalla de 7 segmentos 

El pixel es un constructo social.

RGB funciona de manera contextual, por eso sí es posible que mi pantalla me muestre un color café; en realidad no es café, sino que, por el contraste, parece café.

## Módulo después del break

Falstad es un simulador de circuitos.

En esta clase vamos a usar mucho de ejemplo a Minecraft. 

a Es una entrada.  
b es la corriente con la que se compara.  
c es la salida. 

Comparador de redstone: compáralo, cuánta redstone tiene de entrada vs. la B.



Nos pasaron un chip que se llama LM324N de 14 patas, 4 OP-AMP.

Un clásico de clásicos de los chips, tiene muchos usos distintos.

Amplificador operacional que se abrevia OP-AMP (vamos a pensar en esta como una caja negra, literalmente).

OP-AMP permite resolver operaciones matemáticas.

trabaja por comparación de voltaje

Es un cacho tener 2 polaridades de alimentación que es mucho más compleja de usar.



Cuando alguien pone "pinout" después del nombre de un chip, deja de buscar qué hace cada pata.

No todas las operaciones permiten funcionar con 12v y 0, por ejemplo, necesitan el 12v y -12v, el chip en sí, porque no funcionaría.

Estamos viendo el comparador para abrir nuestro léxico y poder ver cosas muy preciosas, probablemente la próxima semana.

El chip 741 tiene un solo OP-AMP.

Falstad sí es un simulador, no como Tinkercad o KiCad, solo simulador que cuando lo abramos va a tener un resonador RLC.

Con clic derecho va a aparecer todo lo que puedo agregar en Falstad.

Shift + V es para la fuente de poder.

Si le hago clic a la resistencia y pongo "view in new scope".

Control+A selecciona todo para poder borrarlo.

Vamos a poner un active building block, OPM ideal +, y después hacerle click para editar y ponerle max output 9, min output 0.

Este es activo, porque al contrario de los resistores, necesita energía directamente para alimentarlo.

Vamos a agregar un potenciómetro.

Los pasivos son aquellos que no necesitan energía para funcionar, como los potenciómetros.

Ese ejemplo era para división de voltaje, donde entre 2 resistencias, un cable que salga entre medio, a partir de una fórmula, se acabaría reduciendo el voltaje.

Potenciómetro para calibrar el umbral.

Seguir el esquemático que vimos en clases y lo aplique en mi protoboard, funcionando de la manera siguiente:

## encargo-20: pantallas de siete segmentos
Encontré los siguientes displays de 7 segmentos en la universidad.

Para poder mostrar al vendedor el precio de los productos y el precio total de lo que está comprando dentro del casino.

Para poder mostrar la temperatura a la cual es calentada y enfriada en el dispensador de agua de la universidad, la cual asumo es en grados Fahrenheit, porque sería una temperatura demasiado extrema si es que el agua estuviese siendo dispensada a 87 grados Celsius para beber.




## encargo-21: simulación de circuitos con 555 y/o comparadores hechos con opamps en Falstad

```txt
$ 1 0.000005 10.20027730826997 50 5 43 5e-11
165 112 128 272 128 6 0
165 368 128 416 128 6 8.992760336826677
g 432 384 432 416 0 0
g 208 352 208 416 0 0
R 176 0 176 -32 0 0 40 9 0 0 0.5
R 432 0 432 -32 0 0 40 9 0 0 0.5
w 208 288 208 352 0
w 464 288 464 384 0
w 176 0 176 48 0
w 432 0 432 48 0
w 112 224 80 224 0
w 80 224 80 256 0
w 80 256 112 256 0
w 112 160 32 160 0
w 368 160 336 160 0
w 368 256 336 256 0
w 336 256 336 160 0
w 336 160 336 112 0
w 496 192 560 192 0
r 32 160 32 64 0 1000
w 32 64 176 64 0
w 176 48 176 64 0
w 176 64 176 96 0
w 432 96 432 48 0
w 288 224 368 224 0
w 336 256 336 320 0
r 336 48 400 48 0 1000
374 336 112 336 48 0 0.6931 Light\sBrightness
c 336 320 336 352 4 4.7400000000000004e-7 8.999999999997684 0.001 0
g 336 352 336 416 0 0
c 48 304 48 336 4 1.53e-7 3.122189412549181 0.001 0
w 48 304 48 256 0
w 48 256 80 256 0
c 176 336 176 304 4 4.7400000000000004e-7 -5.999999999999782 0.001 0
w 176 288 176 304 0
g 48 336 48 416 0 0
g 176 336 176 416 0 0
w 240 160 240 64 0
w 240 64 176 64 0
w 240 192 288 192 0
w 288 192 288 224 0
w 32 160 -32 160 0
w -32 160 -32 96 0
w 496 160 496 48 0
w 496 48 432 48 0
c 432 352 432 320 4 4.7400000000000004e-7 -5.999999999999782 0.001 0
w 432 288 432 320 0
g 464 384 464 416 0 0
w 432 352 432 384 0
s -256 208 -256 288 0 1 true
s -176 208 -176 288 0 1 true
s -96 208 -96 288 0 1 true
w -256 288 -256 320 0
w -32 320 -32 256 0
w -32 256 48 256 0
w -96 288 -96 320 0
w -176 288 -176 320 0
r -256 96 -256 208 0 10000
r -176 112 -176 144 0 10000
r -176 160 -176 208 0 100000
r -96 112 -96 144 0 10000
r -96 160 -96 208 0 470000
w -176 96 -176 112 0
w -176 144 -176 160 0
w -96 96 -96 112 0
w -96 144 -96 160 0
w -32 96 -96 96 0
w -96 96 -176 96 0
w -176 96 -256 96 0
w -32 320 -96 320 0
w -96 320 -176 320 0
w -176 320 -256 320 0
w 400 48 432 48 0
r 560 224 560 288 0 1000
w 560 192 560 224 0
209 592 192 656 192 4 0.00009999999999999999 0.0009999999999781295 0.001 0 1
w 560 192 592 192 0
162 560 288 560 368 2 default-led 1 0 0 0.01
g 560 384 560 416 0 0
w 560 368 560 384 0
w 656 192 672 192 0
211 672 192 672 96 0 1 8000 1
o 81 64 0 4098 10 0.1 0 1

```
