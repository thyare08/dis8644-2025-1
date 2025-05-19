# sesion-10a <!-- This feels so odd without the vertical lines and the ">" -->

## Apuntes
###### ${\color{#3d3d44}Se \ recomienda \ usar \ modo \ oscuro, \ hay \ palabras \ en \ color \ blanco \ que \ de \ otra \ forma \ no \ son \ visibles.}$ <br/>
###### ${\color{#3d3d44}The \ use \ of \ dark mode \ is \ recommended, \ there's \ white \ colored \ text \ that \ otherwise \ is \ not \ visible.}$ <br/>

### RGB LED
<img align="left" src="./archivos/rgb-led-pinout.jpg" width=400> </br></br> Combinan 3 LEDs de distintos colores (rojo, verde y azul) en un mismo componente, cada uno de estos LEDs brilla con distinta intensidad para producir el color deceado, ya que al estar tan cerca se mescla la luz que cada uno emite </br></br> En los LED RGB, los 3 LEDs de colores suelen venir en 2 confuguraciones: cátodo y ánodo común </br></br></br></br>

### Display de 7 segmentos
<img align="left" src="./archivos/7segDis.jpg" width=400> </br></br></br></br></br> Similares a los LEDs RGB en que contienen múltiples LEDs más pequeños dentro, sin embargo estos displays emplean LEDs del mismo color en distintas ubicaciones para formar distintos números y/o letras </br></br></br></br></br></br></br>

> ### Codificador(encoder) y [decodificador(decoder)](https://youtu.be/HHQFI8R1iZc?si=c0AfhkyOAGCwZzmC)
> En un display de 7 segmentos hay que controlar 7 LEDs, pero ¿qué pasa si tenemos varios displays de 7 segmentos trabajando juntos para mostras números más grandes o pantallas de más alta resolución? necesitaríamos una cantidad enorme de pines GPIO en nuestros microcontroladores (arduino, esp32, raspberry pi pico, etc), sin mencionar la cantidad de cables y espacio. </br> Es por esto que se emplean encoders y decoders
> * Encoders: 
> * Decoders: 

### RGB v/s YCMK

### Comparador Minecraft
> ### LM324 op amp

### Voltaje negativo

### Micrófono Electret

### Componentes activos v/s pasivos

### Divisor de voltaje

### Other things: <!-- Things to organize + random stuff -->
> #### Buffer
-----------------------------------------------------------------------------------------------------------
## Encargo 20 <!-- subir fotos de su propia autoría de pantallas de siete segmentos, y otras variantes que encuentren en su vida cotidiana. les pedimos al menos 3 fotos de distintas pantallas. pueden partir de la base de las que ya subieron hoy a discord. incluir información sobre dónde y cuándo fue capturada la imagen. -->
### Displays de 7 segmentos


-----------------------------------------------------------------------------------------------------------
## Encargo 21 <!-- simular circuitos que hemos visto en clases con chips 555 y/o circuitos comparadores usando el simulador de Falstad disponible en -->
### Simulación de circuitos en Falstad

``` comparator + volatage divider
$ 1 0.000005 10.20027730826997 66 5 43 5e-11
r 224 224 288 224 0 1000
162 288 224 320 224 2 default-led 1 0 0 0.01
g 320 224 320 256 0 0
R 0 192 0 112 0 0 40 9 0 0 0.5
403 48 80 176 144 0 0_64_0_4099_0.0000762939453125_0.00009765625_-1_2_0_3
a 112 224 208 224 9 9 0 1000000 4.945500000000001 3.3533291106226013 100000
174 0 288 80 192 1 100000 0.5495000000000001 potenciometro umbral
g 0 288 0 304 0 0
w 80 240 112 240 0
374 208 160 112 160 0 0.8317000000000001 LDR
R 592 128 592 48 0 0 40 9 0 0 0.5
R 208 160 208 112 0 0 40 9 0 0 0.5
r 112 160 48 160 0 10000
w 112 208 112 160 0
g 48 160 48 192 0 0
w 208 224 224 224 0
403 16 256 144 320 0 8_64_0_4099_5_0.00009765625_-1_2_8_3
403 192 240 320 304 0 15_64_0_4099_0.00030517578125_0.00009765625_-1_2_15_3
403 160 256 288 320 0 13_64_0_4099_10_0.00009765625_-1_2_13_3
o 8 64 0 4099 10 0.00009765625 0 6 8 3 13 0 13 3 15 0 15 3
```

