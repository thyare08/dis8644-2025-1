# sesion-10b

## Apuntes

<!-- ###### ${\color{#3d3d44}Se \ recomienda \ usar \ modo \ oscuro, \ hay \ palabras \ en \ color \ blanco \ que \ de \ otra \ forma \ no \ son \ visibles.}$

###### ${\color{#3d3d44}The \ use \ of \ dark mode \ is \ recommended, \ there's \ white \ colored \ text \ that \ otherwise \ is \ not \ visible.}$ -->

### Chromium OS

![Chromium OS logo](./archivos/chromium.jpg)

Fuente: <https://www.g2.com/products/chromium-os/reviews>

Código open source en base a Linux desarrollado por Google. Múltiples buscadores utilizan Chromium como base, como Google Chrome, Microsoft Edge, Opera GX, Samsung Internet, etc.

>### Firefox

![Mozilla Firefox logo](./archivos/Firefox.png)

Fuente: <https://es.wikipedia.org/wiki/Mozilla_Firefox>

Desarrollado por la fundación Mozilla, Firefox es un buscador open source que, a diferencia de los mencionados anteriormente, no utiliza Chromium como base.

### [Dead internet theory](https://youtu.be/apKw94iLaxc?si=ScbgQItfSVD5oG-y)

Es una teoría que dice que en la actualidad o en el futuro, la mayoría de todo el tráfico y contenido en internet será hecho por bots y AIs, reemplazando a los seres humanos como los usuarios y quienes guían tendencias y discusiones en línea.
Aunque parece que dentro de poco dejará de ser una teoría, ya que Meta anunció sus planes de inundar Facebook e Instagram con usuarios hechos con Inteligencia Artificial (AI).

### [Circuit bending](https://youtu.be/kJfTdD_5XyE?si=9yY0Lwey7DgLPbjp)

![Juguete para niños abierto e intervenido.](./archivos/circuitBending.jpg)

Fuente: <https://cmm.cenart.gob.mx/tallerdeaudio/proyectos/circuitbending/circuitbending.html>

Consiste en modificar los circuitos de objetos baratos para alterar su funcionamiento y "ver qué pasa" al conectar distintos componentes. Se suele hacer con juguetes electrónicos para niños, por su precio, fácil acceso a distintos componentes del circuito, forma interesante del objeto e inputs y outputs llamativos.

### Nic Collins

![Nicolas Collins](./archivos/collins.jpg)

Compositor, artista performático y educador, reconocido por sus obras donde hace circuit bending y hardware hacking (similar a circuit bending, pero más avanzado). Autor del libro "Handmade electronic music: The art of hardware hacking"

### Kicad BOM

Para pasar el BOM (Bill Of Materials) de Kicad a Excel hay que seguir los siguientes pasos:

![Seleccionar BOM en Kicad](./archivos/bom1.jpg)

1.-En el editor esquemático seleccionar BOM. Es importante tener seleccionadas las footprints correspondientes a cada componente.

![Opciones para exportar BOM en Kicad](./archivos/bom2.jpg)

2.- Revisar que esté seleccionado el formato CSV (Comma Separated Values), luego seleccionar la ubicación donde se exportará el BOM y seleccionar OK.

![Seleccionar la pestaña Datos en Microsoft Excel](./archivos/bom3.jpg)

3.- Abrir el documento exportado con Microsoft Excel (Se puede abrir haciendo doble click). Una vez dentro de Excel seleccionar la columna A y la pestaña "Datos", sobre la barra de herramientas.

![Seleccionar Texto en columnas](./archivos/bom5.jpg)

Dentro de la pestaña "Datos" seleccionar la opción Texto en columnas.

![Opción delimitados](./archivos/bom5.jpg)

En la ventana que se abrió seleccionar la opción "Delimitados", en caso que no esté preseleccionada, y apretar siguiente.

![Separadores](./archivos/bom6.jpg)

En el recuadro "Separadores" seleccionar la opción "Coma" y deseleccionar otras opciones, luego apretar siguiente y finalizar.

### Other things: <!-- Things to organize + random stuff -->
>
> ### CSV
>
> Formato utilizado para almacenar tablas de datos.
> Ej: El siguiente texto (CSV) al convertirlo en una tabla quedaría así:

```csv
Taller, Máquinas, Electrónicas
Electrónes, Electrónes, Electrónes
```

> |Taller |Máquinas |Electrónicas |
> |--|--|--|
> |Electrones |Electrones |Electrones |
>
>
> ### CSS (Cascading Style Sheets)
>
> Es un lenguaje que define la visualización de elementos HTML, definiendo colores, escala, posiciones, etc.
>
-----------------------------------------------------------------------------------------------------------

## Encargo 22 y 23 <!-- 22: escribir manual con pasos a seguir, receta, de los pasos que siguieron para ensamblar la PCB. incluir aciertos y errores, aprendizajes y consejos. 23: complementar encargo 22 con fotos explicativas de los materiales usados, de los pasos, etc.-->

### Manual de ensamble udpudu

### Paso 1

Separar los componentes a utilizar según el BOM de udpudu y testearlos individualmente con el multímetro para verificar que funcionen según esperado y polaridad.

![Componentes](./../../13-jotamorales-romulus/sesion-10b/archivos/componentes.jpg)

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

### Paso 2: <!-- socket -->

Colocar el socket del 555 (U1), doblando los pines de los extremos opuestos (1 & 5 y/o 4 & 8), para que se sujete a la PCB (Printed Circuit Board). Después hicimos lo mismo con las resistencias (R2, R3 y R4) y el diodo (D1)

![DIP Socket](./../../13-jotamorales-romulus/sesion-10b/archivos/1.png)

![Colocando resistencia](./../../13-jotamorales-romulus/sesion-10b/archivos/resistencia.png)

![Resistencias y diodo colocados en la PCB.](./../../13-jotamorales-romulus/sesion-10b/archivos/2.png)

### Paso 3: <!-- soldando -->  

Soldar los componentes anteriores. Para tener mayor estabilidad utilizamos 2 trozos de madera para apoyar la PCB, manteniéndola nivelada. Y para mayor control sobre la cantidad de estaño siendo depositado, me puse un guante para aislar mi mano del calor y poder tomarlo desde más cerca.

![@FranUDP soldando con @brauliofigueroa2001 iluminando](./../../13-jotamorales-romulus/sesion-10b/archivos/4.png)

![Close up soldando.](./../../13-jotamorales-romulus/sesion-10b/archivos/5.png)

### Paso 4: <!-- flush cutter -->  

Cortar el material sobrante de las patas de cada componente, teniendo cuidado de sujetarlos al momento de corlarlos con el *flush cutter*, ya que pueden salir volando y causar considerable daño en caso de enterrarse en un ojo.

![alt-text](./../../13-jotamorales-romulus/sesion-10b/archivos/6.png)

### Paso 5: <!-- assembly line -->  

Repetir los pasos anteriores con el resto de componentes del BOM.  Para este punto ya habíamos formado una linea de ensamblaje, donde yo iba soldando las placas (con la asistencia de @brauliofigueroa2001 iluminando el área de trabajo), mientras @duckusu cortaba las patas de los componentes ya soldados y @jotamorales-romulus colocaba los componentes por soldar  

![Udpudu casi terminada](./../../13-jotamorales-romulus/)sesion-10b/archivos/udpudu.jpg)

### Paso 6  

La semana siguiente (sesión 11b) terminamos de soldar los componentes faltantes (spdt y terminal blocks) empleando mis *helping hands* en lugar de los trozos de madera y usando *masking tape* para sujetar los terminal blocks, ya que sus pines/patas eran muy gruesas y cortas como para doblarlas.

![Udpudu terminada](./archivos/finished.jpg)
