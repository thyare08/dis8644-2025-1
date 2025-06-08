# sesion-04a

[martes 01 de abril, 2025

Tema

  Parte 1
    Información sobre evaluaciones.
    Explicación Solemne 1.
  Parte 2
    Atari Punk Console circuito chip 555.

Apuntes
  Evaluaciones

    Síntesis experiencias.
    Projecto 2.
    Bitácoras (4 notas por mes).
    Encargos.

  Divisor de voltaje, soldar.
  Zachary Lieberman, diseñador y programador.
  Bosquejos diarios todos los días, 100 días de hacer algo nos obliga a hacer algo, por lo tanto nos permite tener constancia e inspiración en el trabajo mismo. De aquí que nacen las ideas. Enfrentarse a la hoja en blanco a diario, un ejercicio personal.
  Lauren McCarthy: <https://lauren-mccarthy.com/>
  Hitos, claridad en retrospectiva.
  "./archivos/circuito-led.png" sirve para adjuntar un archivo en el mismo repositorio y no depender de un enlace que está propenso a elminarse. En el repositorio añadir carpeta imágenes, subir como img en doc, NO como link!!
¡¡Traer un objeto electrónico roto o diseccionable para el próximo martes!!

  Que presente un input y un output claros.
  Encargo (información puede cambiar)

  1. (Explicación) Premisa del proyecto, declaración del proyecto.
  2. Anatomía de la fisicalidad del dispositivo en texto, imagen, diagramas de flujo, ilustraciones. Contexto con humanos en su uso (bocetos).
  3. Bitácora, multimedia del proceso.
  4. Esquemático de electónica con todos los componentes y justificaciones.
  5. Bill of materials.
  6. Funcionamiento (sí o no, estable o no, frágil o robusto).
  
  Presentación oral con soporte en Markdown, Github.
  (¡Material visual!).
  Tema:  Construcción de prototipo electrónico a partir de circuito específico APC (¿Atari Punk Console?).
  Se sobreentiende que la materialidad del prototipo debe tener oficio.
  Es posible que haya que traer cautín personal.
  Atari Punk Console
  Los 555 se presentanen circuitos monoastables, bistables (flip-flop) y astables.
  Así como la placa madre de un PC se personaliza con tarjetas gráficas, discos duros, etc. Los 555 y todos los chips se configuran por medio de resistencias y condensadores.
  Por lo tanto, la Atari Punk Console es personalizable.
  Se basa en ondas cuadradas con circuito base fácil de conducir y adaptar. Se puede armar en protoboard, es escalable y personalizable. Así se genera la música de 1 bit.
  Véase 1-bit Symphony, escuchar disco.
  Circuito estable, ojo con las resistencias. Se puede utilizar como una caja negra.
  Input potenciómetro.
  LDR cambia de un valor.
  Atari Punk Console: (555) 3<----->2 (555), conexión entre ranuras.
  Además del chip 555 es bien conocido el chip 4017.
  555 Timer circuits.
  Resistencia no menor a 1K.
  Protoboard 3 secciones, 1 tierra 2 capacitores a tierra.
  Sintetizador DXE.
  Hacer circuito doble de 555 con bocina.
    CIRCUITO DOBLE 555
  Imágenes

![alt-text](./documentos_adjuntos/imagenes-doble-555_izhak_villegas (1).jpg)

![alt-text](./documentos_adjuntos/circuito-doble-555.png)

Fig. 1-2.  En el presente circuito se utilizó el diagrama proporcionado en el servidor de Discord disenoUDP-interaccion en el canal #dis8644-taller por 23_Martin el 01/04/2025 a las 12:32 (UTC-3). Consultado el 03 de abril de 2025.

! [alt-text](./documentos_adjuntos/imagenes-doble-555_izhak_villegas (2).jpg)

Fig. 3.  Con 12 cables dupont a excepción de los que están conectados directamente a la fuente de poder (batería recargable 9V) mediante alambres cocodrilo, 2 LDRs, 1 condensador de 100 uF (con polaridad), 2 resistencias de 1K, 1 condensador cerámico de 151 pf y 2 condensadores de 474 pf, 1 altavoz de 8 ohms conectado a dos alambres cocodrilo correspondientes a cada polaridad y lo más importante: 2 chips 555 se logra el circuito capaz de emitir sonidos tal cual esquema de una Atari Punk Console. En los links están los videos adjuntos probando la sonoridad.

Videos
"<https://github.com/IzhakVillegas/dis8644-2025-1/blob/85e2d9dbb71c04aa100ea7fbb12770763fa0138f/28-IzhakVillegas/sesion-04a/documentos_adjuntos/videos-doble-555-izhak_villegas%20(1).mp4>" target="_blank"
enlace VIDEO 1

"<https://github.com/IzhakVillegas/dis8644-2025-1/blob/85e2d9dbb71c04aa100ea7fbb12770763fa0138f/28-IzhakVillegas/sesion-04a/documentos_adjuntos/videos-doble-555-izhak_villegas%20(2).mp4>"

enlace VIDEO 2

## Encargo

Escuchar 1 bit symphony, entregar una reseña.

1 bit Symphony (2009-10) del artista neoyorquino Tristan Perich es una composición de cinco movimientos en un mismo microchip en una caja de CD programado y ensamblado a mano, es una performance de sonido en vivo porque no es como un CD, vinilo, casette u otro medio de reproducción de música tradicional. Es su segundo trabajo de este estilo, (el primero fue 1 bit Music(2006) que también es un chip interactivo que oscila la energía eléctrica y genera música en 1 bit). El circuito es capaz de sonar por 40 minutos seguidos con sonido de baja fidelidad (low-fi) de 1 bit.

Escuchar los tracks de este llamativo álbum me parece algo sonoramente genial, el cómo la música incluso comprimida en 1 bit puede llegar a alcanzar estas tonalidades, yo siendo fan de la música de 8 y 16 bits me parece algo estupendo. Si pudiera interactuar con la obra en sí seguramente pasaría un buen tiempo manejando el producto, a simple vista resulta ser un circuito bastante sencillo en el que sus oscilaciones pueden seguir un ritmo programado como si se tratase de un videojuego de Atari, sin embargo, puedo notar que al no poseer líricas queda a interpretación propia el significado del ritmo de estos circuitos que bien podría ser música de arte experimental, o también conocido como arte sonoro (prácticas artísticas que tienen como objetivo basarse en las diferentes nociones del sonido y en quién las escucha). En ciertas partes me recuerda a Graham Kartna quien también suele usar música low-fi o samples de sistemas electrónicos, en lo personal me parece una producción genial, me gusta el cómo se pueda representar una propuesta diferente a lo que estamos acostumbrados a las disqueras tradicionales, esta situación me recuerda al vinilo Artaud de Pescado Rabioso. Agradezco la recomendación.

Armar dúo/trío para próximan solemne.
