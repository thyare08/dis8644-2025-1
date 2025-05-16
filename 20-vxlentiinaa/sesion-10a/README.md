# sesion-10a

13-05-2025

## Apuntes

* Aprendimos la nueva aplicación en línea Falstad.com
* LED RGB: Consiste en la combinación de los tres colores primarios Azul-Verde-Rojo. En el cual puede producir diversos colores en base a los colores primarios.
* Amplificador operacional: OP-AMP
* Chip de 14 patas: LM 324
* Con el mismo chip se pueden hacer 4 operaciones a la vez


![IMG_4367](https://github.com/user-attachments/assets/1ed71475-54de-4ff8-844b-6d07bffe91f9)

![IMG_4368](https://github.com/user-attachments/assets/08c29ffa-42f4-43ab-8460-98ee3a1a92fa)

![IMG_4369](https://github.com/user-attachments/assets/495eda8f-bf05-4948-a9a5-8b4c6ec8e9c6)

## Encargo 20

![IMG_4314](https://github.com/user-attachments/assets/e1ac13bf-eb88-4450-a50f-b65a30ccc8a5)

* Fue capturada el 13/05 en República 180, es el ascensor de la universidad, algo que comunmente usamos con mis amigas, nos acordamos que estaba la pantalla de 7 segmentos. 

![IMG_4317](https://github.com/user-attachments/assets/8f0cfaf8-143f-497f-ad3f-9c536c810322)

* Fue capturada el 13/05 en la sala 203 de la FAAD, es el reloj de mi amiga, nos dimos cuenta que estaba la pequeña pantalla de 7 segmentos en su reloj.

 ![IMG_4316](https://github.com/user-attachments/assets/634a1759-55b2-4342-9ff2-9cf04628a0e1)

 * Fue capturada el 13/05 en el Dunkin Donuts de República, le estaban preparando el café a mis amigas y nos dimos cuenta que el temporizador que estaba arriba de la máquina tenía la pantalla de 7 segmentos.

## Encargo 21

### Circuito PWM
<img width="1440" alt="Captura de pantalla 2025-05-15 a la(s) 10 31 51 p m" src="https://github.com/user-attachments/assets/332314b7-4c77-449b-9828-e8feb7bd27ac" />

<img width="1440" alt="Captura de pantalla 2025-05-15 a la(s) 10 33 47 p m" src="https://github.com/user-attachments/assets/15c09740-7b1a-49cf-8528-39878650316f" />

$ 1 0.000005 1.3241202019156522 72 5 50 5e-11
165 560 272 592 272 14 8.992760336826649
c 464 400 464 464 4 100 0.0000012381682351598956 0.001 0
g 656 432 656 560 0 0
g 464 464 464 544 0 0
c 624 432 624 512 4 104 0.00003195110877830514 0.001 0
g 624 512 624 560 0 0
r 688 336 816 336 0 1000
162 816 336 816 432 2 default-led 1 0 0 0.01
g 816 432 816 480 0 0
w 560 304 400 304 0
r 400 304 400 128 0 1000
w 624 240 688 240 0
w 688 240 688 304 0
w 624 240 624 128 0
R 624 128 624 80 0 0 40 9 0 0 0.5
d 208 304 208 352 2 default
d 144 352 144 304 2 default
w 208 304 144 304 0
174 208 352 160 368 1 100000 0.6584000000000001 Resistance
w 400 128 624 128 0
w 560 368 560 400 0
w 400 304 208 304 0
w 560 400 464 400 0
w 176 368 176 400 0
w 176 400 464 400 0
o 1 64 0 4099 0.0000762939453125 0.000390625 0 2 1 3
o 6 64 0 4099 10 0.025 1 2 6 3
o 10 64 0 4099 0.625 0.000390625 2 2 10 3


## Circuito APC Modificado Grupo 1

<img width="1440" alt="Captura de pantalla 2025-05-15 a la(s) 11 11 19 p m" src="https://github.com/user-attachments/assets/053f0d19-2e1f-4518-b114-ec5f939f4ebb" />

$ 1 0.000005 69.34413510434165 66 5 50 5e-11
165 416 240 480 240 14 0
165 720 240 752 240 14 8.999999910000065
w 544 304 624 304 0
w 624 304 624 336 0
w 624 336 720 336 0
w 480 208 544 208 0
w 544 208 544 272 0
R 544 64 544 16 0 0 40 9 0 0 0.5
r 368 160 368 240 0 1000
w 416 272 368 272 0
w 368 272 368 240 0
w 368 272 320 272 0
174 320 272 320 352 1 1000 0.6683 Resistance
w 416 336 416 368 0
w 416 336 352 336 0
w 352 336 352 368 0
w 352 368 320 368 0
c 352 368 352 448 4 474 0.00006008737446298358 0.001 0
g 352 448 352 496 0 0
209 240 272 240 368 4 0.00001 0.08823588320935538 0.001 0.1 1
w 240 272 320 272 0
w 240 272 208 272 0
s 240 368 240 448 0 0 false
209 208 272 128 272 4 0.000001 0.0882358832093572 0.001 0 1
g 512 400 512 496 0 0
c 480 400 480 464 4 474 0.0000831472434956036 0.001 0
g 480 464 480 496 0 0
s 128 272 128 352 0 0 false
w 128 352 128 448 0
w 128 448 240 448 0
g 128 448 128 496 0 0
w 720 272 720 368 0
w 720 272 672 272 0
r 672 272 672 192 0 1000
374 672 192 672 128 0 0.5743 Brillo
w 672 272 672 384 0
c 672 384 672 448 4 474 0.000012316138758551667 0.001 0
g 672 448 672 496 0 0
w 784 208 848 208 0
w 848 208 848 272 0
w 784 208 784 112 0
w 672 128 672 112 0
w 672 112 784 112 0
w 672 112 544 112 0
w 480 208 480 112 0
w 368 160 368 112 0
w 368 112 480 112 0
w 480 112 544 112 0
w 544 112 544 64 0
g 816 400 816 496 0 0
c 784 400 784 464 4 474 0.0000831472434956036 0.001 0
g 784 464 784 496 0 0
209 848 304 976 304 4 0.00009999999999999999 -2.4868995751603507e-14 0.001 0 1
162 880 368 944 368 2 default-led 1 0 0 0.01
w 848 304 880 368 0
w 944 368 976 304 0
211 976 304 1104 304 0 1 8000 1


