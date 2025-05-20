# sesion-10a 13/05

## apuntes clase

Falstad.com -> un simulador de circuitos electrónicos.

LED RGB ->  es la combinación de los tres colores primarios Azul-Verde-Rojo.  lo cual hace que se produzcan distintos colores en base a los colores RGB.

Amplificador operacional -> OP-AMP

Chip de 14 patas -> LM 324
se pueden hacer 4 operaciones a la vez

![IMG_1425](https://github.com/user-attachments/assets/2e31a9aa-6ccb-468c-9404-25dd68033f9c)

![IMG_1426](https://github.com/user-attachments/assets/92d332e0-eb6f-4312-ab83-35c9746d215d)

![IMG_1259](https://github.com/user-attachments/assets/6b1d05f0-ab4f-4eba-8126-5d94079129c7)


## encargo-20: pantallas de siete segmentos

### imagen 1

![pantalladesietesegmentos ejemplo1](https://github.com/user-attachments/assets/83342878-c882-40ef-8ee5-575604fc8cb7)

fue capturada el 13/05 en sevinex, con mis amigas recordamos que ahí tenian un reloj, con una pantalla de siete segmentos.

### imagen 2

 ![pantalladesietesegmentos ejemplo2](https://github.com/user-attachments/assets/de419e1f-3588-4ac4-bb79-ba0e6d9035a4)

fue capturada el 13/05 en el dunkin donuts de república, estabamos comprando cafe con mis amigas.

### imagen3

![pantalladesietesegmentos ejemplo3](https://github.com/user-attachments/assets/ea831424-63c3-4f73-b4fd-f0a276a2f13f)

fue capturada el 15/05 estación de metro pedro de valdivia.
### imagen 4

![pantalladesietesegmentos ejemplo4](https://github.com/user-attachments/assets/44b6f408-eb1b-46c3-8f24-5adefc5f37a1)

fue capturada el 15/05 en mi casa haciendo trabajos.

## encargo-21: simulación de circuitos con 555 y/o comparadores hechos con opamps en Falstad

simular circuitos que hemos visto en clases con chips 555 

### Atari punk sonsole

M<img width="1470" alt="ataripunkconsole falstad" src="https://github.com/user-attachments/assets/d2c52a84-b484-4196-b8fa-cd54ef0c28cf" />

```txt
$ 1 0.000015625 21.593987231061412 66 5 50 5e-11
165 432 384 512 384 14 8.999999910000001
165 752 384 896 384 14 0
r 688 368 688 304 0 1000
r 688 304 688 240 0 1000
r 368 352 368 272 0 1000
r 208 480 208 416 0 1000
w 432 416 368 416 0
w 368 352 368 416 0
w 752 416 688 416 0
w 688 368 688 416 0
w 432 480 368 480 0
w 432 512 368 512 0
w 368 480 368 512 0
w 368 512 208 512 0
w 208 512 208 480 0
w 208 416 368 416 0
w 560 416 592 416 0
w 592 416 592 352 0
w 592 352 496 352 0
w 496 352 496 272 0
g 528 544 528 672 0 0
g 848 544 848 672 0 0
w 688 416 688 480 0
w 688 480 688 512 0
w 688 512 752 512 0
w 560 448 656 448 0
w 656 448 656 480 0
w 880 416 912 416 0
w 912 416 912 352 0
w 912 352 816 352 0
w 816 352 816 272 0
w 496 272 496 256 0
w 816 272 816 240 0
w 496 256 496 240 0
w 368 272 368 240 0
w 368 240 496 240 0
w 688 240 816 240 0
w 816 240 816 192 0
R 624 144 720 144 0 0 40 9 0 0 0.5
w 496 240 496 144 0
w 496 144 624 144 0
w 816 192 624 192 0
w 624 192 624 144 0
c 368 512 368 608 4 0.00009999999999999999 5.555337401396824 0.001 0
c 496 544 496 608 4 0.00009999999999999999 5.999999997918349 0.001 0
c 688 512 688 640 4 0.00009999999999999999 0.044776119402986446 0.001 0
c 816 544 816 640 4 0.00009999999999999999 5.999999997999807 0.001 0
g 368 608 368 672 0 0
g 496 608 496 672 0 0
g 816 640 816 672 0 0
g 688 640 688 672 0 0
209 880 448 1024 448 4 0.00001 0 0.001 0 1
w 656 480 752 480 0
211 1024 448 1136 448 0 1 8000 1

```
### PWM


<img width="1470" alt="circuitopwm falstad" src="https://github.com/user-attachments/assets/2f288c33-404a-4844-a7bc-104513fe4f29" />

```txt
1 0.000005 10.20027730826997 50 5 50 5e-11
165 320 304 464 304 14 0
R 448 192 448 144 0 0 40 9 0 0 0.5
w 384 272 384 192 0
w 384 192 448 192 0
w 448 336 448 192 0
r 448 368 592 368 0 1000
162 592 368 592 432 2 default-led 1 0 0 0.01
g 592 432 592 528 0 0
c 384 464 384 560 4 0.000104 5.999108982982355 0.001 0
g 384 560 384 592 0 0
g 416 464 416 592 0 0
w 320 432 128 432 0
w 320 400 160 400 0
174 96 352 160 384 1 100000 0.5 Resistance
w 128 432 128 384 0
d 160 320 160 352 2 default
d 96 352 96 320 2 default
w 96 320 160 320 0
w 160 320 240 320 0
w 240 320 240 336 0
w 240 336 320 336 0
g 128 560 128 592 0 0
c 128 464 128 560 4 0.000104 4.234031265341355 0.001 0
w 128 464 128 432 0
w 160 400 128 432 0
r 240 320 240 192 0 1000
w 240 192 384 192 0

```
