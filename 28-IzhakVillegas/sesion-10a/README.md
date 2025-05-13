# sesion-10a
### Armar circuito PMW
-  Leds
-  LEDS RGB
-  Cátodo común
-  Ánodo común
-  LED de 7 segmentos, el display de los números o palabras (reloj digital) se programa, display con muchos leds tipo de señal CK CA.
  Se puede realizar un contador de segmentos.
- Decodificadores
- Codificadores
- Multiplexores

Sirve para determinar voltaje, y por cada segmento de voltaje determinar en qué componente recibe la corriente y cuál no, es programación display pero no es programación en un terminal.

Así funcionan los pixeles en una pantalla, son cuadrados en función de un plano cartesiano. (René Descartes).

Los colores son contextuales, colores son subproductos de luces en RGB. Color aditivo y sustractivo RGB y CMYK

Mucho tiene que ver la calidad del archivo con el tamaño del archivo y por lo tanto la percepción visual del archivo en función de su compresión, ocurre tanto en imágenes como audio, esto se decide en base a la percepción sensorial que nosotros tengamos de esto.

Pixeles quemados ocurren por uso y condiciones materiales, no por asuntos digitales.

>  Los leds funcionan como redstone de Minecraft.
Comparador:
¿Es A mayor que B? SI/NO
Condiciones
-  Si A es mayor que B , salida C funciona
-  Si A e s menor que B, salida C no funciona.

### chip LM324 (Amplificador operacional, OP-AMP u Operational Amplifiers)
tiene 14 patas

-  Estadios históricos de la luz electrónica:
Tubo de vacío > diodio > transistor > OP-AMP

"caja negra llena de transistores"

Amplificador operacional (triángulo).
Chip que resuelve operaciones matemáticas integrales. Bell Labs. 

-  Alimentación de Vs negativo y positivo.
-  2 Entradas y
-  1 salida.

LMx24 (4 OP-AMP)
14 patas
(1,2,3) Inputs y Output
(4)  VCC+ batería
(11) VEE- GND
LM358 (2 OP-AMP)
Simplificado con 2 patas INPUT que sale en un OUT

2 baterías negativo con positivo suman y ale tierra GND(+-), aparece +9V y -9V. Fuente bipolar. Sirve a nivel de audio. Sirve para micrófono.

Electret sensor que sabe si se perturbó el aire alrededor.

Comparadores.

LM741 (tiene 1 OP-AMP)

Resonador (RLC) bobina

Voltaje de batería es campo de posibilidades, lienzo electrónico, determina donde empieza y dónde termina. En nuestro caso no puede ser mayor que 9V o menor que 0 porque no tenemos algo mayor o menor que esto.

Divisor de voltaje DIV de Voltaje
Si hay dos resistencias Vo = Vx R1/R1+R2
9V y 0V cuál es Vo?? se calcula como dos pines de un potenciómetro, Voltaje de la mitad.

Voltaje de dos terminales como una batería.

Umbral de potenciómetro, decide quiénes pasan y quiénes no.

Aproximación de voltaje entre resistencias con base al LDR (fotorresistor).

La distorsión es un comparador a nivel de audio

Buffer. Boss DS-1 Distortion

Álegra de Boole, funcionan los comparadores, las compuertas son por ejemplo and y or.
-  Abstracciones.
or gate.
and o nand gate. el logo de android está basado en esto.
nmos, cmos.
Las compuertas son la versión física en el circuito, la programación es en lo digital.

"Si baja la luz lo suficiente se prende una ampolleta".

Comparadores se pueden hacer con otros componentes, sin embargo, es engorroso.

Top down design.

Voltaje y corriente es distinto.

Detector de sombras.

-  Tarea continuar encontrando pantallas. Y encontrar la cantidad de segmentos.
-  Hacer pwm en falstad
-  Y entender pines de los comparadores.
