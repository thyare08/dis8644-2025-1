# sesion-10b

EN ESTA CLASE no pude asistir debido a que me encontraba fuera de Santiago por problemas de fuerza mayor, pero de igual manera quize hablar con mis compañeros para saber que paso en la clase.

Para comenzar, cada uno de nosotros armó un circuito PWM con un LED de diferente color: rojo, verde o azul, respectivamente.

Notamos que, para el LED verde, una resistencia de 1kΩ podría ser excesiva, por lo que decidimos reemplazarla por una de 220Ω para mejorar su brillo. Esto es relevante porque el ojo humano es especialmente sensible a la luz verde, por lo que percibimos este color con mayor intensidad.

Los LEDs RGB combinan tres emisores de luz de diferentes colores (rojo, verde y azul) en un solo componente. Cada uno de estos LEDs puede variar su intensidad de brillo, lo que permite generar una amplia gama de colores mediante la mezcla de luces. Como están ubicados muy cerca entre sí, la luz que emiten se fusiona visualmente.

Estos LEDs RGB suelen presentarse en dos configuraciones: de cátodo común o de ánodo común. Con este montaje, replicamos el principio de funcionamiento de una rosa cromática, ya que al combinar los tres LEDs, pudimos observar cómo sus luces se mezclaban para formar nuevos colores.

# FALSTAD

Falstad es el nombre común con el que se conoce al Simulador de Circuitos Electrónicos Falstad, una herramienta en línea gratuita muy utilizada para visualizar y simular el comportamiento de circuitos eléctricos y electrónicos en tiempo real. Fue desarrollado por Paul Falstad, un programador y físico aficionado, y se ha convertido en una herramienta muy popular en entornos educativos y entre personas que aprenden electrónica.

En esta sesión trabajamos con el LM324N, un chip clásico muy utilizado en electrónica. Este circuito integrado posee cuatro amplificadores operacionales (OP-AMPs) en su interior y cuenta con 14 patas (pines).

- ¿Qué es un OP-AMP?
Un amplificador operacional (abreviado como OP-AMP) puede pensarse como una "caja negra" que realiza operaciones matemáticas basadas en la comparación de voltajes entre sus entradas. Es un componente activo (requiere alimentación externa) y versátil, usado en múltiples aplicaciones: amplificadores, comparadores, filtros, sumadores, etc.

- Alimentación de los OP-AMP
Una dificultad que presentan los OP-AMPs es su alimentación con dos polaridades: algunos circuitos requieren ±12V (positivo y negativo), ya que no todos los diseños funcionan correctamente con una sola fuente de 0V y 12V. Este aspecto complica su implementación si no se tiene una fuente simétrica.

- El LM324N vs. el 741
LM324N: Contiene cuatro OP-AMPs en un solo encapsulado.

741: Otro chip clásico, pero solo con un OP-AMP.

- Pinout y documentación
Cuando se busca información de un chip, como el LM324N, se recomienda escribir “pinout” junto al nombre en buscadores. Así se accede rápidamente al esquema de conexiones sin tener que buscar el significado de cada pata individualmente.

# Construcción del UDPUDU

![UDPUDU1](https://media.discordapp.net/attachments/1318882679659171892/1372986482549198918/IMG_7502.jpg?ex=682d620e&is=682c108e&hm=a647956703994809dbbd3ef9a9497edbcc142c056328215d014d595cbd6b7c37&=&format=webp&width=875&height=544)

![UDPUDU2](https://media.discordapp.net/attachments/1318882679659171892/1372983252595507240/IMG_1379.jpg?ex=682d5f0c&is=682c0d8c&hm=1aca4c280414162260958b3e354fa6b598cc3c5775020a9908dba27a67c93278&=&format=webp&width=408&height=544)

![UDPUDU3](https://media.discordapp.net/attachments/1318882679659171892/1372983253551677591/IMG_1384.jpg?ex=682d5f0c&is=682c0d8c&hm=c2aa89c3467024f0dd374b5ba24f3a94eef85b1e13d3202e9a5c685ba87389f9&=&format=webp&width=725&height=544)

# ¿Que es?

Es un generador de sonido breve que se activa con una señal de entrada. Usa un temporizador 555 para generar un pulso y hacer sonar un buzzer o altavoz por un momento. También enciende un LED para mostrar visualmente que se activó.

# Componentes principales

Alimentación

- J2: Conector para la alimentación de +9V.

- D1 (1N4007): Diodo que protege el circuito de una conexión de voltaje invertido.

- SW1 (switch): Interruptor que enciende o apaga el circuito.

- VCC / GND: Tensión positiva y tierra.

- J1 y J3 (CAIMAN): Entradas donde se puede aplicar un pulso o señal externa para activar el circuito.

- R2 (1k): Limita la corriente de la señal de entrada.

- C4 (1uF): Filtra o desacopla la señal para evitar falsos disparos.

- 555 Es el corazón del circuito. Está configurado en modo monoestable, lo que significa que cuando recibe una señal en el pin TR (2), activa una salida por un tiempo corto.

- C3 (100nF): Estabiliza el voltaje en el pin 5 (CV).

- Los pines 2 y 6 están conectados juntos para detectar el pulso de activación.

- Pin 3 (Q): Es la salida que se activa temporalmente.

- R3 (1k): Limita la corriente hacia el LED y el altavoz.

- D2 (LED): Enciende cuando la salida del 555 está activa (indica visualmente la señal).

- C5 (47uF): Filtra y suaviza la señal hacia el altavoz.

- LS1 (SPK): Altavoz que emite un sonido cuando se activa el circuito.

- D3 (LED) y R4 (1k): Indican que el circuito está encendido (conectado a VCC).

# ¿Cómo funciona todo junto?

1. Conectas 9V y enciendes el interruptor (SW1).

2. El LED de encendido (D3) se ilumina.

3. Cuando llega una señal al pin J1 o J3, el 555 se activa.

4. Durante un corto tiempo:

5. Se enciende el LED D2.

6. Suena el altavoz LS1 con un “bip” o “zumbido”.

7. Luego de ese tiempo, el 555 vuelve a su estado inactivo, apagando el LED y el sonido.

# Bills of Materials (BOM)

|Referencia  |Valor   |Huella                   |Qty|OBS               |
|------------|--------|-------------------------|---|------------------|
|U1          |~       |Socket 8 pines           |1  |                  |
|R2,R3,R4    |1k      |Resistencias             |3  |                  |
|D1          |1n4007  |Diodo                    |1  |                  |
|C3          |100n    |Condensador cerámico     |1  |104               |
|C4          |1u      |Condensador electrolítico|1  |                  |
|C5          |47u     |Condensador electrolítico|1  |                  |
|D2,D3       |LED     |Led 5mm                  |2  |                  |
|J2          |TBLOCK_2|Terminal Block 2         |1  |                  |
|LS1         |SPK     |Terminal Block 2         |1  |                  |
|SW1         |SW_SPDT |Switch spdt              |1  |                  |
|U1          |NE555   |DIP-8                    |1  |Va en el socket U1|
|Clip batería|9v      |                         |1  |                  |
|Parlante    |8ohm    |                         |1  |                  |
|J1,J3       |CAIMAN  |Cables caimán            |2  |                  |

# Circuito de UDPUDU

![sch-pudu](./archivos/udpudu-sch.png)





