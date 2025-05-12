# sesion-05a

## Apuntes
>
> ### Atary punk modding
>
> <img align="left" src="https://github.com/disenoUDP/dis8644-2025-1/blob/main/00-docentes/sesion-04a/archivos/atariPunk_v1.png" width=850> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/>  <img align="left" src="./files/capacitorC5.jpg" width=400> <br/> ${\color{#6462fe}Capacitor \ C5}$ protege al ${\color{#b0e6e6}parlante}$ del constante ${\color{Red}flujo \ de \ corriente}$ y convierte la onda de un abrupto ${\color{white}on/off}$ a una transición más ${\color{#b0e6e6}gradual}$ de estado, lo que permite ${\color{#b0e6e6}percibir}$ mejor el sonido, al generar una mayor  ${\color{#b0e6e6}cantidad \ de \ pasos}$ entre ${\color{white}on}$ y ${\color{white}off}$ <br/> <br/>
>
>> ### Componenetes variables
>>
>> Los valores de ${\color{#ffe4a8}R1}$, ${\color{#6462fe}C1}$, ${\color{#ffe4a8}R4}$ y ${\color{#6462fe}C3}$ pueden ser alterados, mediante ${\color{#ffe4a8}resistencias \ variables}$ y/o añadiendo ${\color{#6462fe}capacitores}$ en paralelo, resultando en variaciones del sonido emitido por el ${\color{#b0e6e6}atari \ punk}$. <br/> <br/>

>> Conecté ${\color{#6462fe}2 \ capacitores}$ en ${\color{#b0e6e6}paralelo}$, con un ${\color{#ffe4a8}potenciómetro}$ entre 2 de sus terminales en un intento de variar la ${\color{#6462fe}capacitancia}$ del segundo ${\color{#6462fe}capacitor}$, teniendo en cuenta que una ${\color{#ffe4a8}mayor \ resistencia}$ hace que un ${\color{#6462fe}capacitor}$ se ${\color{Red}cargue \ más \ lento}$ + el ${\color{#b0e6e6}555}$ <br/> &nbsp;&nbsp;&nbsp; ${\color{white}descargando}$ y <img align="left" src="./files/capacitorFalstad.gif" width=490> ${\color{Red}cargando}$ los ${\color{#6462fe}capacitores}$ ${\color{#b0e6e6}constantemente}$ <br/> &nbsp;&nbsp;&nbsp; = el segundo ${\color{#6462fe}capacitor}$ ${\color{Red}no \ alcanzaría \ a \ cargarse}$ <br/> &nbsp;&nbsp;&nbsp; completamente antes de volver a ${\color{white}descargarse}$. <br/>
>> <br/>
>> &nbsp;&nbsp;&nbsp; Parece que tuve éxito, pues al variar el valor del <br/> &nbsp;&nbsp;&nbsp; ${\color{#ffe4a8}potenciómetro}$, el sonido proveniente del atari punk ${\color{#b0e6e6}varía}$. <br/>
>>
>> &nbsp;&nbsp;&nbsp; Sin embargo, al testear mi hipótesis en ${\color{#b0e6e6}Falstad}$, veo que mi <br/> &nbsp;&nbsp;&nbsp; suposición no es del todo correcta, pues el segundo <br/> &nbsp;&nbsp;&nbsp; ${\color{#6462fe}capacitor \ (izquierda)}$ se ${\color{Red}carga \ a \ un}$ ${\color{Red}voltaje}$ ${\color{Red}máximo}$ que <br/> &nbsp;&nbsp;&nbsp; varía dependiendo del valor del ${\color{#ffe4a8}potenciómetro}$, mas sin <br/> &nbsp;&nbsp;&nbsp; importar el tiempo transcurrido, este ${\color{#b0e6e6}no}$ continuará <br/> &nbsp;&nbsp;&nbsp; ${\color{Red}cargándose}$ hasta alcanzar el ${\color{Red}voltaje \ de \ la \ batería}$, sino el <br/> &nbsp;&nbsp;&nbsp; ${\color{Red}voltaje}$ resultante tras reducirlo con el ${\color{#ffe4a8}potenciómetro}$. <br/>
>>
>> ### [Pin 5 (Control voltage)](https://youtu.be/0zV9W_TUAz4?si=N-xVU88uQmXDHj9_&t=367)
>>
>> <img align="left" src="./files/555HowWorks.jpg" width=600> <br/> <br/> <br/> Se suele utilizar para ${\color{#b0e6e6}estabilizar}$ la señal que emite el ${\color{#b0e6e6}NE555}$, sin embargo también nos permite hacer un ${\color{#b0e6e6}override}$ al ${\color{Red}2/3 \ Vcc}$ con el cual es comparado el ${\color{Red}voltaje}$ del ${\color{#b0e6e6}Pin2}$, lo cual tiene el efecto de ${\color{Red}aumentar}$ o ${\color{White}reducir}$ la ${\color{#b0e6e6}longitud \ de \ onda}$ en el 555 astable. <br/> <br/> <br/> <br/> <br/> <br/>
>> <img align="left" src=./files/pin5.jpg width=600> <br/> <br/> <br/> <br/> <br/> <br/> Conecté el ${\color{#b0e6e6}Pin5}$ del NE555 a ${\color{Red}Vcc}$ a través de un ${\color{#ffe4a8}potenciómetro}$ para ver/oir que ocurriría, el resultado fue un sonido similar al demostrado por Wendy Carlos en este [video](https://youtu.be/4SBDH5uhs4Q?si=8166nyvCWR1Ox6re&t=127) <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/>
>
> ### Other things <br/>
>>
>> ### [0ohm](https://0ohm.cl/) <br/>
>>
>> [JLCPCB](https://jlcpcb.com/) / [PCBWAY](https://www.pcbway.com/) (chinese PCB [Printed Circuit Board] manufacturers) chileno, pero que trabaja para industrias y no minoristas. <br/>
>>
>> ### [Chrystal oscillator](https://youtu.be/_2By2ane2I4?si=mo4OQt6n-ufwWhaF) (quartz) <br/>
>>
>> Componente electrónico empleado para determinar precisamente el paso del tiempo <br/>
>>
>> ### Menu diving <br/>
>>
>> Navegación de un menú con muchas opciones e información distribuidas en múltiples sub-menus usualmente por limitaciones de tamaño o mal diseño (similar a navegar en carpetas de archivos de programa buscando algo en específico) <br/>
>>
>> ### Eliminador de pila <br/>
>>
>> Power Supply Unit (PSU) que alimenta a un objeto en lugar de una batería <br/>
>>
>> ### [AC/DC coupling](https://youtu.be/3h6tH592BEs?si=Qv0bSygBj8Hetm6) <br/>
>>
>> Se muestran los componentes AC (Alternating Current) y DC (Direct Current) de una misma señal al mismo tiempo <br/>
>>
>> ### Calculos
>>>
>>> ### ${\color{#ffe4a8}Resistencias}$ en paralelo
>>>
>>> $$\textcolor{#ffe4a8}{R_{\text{Total}}} = \frac{\textcolor{#ffe4a8}{R_1} \cdot \textcolor{#ffe4a8}{R_2}}{\textcolor{#ffe4a8}{R_1} + \textcolor{#ffe4a8}{R_2}}$$ <br/>
>>>
>>> ### ${\color{#6462fe}Capacitores}$ en serie
>>>
>>> $$\textcolor{#6462fe}{C_{\text{Total}}} = \frac{\textcolor{#6462fe}{C_1} \cdot \textcolor{#6462fe}{C_2}}{\textcolor{#6462fe}{C_1} + \textcolor{#6462fe}{C_2}}$$ <br/> <br/>
>>> <br/>
>> <br/>
> <br/>
