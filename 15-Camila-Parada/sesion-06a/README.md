# ⋆₊˚⊹♡ Clase 06a - Circuito experimental ♡⊹˚₊⋆
##### _Martes 15/04/2024_ 
Grupo 08 - Isabella Gutierrez, Camila Parada

***

### Introducción

<br>
 
Este proyecto surge como inspiración de los circuitos eléctricos y experimentos vistos en clase. Los resultados obtenidos nos han impulsado en la creación de este sintetizador que tiene como base el **oscilador “Atari Punk Console”**, generando una versión,  la cual requiere de **un usuario que pueda conectarse a dicha máquina, para ser la resistencia y desencadenar el sonido**, a través del uso del parlante. Para ello se han realizado modificaciones en los componentes, (tipo, capacidad, entre otros) y la estructura física, permitiendo alterar los sonidos generados por la **conexión humano-máquina.**

***

### Investigación

<br>

Como fue mencionado anteriormente, el proceso del aparato se remonta a los **experimentos realizados en las clases** (desde la clase 03a en adelante). Tras haber tomado el proceso y los resultados, proseguimos a tomar enfoque en qué tipo de dispositivo podemos realizar, con los conocimientos adquiridos, destacándose por desarrollar un sintetizador que pueda interactuar de forma más íntima con el usuario, y **generar una experiencia personal que pueda ser trabajada de forma única o grupal**. Una máquina que pueda percibir como la energía (lo invisible) traspasa los cuerpos, un **proceso que no es capaz de ser percibibo por los sentidos del ser humano**, y lo transmuta y emite en forma de vibraciones y sonido.perteneciente a quien se conecte.


Dentro de los incios consideramos evaluar y ver que piezas podríamos usar. Para ello catalogamos los sensores según el uso que podemos darles:

### Sensores de interacción

<br>

- **Sensor infrarrojo** (presencia y cercanía al objeto):Es un dispositivo **optoelectrónico** que detecta y mide la radiación infrarroja emitida por los objetos. Para ello requiere de los "Rayos infrarrojos", un tipo de radiación electromagnética que posee una menor longitud de onda que la luz visible (que nuestros ojos son incapaces de percibir la radiación) pero se puede detectar como una **sensación de calor.**
  Pudimos observar el funcionamiento de este sensor al estudiar los elementos que componen el **“dron de luces”** presentado en la sesión “05a”, el cuál vuela a una altura variable que es continuamente modificada, por la **información que recibe el sensor al tener contacto con cualquier superficie** (una mano, el suelo, etc.), siendo impredecible su actuar.
  El uso que decidimos destinar a esta pieza es el de activar la máquina cuando identifica una presencia u objeto que se aproxima a cierta distancia del dispositivo.

<br>

https://youtu.be/QwVMbZH8AtY?si=JZScxDciYkhHqdmQ

<br>

_▼ Video de referencia de cómo sirve. Obtenido de Youtube - ExpCaserosMix_

<br>

![WhatsApp Image 2025-04-15 at 6 29 07 AM](https://github.com/user-attachments/assets/05fccfdd-27ff-4717-b078-9a3a9681903d)
_▼ Dron abierto y diagramado_

<br>

 - **Cables Caimán:** Son utilizados para hacer pasar corriente, sin necesidad de soldar. Para este proyecto se usarán para ser conectada a la persona, con finalidad de transformarse en una resistencia variable y cuyo paso de corriente se traduzca en sonido a través del parlante y sus vibraciones. Esta información es derivada de los experimentos realizados el día 28 de marzo.

<br>

https://github.com/user-attachments/assets/548976e8-01af-4795-969c-82976046d79a

<br>

### Sensores de control

<br>

 - **Interruptor:** es un tipo de interruptor mecánico que se activa deslizando una pieza para conectar o desconectar un circuito eléctrico. 
   
<br>

 - **Potenciometro:** es un componente que actúa como una resistencia variable, es decir, que su resistencia se puede modificar manualmente.

<br>

 - **Condensadores:** El Condensador Cerámico es un componente electrónico pasivo que es capaz de almacenar una carga eléctrica, se comporta como un filtro que bloquea la corriente directa y permite que la corriente alterna fluya sin ningún problema.

***

### Registro visual: avances, procesos, errores

<br>

![WhatsApp Image 2025-04-14 at 9 57 12 PM](https://github.com/user-attachments/assets/c299ac5b-6c52-439f-9335-00f9782de4f2)

_▼ Fotografía del circuito - Primera parte_


![WhatsApp Image 2025-04-14 at 9 16 33 PM](https://github.com/user-attachments/assets/3dd10f62-5c41-4f81-95bd-aff92467df84)

_▼ Diagrama - Primera parte_

![WhatsApp Image 2025-04-14 at 10 10 57 PM](https://github.com/user-attachments/assets/03d5d335-aec2-4837-8cb9-53150997acca)


https://github.com/user-attachments/assets/01c84a79-8003-42ce-b24c-b0f0ae260781


En esta ocasión probamos conectando un LDR al caimán, donde el sonido queda estático  


https://github.com/user-attachments/assets/6e3b1046-6087-439d-90f5-5783a0b47423

 Pero nos dimos cuenta de que faltaba un componente!!!

 ![WhatsApp Image 2025-04-15 at 12 00 28 AM](https://github.com/user-attachments/assets/979a5d7e-6f49-4dcd-9412-947ec612061e)

## Arreglo de errores
 ![WhatsApp Image 2025-04-15 at 12 06 05 AM](https://github.com/user-attachments/assets/041c3b2a-5799-4a44-9650-d4b17ef6e887)

 

https://github.com/user-attachments/assets/547e6b82-f461-43aa-b481-85769ec32518

## Experimentación 

Cambiamos el **LDR** que estaba en los cables amarillos, por un **pedazo de membrillo**, y funciona!!!

![WhatsApp Image 2025-04-15 at 12 16 26 AM](https://github.com/user-attachments/assets/f76a36e3-8174-494a-9bb7-d52c60df6218) 

https://github.com/user-attachments/assets/fafc23d4-49af-4e43-bb54-dee9a7d308ee

## Primera parte del esquema corregido

![WhatsApp Image 2025-04-15 at 3 10 30 AM](https://github.com/user-attachments/assets/47625dfd-8b80-44e5-ad6f-5b12937dec05)

## Bill of materials esquema 1
 

| Componente       | Qty | Nombre(s) | Valor/tipo |
|-----------------------|---------|------------|----------------|
| Chip 555              | 1       | U1         |                |
| Resistencia           | 2       | R1, R2     | Variable, 1k   |
| Condensadores         | 3       | C1,C2,C3   | 100n, 100u     |
| Parlante              | 1       |  LS1       |      2w        |

## Esquema completo

![WhatsApp Image 2025-04-15 at 3 31 32 AM (1)](https://github.com/user-attachments/assets/132ddb01-a23e-4f2c-a78a-8fe81fba02f0)


## Bill of material final

| Componente       | Qty | Nombre(s) | Valor/tipo |
|-----------------------|---------|------------|----------------|
| Chip 555                 | 2       | U1, U2         |                |
| Resistencia              | 4       | R1, R2, R3, R4        | Variable, 1k, 10k, 1k      |
| Condensadores      | 6       | C1, C2, C3, C4, C5, C6         | 100n, 100n, 1uF, 470n, 470n, 10uF        |
| Parlante                  | 1       |  LS1         |      2w          |
| Potenciómetro                  | 1       |  P1         |      B500K          |
| Led                  | 1       |  L1         |      3,3w          |
| Interruptor                  | 1       |  IN1         |               |









   


