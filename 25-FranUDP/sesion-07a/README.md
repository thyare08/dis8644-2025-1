# sesion-07a

## Apuntes
>
> ### Componentes electrónicos
> Todos poseen 3 características: <br/>
> * ${\color{#b0e6e6}Valor}$ (ej: 1k resistencia) <br/><br/>
> * ${\color{#b0e6e6}Símbolo}$: dibujo que representa un ${\color{#b0e6e6}componente}$ en el diagrama/esquema ej: <br/><br/> <img align="left" src="./files/resistorSymbols.jpg" width=220> <br/><br/><br/><br/><br/><br/><br/><br/><br/><br/>
> * ${\color{#b0e6e6}Rating}$: Cuanto ${\color{red}voltaje}$ y/o ${\color{#b0e6e6}corriente}$ soporta antes de quemarse o explotar <br/>
>
> Aparte de las características ya mencionadas, otro detalle son las ${\color{#b0e6e6}dimensiones \ físicas}$ que ocupa cada componente (${\color{#b0e6e6}footprint}$) <br/><br/>
> <img align="left" src="./files/footprint.jpg" width=200> <br/> Length <br/><br/> Diameter/Width <br/><br/> Pitch (distancia entre las patas) <br/><br/>
>
> ### Kicad <img align="left" src="./files/kicadLogo.png" width=45> <br/><br/>
> Software suite (múltiples programas distintos en un mismo lugar) <br/><br/>
>> ### Esquema (sch) <img align="left" src="./files/sch.png" width=45> <br/><br/>
>> Se importan los ${\color{#b0e6e6}símbolos}$ de los componentes a utilizar y se definen las ${\color{#b0e6e6}conexiones}$ entre ellos, que luego serán utilizadas para guiar el diseño de la PCB. <br/>
>> ### Shortcuts: <br/>
>> | A |  Añadir simbolo <img align="right" src="./files/A.png" width=45> <br/><br/> |
>> |:-:|:----------------|
>> | R | Rotar elemento |
>> | M | Mover elemento |
>> | G | Mover elemento + conexiones |
>> | Q | Pin sin conectar <img align="right" src="./files/Q.png" width=45> <br/><br/>|
>> | E | Ver info componente |
>> | V | Editar valor componente |
>> | X | Espejar simbolo y textos en el eje X |
>> | Y | Espejar simbolo y textos en el eje Y |
>> | W | Trazar cable <img align="right" src="./files/W.png" width=45> <br/><br/>|
>> 
>> ### Generate Bill Of Materials <img align="left" src="./files/BOM.png" width=45> <br/><br/>
>> Automaticamente exporta nuestro BOM en formato .cvs (editable en excel) <br/>
>
> ### PCB Editor <img align="left" src="./files/pcb.png" width=45> <br/><br/>
> Tras asignar la ${\color{#b0e6e6}footprint}$ de cada componente, estos se pueden comenzar a ${\color{#b0e6e6}organizar}$ en la placa PCB junto con sus ${\color{#b0e6e6}conexiones}$. <img align="right" src="./files/pcb_sch.png" width=45> <br/> Para ${\color{#b0e6e6}actualizar}$ el editor PCB con los componentes y conexiones del editor esquemático apretar el ícono a la derecha <br/><br/>
> ### Shortcuts: <br/>
> Algunos de los shortcuts anteriores ${\color{#b0e6e6}no \ funcionan}$ en el editor PCB
> | A |  Añadir simbolo <img align="right" src="./files/A2.png" width=45> <br/><br/> |
> |:-:|:----------------|
> | R | Rotar elemento |
> | M | Mover elemento |
> | G | Mover elemento + conexiones |
> | E | Ver info componente |
> | V | Rotar entre capa de cobre frontal y posterior y si se tiene seleccionado un cable, poner una via |
> | X | Trazar cable <img align="right" src="./files/X.png" width=45> <br/><br/>|
> | W | Rotar entre grosores de trazos de cobre (cable) |
>
> Para ver la placa PCB en 3d presionar ${\color{#b0e6e6}"Alt \ + \ 3"}$ (windows) <br/>
>> Componentes seleccionados en el editor PCB se verán ${\color{lightgreen}verdes}$ en el visor 3d <br/>
>
> ### Other things
>
>> #### THT (Through Hole Technology) <br/><br/>
>> 
>> ### Package
>> ${\color{#b0e6e6}Dimensiones \ estándar}$ para componentes ej: DO 35 o 0805 <br/><br/> <img align="left" src="./files/package.jpg" width=400> <br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/>
> <br/>
-----------------------------------------------------------------------------------------------------------
## Encargo 14
### Esquema Atari Punk en Kicad
> <img align="left" src="./files/atariPunk.png" width=940> <br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/>
>
-----------------------------------------------------------------------------------------------------------
## Encargo 15
### 2 dudas o aprendizajes
>> ### 1: ¿cómo podemos hacer una placa con más de 2 capas? [(Tutorial)](https://youtu.be/RlB2mzoIKbo?si=8R2g06NOSoa8hhVs)<br/>
>> Haciendo click en ${\color{#b0e6e6}Board \ Setup}$ <img src="./files/boardSetup.png" width=25> y luego seleccionando la cantidad de capas de cobre
>> 
>> ### 2: ¿Qué es "impedance"? <br/>
>>  viendo varios tutoriales, algo que muchos mencionan es "impedance" y que los trazos de cobre tienen que tener un valor de 50Ω, por lo que logro entender parece ser algo para evitar que la señal electromagnética de cada trazo interfiera con la del que tiene al lado, aunque podría ser solo algo específico de diseños RF (RadioFrequency)
> <br/>
