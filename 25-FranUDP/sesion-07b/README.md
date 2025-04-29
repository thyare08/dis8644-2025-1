# sesion-07b

## Apuntes
>
> ### Instalación librería customizada
> Tras descargar los símbolos y/o footprints que queremos añadir a Kicad, es ideal (aunque no necesario) moverlos a una ubicación adecuada (como la carpeta de instalación de Kicad) para evitar accidentalmente cambiarlos de dirección o eliminarlos. <br/> <br/>
> Luego hay que ir a preferencias y seleccionar librería de símbolos <br/><br/> <img src="./files/pref1.png" width=300> <br/><br/>
> Una vez dentro de la librería de símbolos, apretar el icono de carpeta, buscar la ubicación del archivo o carpeta que se desea importar, seleccionarlo y darle ok. <br/><br/> <img src="./files/pref2.png" width=300>
>
> ### Kicad 
> ### Circuitos paralelos
>> ### Indicador de energía
>> <img align="left" src="./files/energy.png" width=200> <br/><br/><br/><br/><br/> Este circuito enciende un LED para indicar que el circuito (total) tiene energía y por lo tanto, tiene una fuente de poder conectada <br/><br/><br/><br/><br/><br/><br/><br/>
>>
>> ### Circuito de protección
>> <img align="left" src="./files/protecc.png" width=450> <br/><br/><br/> Este circuito se encarga de prevenir que explote el circuito (total) en caso de que accidentalmente se conecten los cables al revéz, mediante la implementación de un diodo. <br/> (en mi caso no es realmente necesario, pues decidí poner un conector JST para la batería) <br/><br/><br/><br/><br/><br/> 
> 
> ### Gráficos
>> Nos enseñaron 2 métodos para añadir logos y gráficos en la placa PCB: <br/><br/>
>>  <img align="left" src="./files/logo1.png" width=450> <br/><br/><br/><br/> 1. Footprint: <br/> Se añade la gráfica a la librería de footprints y luego se inserta en la placa
>>     <br/><br/><br/><br/><br/><br/><br/>
>> <img align="left" src="./files/logo2.png" width=450> <br/><br/><br/><br/><br/><br/><br/> 2. Importar gráficos: <br/> Se importa un gráfico en formato .xdf o .svg <br/><br/><br/><br/><br/><br/><br/><br/><br/><br/>
>>
>> ### Capas
>> <img align="left" src="./files/layers.png" width=450> <br/><br/><br/><br/><br/><br/> Se puede cambiar la capa en la cual se insertó el gráfico haciendo doble click 2 veces en él y luego seleccionando la capa a la cual queremos moverlo <br/><br/><br/><br/><br/><br/><br/>Dependiendo de la capa que elijamos, el gráfico tendrá un efecto distinto en la PCB: <br/>
>> * ![color](https://placehold.co/15x15/c83434/codigo_color.png) ![color](https://placehold.co/15x15/4d7fc4/codigo_color.png) .Cu: <img align="right" src="./files/Cu.png" width=100> Considerando que en la zona donde está el gráfico no hay un plano sólido de cobre, esté se verá de un tono más claro, ya que generará un trazo de cobre bajo la superficie de la PCB <br/><br/><br/><br/><br/>
>>
>> * ![color](https://placehold.co/15x15/f2eda1/codigo_color.png) ![color](https://placehold.co/15x15/e8b2a7/codigo_color.png) .Silkscreen: <img align="right" src="./files/silk.png" width=100> Poner el gráfico en esta capa hará que lo impriman sobre la superficie de la pcb con tinta blanca <br/><br/><br/><br/><br/><br/>
>>
>> * .Mask: <img align="right" src="./files/mask.png" width=100> Ubicar el gráfico en esta capa hace que en esa sección de la placa no esté el recubrimiento superior, lo que hace que el cobre (estaño u oro, dependiendo del acabado) y/o el material de la PCB queden expuestos <br/><br/><br/><br/><br/><br/>
>
> ### Other things
>
>> ### Símbolo v/s Footprint
>> Si tenemos un componente que va conectado al circuito, pero no queremos ponerlo en la placa PCB, se le puede asignar el footprint de un conector, pins, "soldering pads", etc <br/><br/>
>>
>> ### SPDT
>> <img align="left" src="./files/spdt.png" width=150> <br/> Es un interruptor de 2 posiciones, que en lugar de abrir o cerrar un circuito, puede hacer que un circuito esté abierto, mientras un segundo circuito está cerrado (no pueden estar ambos cerrados o abiertos a la vez) <br/><br/><br/><br/>
>>
>> ### Color del cable (sch)
>> <img align="left" src="./files/wireC.png" width=450> <br/> @21-SebastianSaez1003 me mostró que en el modo esquemático se puede cambiar el color de los cables para que sea más facil diferenciarlos <br/><br/><br/>
>>
>> ### JST
>> <img align="left" src="./files/JST-XH.jpg" width=450> <br/><br/><br/><br/><br/> Conector ámpliamente usado en la industria, pequeño y barato, similar a los conectores dupont pero con un mecanismo de retención que además previne que se inserte al revés <br/><br/> [DIY 3d print JST made by me](link thinggyverse soon to come) <br/><br/><br/><br/><br/><br/><br/><br/><br/><br/>
><br/>
-----------------------------------------------------------------------------------------------------------
## Encargo 16
### UDPudu (hacerse una cuenta en JLCPCB y cotizar udpudu, para 30 personas, documentar cada parámetro y elección.)
> <img align="left" src="./files/udpudu-F.png" width=460><img align="left" src="./files/udpudu-B.png" width=460> <br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/>
>
> Considerando 1 PCB por persona (30 PCBs total), El precio de la orden sería de $14.70 USD + envío ($14.03 USD - $39.11 USD) o $0.95 USD - $1.80 USD por cada PCB <br/>
>
> Si se consideran 5 PCBs por persona (150 PCBs total), El precio quedaría en $40.40 USD + envío ($71.80 USD - $90.41 USD) o $0.75 USD - $0.87 USD por cada PCB <br/>
>
> 
-----------------------------------------------------------------------------------------------------------
## Encargo 17
### TITULO (probar opciones que no entiendan, documentar otros parámetros que no conozcan aún.)
>
>
