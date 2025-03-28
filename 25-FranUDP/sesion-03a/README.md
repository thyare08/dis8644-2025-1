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
> <img align="left" src="https://th.bing.com/th/id/R.a8057d46a9fe796121af98f1a3dd02f3?rik=AAD%2fVV2eYzustQ&riu=http%3a%2f%2ftutordelectronica.weebly.com%2fuploads%2f2%2f4%2f4%2f1%2f24418880%2f239438.jpg%3f623&ehk=s40UHD9u%2ffetT%2bD8Yr1tyAEp6rkjAxeDieXO5BjA7ys%3d&risl=&pid=ImgRaw&r=0" width=400>
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
>> &nbsp;&nbsp;&nbsp;Similares a una bateria en que atrapan y liberan electrones
>> &nbsp;&nbsp;&nbsp;(carga/corriente), pero difieren en que estos se cargan
>> &nbsp;&nbsp;&nbsp;mucho más rapidamente y tienen una capacidad muchisimo
>> &nbsp;&nbsp;&nbsp;más limitada. <br/>
>> &nbsp;&nbsp;&nbsp;Se suelen utilizar para estabilizar señales (pulsación como
>> &nbsp;&nbsp;&nbsp;metralleta -> pulsación estable, al evitar un on-off de golpe
>> &nbsp;&nbsp;&nbsp;al descargarse el capacitor)
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
> <img align="left" src="https://github.com/FranUDP/dis8644-2025-1/blob/main/25-FranUDP/sesion-03a/555Pinout.jpg" width=400> [NE555 datasheet](https://github.com/disenoUDP/dis8644-2025-1/blob/main/00-docentes/sesion-03a/archivos/lm555-datasheet.pdf)
>
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
>> #### Circuito astable
-----------------------------------------------------------------------------------------------------------
## Encargo 06
### Einstürzende Neubauten
>
>
-----------------------------------------------------------------------------------------------------------
## Encargo 07
### The 555 rabbit hole
> El 555 obtiene su nombre a partir de las 5 resistencias de 5 ohm conectadas en serie entre el pin 1 (GND) y el pin 8 (VCC)
>
