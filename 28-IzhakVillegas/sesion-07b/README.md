# sesion-07b

CAD Assistant

* library > símbolos para el esquemático
* modules > footprints (huellas) del PCB
* packages3d/ > visualizador de modelos 3D
* añadido -> shapes > forma para el PCB

Librería de símbolos

Añadir biblioteca

Encontrar comprimido y descomprimirlo, open 555_ordenado kicad_sym

Seleccionar R y apretar F, resistencia.

R_Axial_DIN0207_L6 3mm....5mm_P10.16MM

Huellas recomendadas:

Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P10.16mm_Horizontal
Capacitor_THT:C_Disc_D6.0mm_W2.5mm_P5.00mm
Capacitor_THT:CP_Radial_D6.3mm_P2.50mm
LED_THT:LED_D5.0mm

Resistencia axial significa que estan en el mismo eje

Resistencia radial propiedad eléctrica encapsulado

Nombre_valor_encapsulado

cdm.link página Cómo referirse a algo de manera no violenta  <https://cdm.link/so-yeah-lets-just-use-plug-and-socket-industry-group-recommends-obvious-change-in-terminology/>

conn > caimán

Diseño de interacción, colocar un LED conectado a corriente y a tierra aparte del circuito para saber si estamos con corriente.

Switch pcb
switch interruptor 2 posiciones SPDT 1P2T

Jack DC 2.1mm
Terminal block 5 (hay que conectarlo bien, no al revés ni tampoco romperlo).

Protección para el Jack. Se le puse colocar un diodo para que nadie se queme.

JST CONN

diodo protection diode
50 unidades vale $790 CLP.

Administración de alimentación y Formato del circuito

Dividir, organizar nuestro esquemático.

Se puede previsualizar el 3D

Importar Logo conversor de imágenes, convertir imagen a huella y cuando sea huella se puede importar al PCB.

Conversor de imágenes en Kicad menú principal.

Silkscreen frontal > texto (ícono T) se añade texto, sirve para indicar especificaciones a la placa, ideal para que la persona que imprima sepa que está imprimiendo. CAPA SILKSCREEN.

Bottom Cu

No se puede tocar cobre con cobre ni serigrafía con serigrafía.

* Saltos de línea

1. Arrastrar borde en 5 mm > hacer un arco, y así se logra un borde circular para la placa PCB. En capa edgecuts.
2. Vía PCB, saltar entre capas de la placa. Presionar "V", cuando le hago click cambia el color de la vía a rojo y eso indica que estamos por debajo de la placa.
3. Trazaar para exportar. Marcar F.cu B.cu F. Sikscreen B. Silkscreen F. Mask B. Mask Edge cuts
4. Archivos .gbr y .drl. Carpeta gerber, lo que se manda a la impresora. Se recibe en .zip JLCPCB.
5. Add gerber file. Indicar Layers, dimensions, PCB Qly, Prdocut Type (indicar para qué es).
6. Se indica el color.
7. PCB Thickness 1.2mm, es más caro hacer placas más delgadas.
8. SMD (se puede pedir soldado).
9. LCSC (Shenzhen).

1 mes antes de la entrega, ver qué vamos a ensamblar. Después interfaz de usuario.

11. Ver envío, sube precio. Por ejemplo 5 PCB salndrían $10 USD.
