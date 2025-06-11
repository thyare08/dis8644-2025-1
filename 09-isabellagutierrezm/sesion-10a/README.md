# sesion-10a

13.mayo.2025

## Primer bloque: Trabajo en clases

1. Armar un circuito PWM cada uno
2. Juntarse en grupos de tres, cada uno con un LED rojo, verde o azul
3. Combinar colores

![circuito PWM](https://github.com/isabellagutierrezm/dis8644-2025-1/blob/main/09-isabellagutierrezm/sesion-10a/archivos/circuito%20PWM.jpeg)

Utilizamos caimanes para pasar la corriente eléctrica al LED

<https://github.com/user-attachments/assets/19bd91f4-5c56-448c-acb6-a0d18600ded4>

Vamos juntando los LED para crear colores

![colores](https://github.com/isabellagutierrezm/dis8644-2025-1/blob/main/09-isabellagutierrezm/sesion-10a/archivos/colores.jpeg)

 Se logró!!!

- **LED RGB:** Múltiples combinaciones de los tres colores primarios ópticos, rojo, verde y azul, superpuestos entre sí , los colores se mezclan y el brillo mezclado es igual a la suma de las dos luces.
![RGB](https://github.com/isabellagutierrezm/dis8644-2025-1/blob/main/09-isabellagutierrezm/sesion-10a/archivos/RGB.jpeg)

- **Redstone:** Es un elemento fundamental que permite la creación de mecanismos y circuitos en Minecraft, el cual es de color rojo.

- **LM324 OP-AMP:** Es un amplificador operacional con 4 entradas diferentes, es decir se puede hacer cuatro funciones en uno.
- **Falstad:** Es un simulador de circuitos

![falsat](https://github.com/isabellagutierrezm/dis8644-2025-1/blob/main/09-isabellagutierrezm/sesion-10a/archivos/falsat.png)

![circuitofalstad](https://github.com/isabellagutierrezm/dis8644-2025-1/blob/main/09-isabellagutierrezm/sesion-10a/archivos/circuitofalstad.png)

- **Pantalla de siete segmentos:** Son dispositivos que representan números del 0 al 9, como por ejemplo temporizadores o calculadoras.
![7 segmentos](https://github.com/isabellagutierrezm/dis8644-2025-1/blob/main/09-isabellagutierrezm/sesion-10a/archivos/7%20segmentos.jpeg)

## Encargo 20: Pantalla de siete segmentos

- Foto tomada en el casino de la escuela, el martes 13 de mayo
![microondas](https://github.com/isabellagutierrezm/dis8644-2025-1/blob/main/09-isabellagutierrezm/sesion-10a/archivos/microondas.jpeg)

-Foto tomada de la temperatura de mi refrigerador, miércoles 14 de mayo
![refri](https://github.com/isabellagutierrezm/dis8644-2025-1/blob/main/09-isabellagutierrezm/sesion-10a/archivos/refri.jpeg)

-Video tomado en la estación de metro, jueves 15 de mayo

<https://github.com/user-attachments/assets/cb71c247-3422-4a41-a363-738bec171e5a>

- Foto tomada de la temperatura de la sala, viernes 16 de mayo
![temperatura sala](https://github.com/isabellagutierrezm/dis8644-2025-1/blob/main/09-isabellagutierrezm/sesion-10a/archivos/temperatura%20sala.jpeg)

## Circuito 555 en falstad

Para ello utilice el circuito Monoestable botón más LED

![circuitomonostable](https://github.com/isabellagutierrezm/dis8644-2025-1/blob/main/09-isabellagutierrezm/sesion-10a/archivos/circuitomonostable.png)

```txt
$ 1 0.000005 10.20027730826997 50 5 50 5e-11
165 256 208 400 208 14 2.943329998186235
w 256 240 224 240 0
w 256 304 224 304 0
w 224 304 224 384 0
c 224 384 224 448 4 0.00009999999999999999 2.941200069375345 0.001 0.1
g 224 448 224 480 0 0
c 320 368 320 432 4 0.00009999999999999999 6.767858900456613 0.001 0
g 320 432 320 464 0 0
w 384 272 464 272 0
w 224 304 224 240 0
172 320 176 320 80 0 7 9 9 0 0 0.5 Voltage
r 224 240 224 176 0 10000
w 224 176 224 144 0
w 224 144 384 144 0
w 384 240 384 144 0
w 224 144 144 144 0
w 144 144 144 176 0
r 144 176 144 240 0 10000
w 224 304 144 304 0
w 256 336 224 336 0
w 144 240 144 352 0
s 144 352 144 400 0 1 false
g 144 400 144 464 0 0
w 464 272 464 288 0
162 464 288 464 352 2 default-led 1 0 0 0.01
r 464 352 464 400 0 10000
g 464 400 464 432 0 0```


```text
Plain text in a code block
```



