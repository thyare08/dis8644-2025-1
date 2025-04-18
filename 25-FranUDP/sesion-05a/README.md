# sesion-05a

## Apuntes
>
> ### Atary punk modding
> <img align="left" src="https://github.com/disenoUDP/dis8644-2025-1/blob/main/00-docentes/sesion-04a/archivos/atariPunk_v1.png" width=850> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/>  <img align="left" src="./files/capacitorC5.jpg" width=400> <br/> ${\color{#6462fe}Capacitor \ C5}$ protege al parlante del flujo constante de corriente y convierte la onda de un abrupto on/off a una transcición más gradual de estado, lo que permite escuchar más del sonido, al hacer que "hayan más pasos" entre on y off <br/> <br/>
>> ### Componenetes variables
>> Los valores de R1, C1, R4 y C3 pueden ser variados, mediandte resistencias variables y/o añadiendo capacitores en paralelo, resultando en variaciones del sonido emitido por el atari punk. <br/> <br/>
>> Conecté 2 capacitores en paralelo, con un potenciómetro entre 2 de sus teminales en un intento de variar la capacitancia del segundo capacitor, teniendo en cuenta que una mayor resistencia hace que un capacitor se cargue más lento + el 555 descargando y <img align="left" src="./files/capacitorFalstad.gif" width=490> &nbsp;&nbsp;&nbsp;cargando los capacitores constantemente = el segundo capacitor no alcanzaría a cargarse completamente antes de volver a descargarse. <br/> <br/>
>> Parece que tuve exito, pues al variar el valor del potenciometro, el sonido proveniente del atari punk varía. <br/> <br/> 
>> sin embargo, al testear mi hipotesis en falstad, veo que mi suposición no es del todo correcta, pues el segundo capacitor (izquierda) se carga a un voltaje máximo que varía dependiendo del valor del potenciómetro, mas sin importar el tiempo transcurrido, este no continuará cargandose hasta alcanzar el voltaje de la bateria, sino el voltaje resultante tras reducirlo con el potenciómetro.
>> ### [Pin 5](https://youtu.be/0zV9W_TUAz4?si=N-xVU88uQmXDHj9_&t=367)
>> <img align="left" src="./files/555HowWorks.jpg" width=600> Se suele utilizar para estabilizar la señal que emite el 555, sin embargo también nos permite hacer un override al 2/3 Vcc con el cual es comparado el voltaje del pin2, lo cual tiene el efecto de ampliar o acortar la longitud de onda en el 555 astable. <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/>
> 
> ### Other things
>> ### [0ohm](https://0ohm.cl/)
>> [JLCPCB](https://jlcpcb.com/) / [PCBWAY](https://www.pcbway.com/) (chinese PCB [Printed Circuit Board] manufacturers) chileno, pero que trabaja para industrias y no minoristas.
>> 
>> ### [Chrystal oscilator](https://youtu.be/_2By2ane2I4?si=mo4OQt6n-ufwWhaF)
>> Componente electrónico empleado para determinar precisamente el paso del tiempo
>> 
>> ### Menu diving
>> Navegación de un menú con muchas opciones e información distribuidas en multiples sub-menus por limitaciones de tamaño usualmente o mal diseño (similar a navegar en carpetas de archivos de programa buscando algo en especifico)
>> 
>> ### Eliminador de pila
>> Power Supply Unit (PSU) que alimenta a un objeto en lugar de una batería
>> 
>> ### AC/DC coupling
>> 
>> 
>> ### Calculos
>>> ### Resistencias en paralelo
>>> 
>>> 
>>> ### Capacitores en serie
>>> 
>>> 

