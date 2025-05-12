# sesion-03a

![1](https://github.com/user-attachments/assets/69f54fe6-7dd6-473d-87d6-c6a07f6bf0ae)

![2](https://github.com/user-attachments/assets/e71a1f10-f2d2-4d44-983a-21cda04da739)

| prefijo | notación científica | valor | abreviatura |
| --- | --- | --- | --- |
| giga | 1*10^9 | 1.000.000.000 | g |
| mega | 1*10^6 | 1.000.000 | M |
| kilo | 1*10^3 | 1.000 | k |
| unidad | 1*10^0 | 1 | u |
| mili | 1*10^-3 | 0,001 | m |
|  micro | 1*10^-6 | 0,000001 | u |
| nano | 1*10^-9 | 0,000000001 | n |
| pico | 1*10^-12 | 0,000000000001 | p |

## chip 555

data sheet

se lee de una forma especifica y es un oscilador astable
![4](https://github.com/user-attachments/assets/6716431b-a7fe-444c-8d1b-b2e481a65173)
circuito astable con chip 555 y se agrega potenciómetro para variar el tiempo del periodo

![3](https://github.com/user-attachments/assets/4b85a4f8-afa6-4024-bb37-ef84a45b133d)

## encargo-06

zeichnungen des patienten o.t.

de 1983 en Berlín, Alemania.

personalmente el disco no es de mi gusto. lo que más me llama la atención es la forma en que lleva al extremo el uso de materiales no convencionales como instrumentos, creando un sonido agresivos y ruidosos.

en este álbum, utiliza chatarra metálica, tuberías, entre otros y la percusión hecha con objetos de construcción que considero que es interesante la composición de sus instrumentos musicales, son totalmente experimentales.

en ciertas canciones juegan con la repetición rítmica creando patrones que aparecen y desaparecen. me parece increíble lo que logran con esta combinación de sonidos que totalmente es un sello y se logra diferenciar de todos los otros estilos de música que he escuchado antes.

## encargo-07

patitas -> pines

pin 1 -> GND (tierra) -> se conecta al negativo.

pin 2 -> TRIG (disparo) -> activa el temporizador.

pin 3 -> OUT (salida) -> salida del 555, aca se puede encender un LED.

pin 4 -> RST (reset) -> reinicia el chip cuando se pone en bajo 0V. Si no lo usás, conectalo a VCC.

pin 5 -> CTRL (control) -> modifica el punto de referencia interno. (se deja sin usar y se pone un capacitor de 10nF a GND para evitar ruido)

pin 6 -> THRS (umbral) -> detecta cuándo se debe terminar el pulso.

pin 7 -> DISCH (descarga) -> descarga el capacitor. (usado en modos aestable y monoestable)

pin 8 -> VCC (alimentación) -> se conecta al positivo.

configuración

astable -> oscilador

monoestable -> pulso en base a una señal

biestable -> funciona como flip-flop o interruptor

se puede calcular en base a las resistencias y el capacitador
