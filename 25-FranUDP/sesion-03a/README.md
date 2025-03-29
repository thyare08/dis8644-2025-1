# sesion-03a

## Apuntes
>
> ### Voltaje y resistencia en tipos de circuitos
> Vcc = Voltaje Corriente Continua (el positivo) <br/>
> * Resistencia en serie = **R<sub>Total</sub>** = R<sub>1</sub> + R<sub>2</sub> + R<sub>2</sub> + R<sub>4</sub> <br/>
> * [Resistencias en paralelo](https://youtu.be/5uyJezQNSHw?si=-xhBxAEVZoKuAEOg&t=576) = 1/**R<sub>T</sub>** = 1/R<sub>1</sub> + 1/R<sub>2</sub> + 1/R<sub>2</sub> + 1/R<sub>4</sub>
>> 1k + 1k = 500 ohm (por eso al conectar una segunda resistencia en paralelo, el LED brilla más) 
>
> ### Prefijos notación científica
> <img align="left" src="https://th.bing.com/th/id/R.a8057d46a9fe796121af98f1a3dd02f3?rik=AAD%2fVV2eYzustQ&riu=http%3a%2f%2ftutordelectronica.weebly.com%2fuploads%2f2%2f4%2f4%2f1%2f24418880%2f239438.jpg%3f623&ehk=s40UHD9u%2ffetT%2bD8Yr1tyAEp6rkjAxeDieXO5BjA7ys%3d&risl=&pid=ImgRaw&r=0" width=420>
> Son simbolos que se colocan antes de las unidades de medida, para cambiar su valor y expresar cantidades más grandes o pequeñas de forma más corta (resumida) y comprensible.
>
> Una forma en que se podría pensar sobre esto es con las unidades de medida del sistema métrico (ej: "g" y "kg") pero en lugar de tener 500 mil distintas unidades de medida distintas para medir lo mismo, le añadimos un apellido para denotar la cantidad de ceros. 
> <br/>
> <br/>
> <br/>
> <br/>
> <br/>
> <br/>
> <br/>
> <br/>
> <br/>
> <br/>
>
>
> ### [Capacitores<sub>1</sub>/](https://youtu.be/X4EUwTwZ110?si=W06CjwpOs9OW3rEu)[Condensadores<sub>2</sub>](https://www.youtube.com/watch?v=rbCXKhhzBN0)
>> <img align="left" src="https://github.com/FranUDP/dis8644-2025-1/blob/main/25-FranUDP/sesion-03a/CapacitorChargeDischarge.gif" width=500>
>> <br/>
>> &nbsp;&nbsp;&nbsp;Similares a una bateria en que atrapan y liberan electrones <br/>
>> &nbsp;&nbsp;&nbsp;(carga/corriente), pero difieren en que estos se cargan <br/>
>> &nbsp;&nbsp;&nbsp;mucho más rapidamente y tienen una capacidad muchisimo <br/>
>> &nbsp;&nbsp;&nbsp;más limitada. <br/>
>> &nbsp;&nbsp;&nbsp;Se suelen utilizar para estabilizar señales (pulsación como <br/>
>> &nbsp;&nbsp;&nbsp;metralleta -> pulsación estable, al evitar un on-off de golpe <br/>
>> &nbsp;&nbsp;&nbsp;al descargarse el capacitor) <br/>
>> <br/>
>>
>> #### Simbologia
>> <img align="left" src="https://github.com/FranUDP/dis8644-2025-1/blob/main/25-FranUDP/sesion-03a/CapacitorSymbology.png" width=500>
>> <br/>
>> <br/>
>> <br/>
>> <br/>
>> <br/>
>> <br/>
>> <br/>
>>
>> #### Ceramic & electrolytic 
>> <img align="right" src="https://www.majju.pk/assets/uploads/2018/06/470UF-35V-ALUMINIUM-ELECTROLYTIC-POLAR-CAPACITOR-1200x684.jpg" width=334> Los ${\color{orange}capacitores \space cerámicos}$ no tienen una polaridad predefinida, por lo que no importa que "pata" del capacitor es conectada al positivo o negativo. <br/>
>> 
>>
>> <img align="right" src="https://th.bing.com/th/id/OIP.fZ6K37RHqWd1_SyJEgwiYgAAAA?rs=1&pid=ImgDetMain" width=200> Estos capacitores tienen su capacidad escrita en un código de 3 dígitos: XXY, donde los primeros 2 dígitos (XX) son los primeros digitos del valor, al los cuales se le agrega (Y) cantidad de 0s. Ej: 474 = 470.000 F (Farads)
>> <br/>
>> <br/>
>> Los ${\color{#6462fe}capacitores \space electrolíticos}$, a diferencia de los cerámicos, si tienen una polaridad definida. Aparte de eso, almacenan más electrones y tienen su <br/> capacitancia y voltaje escritos.
>> <p align="center"> :warning: <strong>Si se conectan al revés hay una alta probabilidad que exploten</strong> :warning: </p>
>
> ### [555 Timer](https://youtu.be/fLaexx-NMj8?si=-22qzLNU37zI5imM)
> Es una IC (Integrated Circuit), es decir, un circuito que alguien ya diseñó y que solo tenemos que conectarlo y usarlo. <br/>
> En el caso del NE555, este es una IC que se emplea para producir *time delays* y oscilaciones precisas. <br/>
> <br/>
> El 555 puede operar en los siguientes modos: <br/>
> * ${\color{white}Bistable}$: We can make it output 0 or 1 <br/>
> * ${\color{white}Monostable}$: We can make it output 0 or 1, but it will return to it's set default state (auto-reset) <br/>
> * ${\color{white}Astable}$: It will oscillate between 0 and 1 <br/>
> ### Pinout and datasheet <br/>
> <img align="left" src="https://github.com/FranUDP/dis8644-2025-1/blob/main/25-FranUDP/sesion-03a/555Pinout.jpg" width=440> [NE555 datasheet](https://github.com/disenoUDP/dis8644-2025-1/blob/main/00-docentes/sesion-03a/archivos/lm555-datasheet.pdf): Una *datasheet* es como un manual, en ella está toda la información relevante en cuanto al uso y operaciones de un componente o módulo electrónico, como lo son: <br/>
> * Operational Voltaje range
> * Current rating
> * Power consumption (Watts)
> * Pinout diagrams
> * Etc.
>
>> #### Circuito astable
>> <img align="left" src="https://github.com/FranUDP/dis8644-2025-1/blob/main/25-FranUDP/sesion-03a/555Circuit1D.jpg" width=420> <img src="https://github.com/FranUDP/dis8644-2025-1/blob/main/25-FranUDP/sesion-03a/555Circuit1.jpg" width=420> <br/>
>> Armamos un circuito que prende y apaga un LED continuamente. <br/>
>> <br/>
>> <img align="left" src="https://github.com/FranUDP/dis8644-2025-1/blob/main/25-FranUDP/sesion-03a/555Circuit1a.jpg" width=420> <br/>
>> <br/>
>> <br/>
>> <br/>
>> Cambiando el valor del capacitor C<sub>1</sub> (conectado al pin 2) y resistencia R<sub>2</sub> (conectada al pin 2, pin 6 y pin 7) aprendimos que mientras menor su capacitancia y menor su resistencia, mayor es la frecuencia de la oscilación. me da la sensación como si estubiesen jugando a hacer ruidos, comenzando siempre con pocos elementos y conforme va progresando la canción, agregando más, pero de forma caotica, algunos sonidos apareniendo solo una o dos veces.
>> <br/>
>> <br/>
>> <br/>
>> <br/>
>
-----------------------------------------------------------------------------------------------------------
## Encargo 06
### Einstürzende Neubauten
> Escuché el album *"Five on the open-Ended Richter Scale"*, me sorprendió lo caoticos que eran los sonidos de las canciones, a diferencia del 90% de la música que tienen partes definidas que suelen repetirse o mantrenerse constantes. <br/> Al escucharlos me daba una sensación... como si no tuviesen una estructura, como si estuviesen jugando con los sonidos, haciendo ruido para ver como suena, sin un orden o ritmo definido. <br/> También están los sonidos que se escuchan a demás de algún que otro instrumento tradicional. Sonidos metálicos, motores, algo que sonaba como un pistón hidraulico... me da la sensación como si estuviesen en un taller mecanico o en una obra en construcción haciendo sonidos golpeando cosas con una llave inglesa o tirando un barril bajo las escaleras.
>
> Tras investigar un poco y ver algunas entrevistas a Blixa, puedo decir que no me esperaba que de verdad tocasen golpeando, raspando, doblando y haciendo quien sabe qué con basura o chatarra que sacaron de un deshuesadero, a pesar que al inicio ello era por necesidad, al no poder costear instumentos.<br/> Aunque supongo que tras ver la filosofia creativa de Blixa tiene sentido, ya que la inprevisibilidad de la vida les dio esos instrumentos, que según menciona Blixa, no podían llevar en sus giras, por lo que se veian forzados a ir a basurales a buscar nuevos para cada performance.<br/> Lo cual también explica el aparente caos y falta de orden en sus canciones, al preferir los patrones aleatorios y/o accidentales que se producen al no tener tanto control del proceso creativo.
> 
-----------------------------------------------------------------------------------------------------------
## Encargo 07
### The 555 rabbit hole
> El 555 obtiene su nombre a partir de las 5 resistencias de 5 ohm conectadas en serie entre el pin 1 (GND) y el pin 8 (VCC)
>
