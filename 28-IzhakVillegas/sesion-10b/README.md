# sesion-10b
##  16-05-2025
###  Circuit bending

(circuit bender) Doblar, customización creativa de dispositivos electrónicos, suele ser para juegos para niños. Tienden a ser robustos y a resistir la destrucción controlada.

###  Nic Collins (circuit bending)

**1  Nicolas Collins performs Christian Marclay's "Sixty-four Bells and a Bow" (2009)**

<https://www.youtube.com/watch?v=Lhs25l8l4yw>

**2  Canal: siliconluthier**

<https://www.youtube.com/@siliconluthier>

**3  Hack of the Month Club -- Project #3: Jumping Speakers**

<https://www.youtube.com/watch?v=6ZxxuDNQuMQ>

![speakandspell](./archivos/speakandspell.jpg)

**4  speak and spell circuit bending**

<https://youtu.be/Y-M9mXLl9gM?si=XZLm_hF8-91JmpP_>

Cuidado con capacitores, "todo funciona con una batería de 9V".

*  **Libro: The art of handmade electronics - music Nicolas Collins (2006 primera edición)(2020 tercera edición).**

<https://www.nicolascollins.com/handmade.htm>

## udpudu 20250425 - DIS8644

![udpuduvector](./archivos/udpudu-pcbRef.png)
![udpudu1](./archivos/udpudu-foto(1).jpg)
![udpudu2](./archivos/udpudu-foto(2).jpg)

-  Exportar vectores
-  Extraer BOM (bill of materials, lo que hay que comprar para soldarlo)
  Botón : .bom > output file > export > texto (.csv) a excel (o google docs), arreglar excel de entrada > datos > de texto a columnas (agarra las comas y reparte en las columnas siguientees)> 'next' > 'comma' (en **google docs** import file file, import > localtion separation)> se rellena con detalles menos técnicos> se puede exportar en .xsl y .csv entre otros.

*  El .csv se puede abrir con el bloc de notas. Se selecciona el texto del bloc de notas o se importa el archivo directo a google docs.

*  .csv comma separated values, sirve para excel

*  **CSV A MARKDOWN:**  <https://www.convertcsv.com/csv-to-markdown.htm>

**BOM UDPUDU**

|Reference   |Value   |Footprint                |Qty|OBS               |
|------------|--------|-------------------------|---|------------------|
|C3          |100n    |Condensador cerámico     |1  |104               |
|C4          |1u      |Condensador electrolítico|1  |                  |
|C5          |47u     |Condensador electrolítico|1  |                  |
|D1          |1n4007  |Diodo                    |1  |                  |
|D2,D3       |LED     |Led 5mm                  |2  |                  |
|J1,J3       |CAIMAN  |                         |2  |                  |
|J2          |TBLOCK_2|Terminal block 2         |1  |                  |
|LS1         |SPK     |Terminal block 2         |1  |                  |
|R2,R3,R4    |1k      |Resistencias             |3  |                  |
|SW1         |SW_SPDT |Switch spdt              |1  |                  |
|U1          |~       |Socket 8 pines DIP-8     |1  |va en el socket U1|
|Clip batería|9v      |                         |   |                  |
|Parlante    |8ohm    |                         |   |                  |

html, css: Cascading Style Sheets (para editar páginas web).
