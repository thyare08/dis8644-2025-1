# sesion-06a

## Sintetizador Pin5-55
>
> #### Integrantes: ${\color{white}Francisco \ Stephens}$, ${\color{white}José \ Morales}$ y ${\color{white}Braulio \ Figueroa}$ <br/>
>
> <br/>
> <br/>
>
>El proyecto parte con la idea de un ${\color{#b0e6e6}sintetizador}$ pocket de uso recreativo para el usuario. <br/> <br/> En un comienzo el sintetizador reproducía un sonido ${\color{#b0e6e6}monótono}$ y no era adecuado a lo que se buscaba. <br/> A través de diversos intentos por buscar un sonido en específico y más variable, se encontró una forma de producir una ${\color{#b0e6e6}escala \ descendiente}$, al probar conectar elementos del circuito de formas variadas. <br/> <br/> Esta variación nos pareció muchísimo menos monótona que lo que se tenía anteriormente y posee una mayor riqueza en cuanto a interacción con el usuario, es por ello que fue elegida para el proyecto final <br/> <br/>
>
> ### haciendo más y logrando menos
>>
>> El sonido emitido por la versión anterior de este circuito comenzó jugando con el ${\color{#b0e6e6}pin5}$ del 555 timer (control voltage), con el objetivo de lograr un sonido alterando una parte del circuito que usualmente es ${\color{#b0e6e6}dejada \ de \ lado}$. <br/> <br/> Sin embargo, este circuito, a pesar lograr algo aproximado al sonido esperado, la variación producida era muy ${\color{#b0e6e6}poco \ perceptible}$.
>>
>>> ### [Wendy Carlos](https://youtu.be/4SBDH5uhs4Q?si=8166nyvCWR1Ox6re&t=127)
>>>
>>> la referencia inicial del proyecto parte por intentar ${\color{#b0e6e6}recrear}$ un sonido parecido al que logra Wendy Carlos en este video
>>
>><https://github.com/user-attachments/assets/d3747b5a-ae32-4fbd-915e-246ecd4d51cc>
>>
>>
> ### En busqueda de la identidad
>
> Nuestro objetivo era un sonido ${\color{#b0e6e6}icónico}$, distintivo del sonido característico del ${\color{#b0e6e6}atari \ punk}$ y sus variantes (sonido persistente electrónico que varia de a poco).
> Queriamos añadir un ${\color{#b0e6e6}ritmo}$ al atari punk
> 
>
><https://github.com/user-attachments/assets/5631af2c-f057-41ac-9430-e160aad07472>
>
>
> ###### Compuesto en FL Studio
>
>
><https://github.com/user-attachments/assets/346432a3-d82d-4862-842e-ccf5c7abdef2>
>
>
> Cuando logramos este sonido, estabamos experimentando con el circuito conectando ambos ${\color{#b0e6e6}pines \ 5}$ de ambos 555 (astable y monostable). <br/> Al hacer esto nos percatamos que al  ${\color{Red}aumentar \ el \ voltaje}$ que recibe el pin5 del 555 monostable, se  ${\color{#b0e6e6}reducía \ el \ volumen \ y \ la \ frecuencia}$ del sonido (es posible que afectase la amplitud de la onda). <br/> <br/>
> Tras percatarnos de este efecto, notamos que  ${\color{#b0e6e6}mientras \ más \ tiempo}$ estuviese conectado ${\color{Red}Vcc}$ al ${\color{#b0e6e6}pin5}$, más ${\color{#b0e6e6}larga}$ sería la escala musical que emita, tras retirar el cable. <br/>
> Además, si se mantiene conectado Vcc al ${\color{#b0e6e6}pin5}$ por unos segundos, el circuito empezará a emitir un "beat".
>
> ### Prototipado final
>> <!--criterio-02: anatomía física, diagramas, ilustraciones, texto -->
>>
>> <!--criterio-04: esquemático eléctrico, bill of materials, citas y referencias-->
>>
>>
>> <img align="left" src="./files/diagrama.jpg" width=850> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/>
>>
>>
>><https://github.com/user-attachments/assets/5eb682e0-7f3b-4274-87ac-318b583221c9>
>>
>>
>>A través de la experimentación se logró obtener un sonido similar al de una ${\color{#b0e6e6}escala \ musical}$, lo cual creemos que ocurre debido que tras conectar el ${\color{#b0e6e6}pin5}$ a  ${\color{Red}Vcc}$ y cambiar su voltaje, el cual es comparado con el voltaje del pin2, de alguna manera se carga un ${\color{#6462fe}capacitor}$ que tras alcanzar  ${\color{white}9V \ == \ 9V \ Vcc}$, el 555 comienza a permitir que se descargue por una fracción de segundo, generando un beat. <br/> Y al  ${\color{#b0e6e6}soltar \ el \ botón}$ y hacer que el ${\color{Red}voltaje}$ del ${\color{#b0e6e6}pin2}$ sea ${\color{#b0e6e6}comparado}$ con ${\color{Red}2/3 \ de \ Vcc}$ de nuevo, ocasiona la escala al ${\color{#b0e6e6}descargarse}$ el ${\color{#6462fe}capacitor}$ mientras el 555 monoestable ${\color{#b0e6e6}regresa}$ a su frecuencia habitual. <br/> <br/>
>> <img align="left" src="./files/circuitoFinal.jpg" width=600> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/>
>>
>> <img align="left" src="./files/dibujo.jpg" width=600> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/>
>> La interacción del usuario con el objeto, mediante 2 ${\color{#ffe4a8}potenciómetros}$, ${\color{#ffe4a8}LDRs}$, un ${\color{#b0e6e6}botón}$ y un ${\color{#b0e6e6}interruptor}$. La carcasa está realizada de forma que sea cómoda al ser tomada con ambas manos. Facilitando ejercer una acción y generar sonidos mediante la interacción y experimentación con las partes del objeto. <br/> <br/>
>>Los ${\color{#ffe4a8}potenciómetros}$ permiten cambiar la ${\color{#b0e6e6}frecuencia}$ y la ${\color{#b0e6e6}longitud \ de \ onda}$ mientras que el botón al ser presionado y ${\color{#b0e6e6}soltado}$, genera un sonido con ${\color{#b0e6e6}escala \ descendente}$. <br/> <br/>
>>Estos sonidos pueden ser distintos según la luz que reciban los ${\color{#ffe4a8}LDRs}$ colocados en la parte superior de la carcasa, causando diferentes variaciones sonoras <br/>
>>
>> ### Bill of materials
>>
>> |  materiales | cantidad |
>> |:------:|:-----:|
>> | ${\color{#b0e6e6}Chip \ 555}$ |2|
>> | ${\color{Red}Batería \ 9v}$ |1|
>> | ${\color{#ffe4a8}Resistencias \ 1k}$  |1|
>> | ${\color{#ffe4a8}Resistencias \ 10k}$   | 1 |
>> | Botón  | 1|
>> | ${\color{#ffe4a8}Ldr}$   | 1 |
>> | Contector bateria | 1 |
>> | ${\color{#ffe4a8}Potenciometro \ 10k}$  | 3 |
>> |  ${\color{#6462fe}Capacitores \ 474}$  | 2 |
>> |  ${\color{#6462fe}Capacitores \ 154}$   | 2 |
>> |   ${\color{#6462fe}Capacitores \ electrolitico \ 100 \ uf}$ | 2 |
>> |  ${\color{#6462fe}Capacitores \ electrolitico \ 10 \ uf}$ | 1 |
>> |  Parlante 8 ohm | 1 |
>> |  Carcasa| 1|
>

[Pin5](https://youtu.be/0zV9W_TUAz4?si=GYJQ9aqAqcNYVX_z&t=348)
