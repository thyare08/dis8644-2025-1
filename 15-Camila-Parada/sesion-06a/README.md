# ⋆₊˚⊹♡ Clase 06a - Circuito experimental ♡⊹˚₊⋆

Martes 15/04/2024

Grupo 08 - Isabella Gutierrez, Camila Parada

***

## Introducción

Este proyecto surge como inspiración de los circuitos eléctricos y experimentos vistos en clase. Los resultados obtenidos nos han impulsado en la creación de este sintetizador que tiene como base el **oscilador “Atari Punk Console”**, generando una versión,  la cual requiere de **un usuario que pueda conectarse a dicha máquina, para ser la resistencia y desencadenar el sonido**, a través del uso del parlante. Para ello se han realizado modificaciones en los componentes, (tipo, capacidad, entre otros) y la estructura física, permitiendo alterar los sonidos generados por la **conexión humano-máquina.**

***

### Investigación

Como fue mencionado anteriormente, el proceso del aparato se remonta a los **experimentos realizados en las clases** (desde la clase 03a en adelante). Tras haber tomado el proceso y los resultados, proseguimos a tomar enfoque en qué tipo de dispositivo podemos realizar, con los conocimientos adquiridos, destacándose por desarrollar un sintetizador que pueda interactuar de forma más íntima con el usuario, y **generar una experiencia personal que pueda ser trabajada de forma única o grupal**. Una máquina que pueda percibir como la energía (lo invisible) traspasa los cuerpos, un **proceso que no es capaz de ser percibibo por los sentidos del ser humano**, y lo transmuta y emite en forma de vibraciones y sonido.perteneciente a quien se conecte.

Dentro de los incios consideramos evaluar y ver que piezas podríamos usar. Para ello catalogamos los sensores según el uso que podemos darles:

### Sensores de interacción

- **Sensor infrarrojo** (presencia y cercanía al objeto):Es un dispositivo **optoelectrónico** que detecta y mide la radiación infrarroja emitida por los objetos. Para ello requiere de los "Rayos infrarrojos", un tipo de radiación electromagnética que posee una menor longitud de onda que la luz visible (que nuestros ojos son incapaces de percibir la radiación) pero se puede detectar como una **sensación de calor.**
  Pudimos observar el funcionamiento de este sensor al estudiar los elementos que componen el **“dron de luces”** presentado en la sesión “05a”, el cuál vuela a una altura variable que es continuamente modificada, por la **información que recibe el sensor al tener contacto con cualquier superficie** (una mano, el suelo, etc.), siendo impredecible su actuar.
  El uso que decidimos destinar a esta pieza es el de activar la máquina cuando identifica una presencia u objeto que se aproxima a cierta distancia del dispositivo.

<https://youtu.be/QwVMbZH8AtY?si=JZScxDciYkhHqdmQ>

Video de referencia de cómo sirve. Obtenido de Youtube - ExpCaserosMix

![WhatsApp Image 2025-04-15 at 6 29 07 AM](https://github.com/user-attachments/assets/05fccfdd-27ff-4717-b078-9a3a9681903d)

Dron abierto y diagramado

- **Cables Caimán:** Son utilizados para hacer pasar corriente, sin necesidad de soldar. Para este proyecto se usarán para ser conectada a la persona, con finalidad de transformarse en una resistencia variable y cuyo paso de corriente se traduzca en sonido a través del parlante y sus vibraciones. Esta información es derivada de los experimentos realizados el día 28 de marzo.

<https://github.com/user-attachments/assets/548976e8-01af-4795-969c-82976046d79a>

### Sensores de control

- **Interruptor:** es un tipo de interruptor mecánico que se activa deslizando una pieza para conectar o desconectar un circuito eléctrico.

- **Potenciometro:** es un componente que actúa como una resistencia variable, es decir, que su resistencia se puede modificar manualmente.

- **Condensadores:** El Condensador Cerámico es un componente electrónico pasivo que es capaz de almacenar una carga eléctrica, se comporta como un filtro que bloquea la corriente directa y permite que la corriente alterna fluya sin ningún problema.

***

### Desarrollo: avances, procesos, videos e imágenes

![WhatsApp Image 2025-04-14 at 9 57 12 PM](https://github.com/user-attachments/assets/c299ac5b-6c52-439f-9335-00f9782de4f2)

Fotografía del circuito - Primera parte

<https://github.com/user-attachments/assets/ce2a415f-f977-404f-ae49-371a6b5f4876>

Video del circuito funcionando

![WhatsApp Image 2025-04-14 at 9 16 33 PM](https://github.com/user-attachments/assets/3dd10f62-5c41-4f81-95bd-aff92467df84)

Diagrama - Primera parte

#### Bill of materials diagrama 1

| Componente       | Qty | Nombre(s) | Valor/tipo |
|-----------------------|---------|------------|----------------|
| Chip 555              | 1       | U1         |                |
| Resistencia           | 2       | R1, R2     | Variable, 1k   |
| Condensadores         | 3       | C1,C2,C3   | 100n, 100u     |
| Parlante              | 1       |  LS1       |      2w        |

***

El siguiente avance consistió en armar la seguna parte del circuito Atari, conectardo otro chip 555 pero con la modificación de que se le agrega un interruptor al final del camino, este conectando a 2 condensadores cerámicos polarizados de distintos valores en cada camino. Puesto que este circuito como tal funcionaba de forma estática al conectar una fruta a los cables tipo caimán, probamos a cambiarlo por un un LDR. El resultado para ambos circuitos fue el mismo: un sonido que se mantiene independiente de el uso del interruptor, solo varía segun lo que se conecte a los caimanes.

<https://github.com/user-attachments/assets/c9100e24-443c-45cd-bf76-fc65ae19f9fb>

Video de la primera versión del segundo citcuito

<https://github.com/user-attachments/assets/6e3b1046-6087-439d-90f5-5783a0b47423>

Video de la segunda versión del segundo citcuito (con LDR conectado a caimán)_

Tras ver las fallas que se presentaban, realicé el circuito tal cual cómo se había mostrado en clases todo este tiempo (usando como resistencias experimentales sensores LDR).
Al analizar el circuito y sus partes se llegó a la conclusión de ver una parte faltante.

<https://github.com/user-attachments/assets/73094c17-99c1-47d2-8942-8a9a091a37b1>

Circuito original del Atari Punk Console con sensores LDR_

![WhatsApp Image 2025-04-15 at 12 00 28 AM](https://github.com/user-attachments/assets/979a5d7e-6f49-4dcd-9412-947ec612061e)

Detalle de la parte faltante del circuito_

Una vez agregada esta parte al circuito solo quedó volver a colocar el interruptor, donde un camino presenta un potenciometro mientras que el otro solo tiene una resistencia y un condensador cerámico polarizado, demostrando un resultado exitoso.

![WhatsApp Image 2025-04-14 at 10 10 57 PM](https://github.com/user-attachments/assets/03d5d335-aec2-4837-8cb9-53150997acca)

Fotografía del circuito - Segunda parte_

<https://github.com/user-attachments/assets/01c84a79-8003-42ce-b24c-b0f0ae260781>

Video del circuito usando el camino del condensador_

<https://github.com/user-attachments/assets/5c55a574-e296-4451-891d-6de0009927bc>

Video del circuito usando el camino del potenciometro_

![WhatsApp Image 2025-04-15 at 3 31 32 AM (1)](https://github.com/user-attachments/assets/132ddb01-a23e-4f2c-a78a-8fe81fba02f0)

Diagrama del circuito fnal_

#### Bill of materials diagrama final

| Componente       | Qty | Nombre(s) | Valor/tipo |
|-----------------------|---------|------------|----------------|
| Chip 555                 | 2       | U1, U2         |                |
| Resistencia              | 4       | R1, R2, R3, R4        | Variable, 1k, 10k, 1k      |
| Condensadores      | 6       | C1, C2, C3, C4, C5, C6         | 100n, 100n, 1uF, 470n, 470n, 10uF        |
| Parlante                  | 1       |  LS1         |      2w          |
| Potenciómetro                  | 1       |  P1         |      B500K          |
| Led                  | 1       |  L1         |      3,3w          |
| Interruptor                  | 1       |  IN1         |               |

***

### Un poco de información extra

#### ¿Cómo crear un sensor de presencia?

Ya realizados los avances de las otras partes del circuito, se procede a averiguar de que forma se puede activar el dispositivo mediante la detección de movimiento para que se pueda encender.

Al momento de investigar pude dar con un video que expone el circuito de una alarma que se enciende al acercarse a distancia que es regulada por un potenciometro y que debe ser apagada de forma manual.  La creación del sensor de presencia mediante el uso de LDR’s, un amplificador operacional y algunas otras partes serán replicadas y puestas a prueba.

[https://youtu.be/QwVMbZH8AtY?si=JZScxDciYkhHqdmQ](https://youtu.be/FX98xrTd4os?si=KW8wmtMbXif0Z4fG)

Video de referencia para armar un circuito con un sensor de proximidad. Obtenido de Youtube - Ivan Espinoza._

![IMG_0158](https://github.com/user-attachments/assets/e71b5c89-c527-4101-84bf-a8682fe4f187)
Captura del circuito armado en protoboard. Obtenido de Youtube - Ivan Espinoza._

![IMG_0155](https://github.com/user-attachments/assets/9359a88a-f24b-418d-8f60-b3266ea0687e)
Captura del circuito final (en placa PCB). Obtenido de Youtube - Ivan Espinoza._

![IMG_0156](https://github.com/user-attachments/assets/2004040a-e53d-4f18-9b48-7dd1cf90485f)
Diagrama del circuito. Obtenido de Youtube - Ivan Espinoza._

#### Piezas clave de este circuito

- **LDR:** es un sensor analógico compuesto por una resistencia que cambia su valor dependiendo de la cantidad de luz que reciba, por lo que se le confieran sensores pasivos al requerir de un estimulo que es variable. Si existe más cantidad de luz detectada la resistencia disminuye y, por ende, deja pasar más corriente al aumentar su conductibilidad. Los materiales que poseen son semiconductores, como sulfuro de cadmio (CdS). Son utiles para proyectos de control de iluminación, seguidores solares, interruptores crepusculares. Hay que tener presente que estos tienen baja precisión.

- **Am. Op. Lm741:**  Un amplificador operacional es un tipo de circuito integrado compuesto por multiples transistores que permiten controlar las corrientes y tensiones. Este modelo (741) es uno de los más usados para amplificar las señales analógicas, siendo de los más comunes y versátiles. Poseen dos entradas y una salida, además de una alimentación positiva y otra negativa. La configuración de estas partes define el comportamiento del chip. Entre sus características se encuentran su alta ganancia (aumento significativo de la amplitud o potencia de la señal por el puerto de salida en comparación con el la potencia de la entrada), su amplio rango de de voltaje de operación, bajo costo y alta presencia en el mercado.

- **Potenciometro de precisión:** también llamado potenciometro multi vueltas, es una resistencia continuamente ajustable con la cualidad de permitir ajustes más precisos del valor de la resistencia al girar la pieza ubicada en la parte superior, por lo que su presencia suele encontrarse en circuitos que se requiere de un control fino y repetible de la señal. Como ejemplo de sus aplicaciones en máquinas se pueden encontrar son sistemas de maquinarias o cadenas de ensamblaje automatizadas. Otras de sus ventajas es su pequeño tamaño. En nuestro caso usaremos un potenciometro 3296W (1k, 10k, 100k) que rinde 25 vueltas aproximadamente.
