# sesion-02a

## Apuntes
>
> ### Carpetas y archivos
> Nombres sin espacios " ", solo guiones "-" y "_" o camelCase (ej: valorTotal)
> Sin letras mayúsculas en nombres de archivos y/o carpetas
> Asegurarse que el archivo tenga la extensión deseada (.exe .txt. .md .stl ...)
>
> ### [Github personal web page](https://youtu.be/o5g-lUuFgpg?si=7qb0U5vslgImk-H2)
> nombrePerfil.github.io = pagina web personal gratis (html, md compatible)
>
> CNAME (Cannonical NAME record). Maps one domain name to another eg: originalName.github.io -> clicheSurame.com (dominio nuevo se tiene que comprar)
>
> [Profile readme generator](https://youtu.be/onUx22pgiBM?si=5ASsmWzo5xztjWpg)
>
> ### [Tinkercad](https://www.tinkercad.com)
> simulación circuitos electricos
>
> ### Circuitos
> cerrado v/s abierto
>> En un circuito cerrado hay flujo de corriente, mientras que en uno abierto, no.
>> 
>><img align="left" src="https://github.com/FranUDP/dis8644-2025-1/blob/main/25-FranUDP/sesion-02a/closedCircuitArduino.jpg" width=300> <img align="center" src="https://github.com/FranUDP/dis8644-2025-1/blob/main/25-FranUDP/sesion-02a/openCircuitArduino_9V.jpg" width=300> <img align="right" src="https://github.com/FranUDP/dis8644-2025-1/blob/main/25-FranUDP/sesion-02a/ClosedCircuit9V.jpg" width=300>
>> Como se ve en las imagenes, un componente puede estar conectado al positivo de una fuente de alimentación y al negativo de otra, pero al no estar cerrado el circuito este LED no se ilumina.
><img align="right" src="https://i.pinimg.com/736x/ca/3c/b4/ca3cb49388066ce14e9acee02dcac84a.jpg" width=300>
> Voltaje = diferencia de potencial entre 2 puntos -> 0V = negativo/tierra
><br/>
><br/>
>
> I=V/R &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Ley de Ohm](https://www.youtube.com/watch?v=HsLLq6Rm5tU)
><br/>
><br/>
>Circuito = laso cerrado con elementos resistivos
><br/>
><br/>
>
> #### Tipos de circuito
> * [Paralelo](https://youtu.be/5uyJezQNSHw?si=AVs_V-hrtPFCKdkU) -> se divide la corriente pero se mantiene el voltaje. Si un componente falla, no falla todo el circuito
>> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img align="middle" src="https://github.com/FranUDP/dis8644-2025-1/blob/main/25-FranUDP/sesion-02a/circuitoParaleloClass.jpg" width=400>
>><br/>
>
> * [Serie](https://youtu.be/VV6tZ3Aqfuc?si=LqOyVR3KekmErDvc) -> Se divide/multiplica el voltaje. Si un componente falla, falla todo el circuito.
>> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img align="middle" src="https://github.com/FranUDP/dis8644-2025-1/blob/main/25-FranUDP/sesion-02a/circuitoSerieClass.jpg" width=400>
>>
___
## Encargo 04
### Pueblo nuevo

___
## Encargo 05
> ### Resistencias
>> <img align="left" src="https://github.com/FranUDP/dis8644-2025-1/blob/main/25-FranUDP/sesion-02a/FotoLibroArduinoResist.jpg" width=600> De acurdo a la tabla vista en la foto, las siguientes resistencias tendrian los siguientes colores (4 y 5 bandas, sin banda de tolerancia):
>> 
>> 1 Ohm ![#4e4e4e](https://placehold.co/15x15/4e4e4e/4e4e4e.png) ![#9d3a1f](https://placehold.co/15x15/9d3a1f/9d3a1f.png) ![#4e4e4e](https://placehold.co/15x15/4e4e4e/4e4e4e.png)
>>
>> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![#4e4e4e](https://placehold.co/15x15/4e4e4e/4e4e4e.png) ![#4e4e4e](https://placehold.co/15x15/4e4e4e/4e4e4e.png) ![#9d3a1f](https://placehold.co/15x15/9d3a1f/9d3a1f.png) ![#4e4e4e](https://placehold.co/15x15/4e4e4e/4e4e4e.png)
>>
>> <br/>
>>
>>  10 Ohm ![#9d3a1f](https://placehold.co/15x15/9d3a1f/9d3a1f.png) ![#4e4e4e](https://placehold.co/15x15/4e4e4e/4e4e4e.png) ![#4e4e4e](https://placehold.co/15x15/4e4e4e/4e4e4e.png)
>> 
>> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![#4e4e4e](https://placehold.co/15x15/4e4e4e/4e4e4e.png) ![#9d3a1f](https://placehold.co/15x15/9d3a1f/9d3a1f.png) ![#4e4e4e](https://placehold.co/15x15/4e4e4e/4e4e4e.png) ![#4e4e4e](https://placehold.co/15x15/4e4e4e/4e4e4e.png)
>>
>> <br/>
>>
>> 100 Ohm ![#9d3a1f](https://placehold.co/15x15/9d3a1f/9d3a1f.png) ![#4e4e4e](https://placehold.co/15x15/4e4e4e/4e4e4e.png) ![#9d3a1f](https://placehold.co/15x15/9d3a1f/9d3a1f.png)
>> 
>> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![#4e4e4e](https://placehold.co/15x15/4e4e4e/4e4e4e.png) ![#9d3a1f](https://placehold.co/15x15/9d3a1f/9d3a1f.png) ![#4e4e4e](https://placehold.co/15x15/4e4e4e/4e4e4e.png) ![#9d3a1f](https://placehold.co/15x15/9d3a1f/9d3a1f.png)
>>
>> <br/>
>>
>> 1k Ohm ![#9d3a1f](https://placehold.co/15x15/9d3a1f/9d3a1f.png) ![#4e4e4e](https://placehold.co/15x15/4e4e4e/4e4e4e.png) ![#ff0000](https://placehold.co/15x15/ff0000/ff0000.png)
>> 
>> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![#9d3a1f](https://placehold.co/15x15/9d3a1f/9d3a1f.png) ![#4e4e4e](https://placehold.co/15x15/4e4e4e/4e4e4e.png) ![#4e4e4e](https://placehold.co/15x15/4e4e4e/4e4e4e.png) ![#9d3a1f](https://placehold.co/15x15/9d3a1f/9d3a1f.png)
>><br/>
>><br/>
>><br/>
>><br/>
>><br/>
>><br/>
>><br/>
>><br/>
>><br/>
>><br/>
>><br/>
>><br/>
>
> ### LEDs
>> El rango de voltaje en que operan difiere entre LEDs de distintos colores.
>> Para determinar el rango de voltaje de un LED se puede usar una [calculadora de voltaje](https://somanytech.com/led-voltage-calculator-for-different-color/) o testear el LED con un multimetro (in diode mode)
>> 
>> <img align="left" src="https://somanytech.com/wp-content/uploads/2023/04/optim-online-led-voltage-calculator-smd.jpg" width=600> Tras medir los LEDs que nos dieron los profes (Ø3.5mm), estos son los voltajes optimos de operación:
>>
>> | Color | Voltaje |
>> |-------|---------|
>> | $${\color{white}Blanco}$$ | 2.6 |
>> | $${\color{blue}Azul}$$ | 2.5 |
>> | $${\color{yellow}Amarillo}$$ | 1.9 |
>> | $${\color{green}Verde}$$ | 1.9 |
>> | $${\color{red}Rojo}$$ | 1.8 |
>><br/>
>><br/>
>><br/>
>><br/>
>><br/>
>><br/>
>><br/>
>><br/>
>><br/>
>
>### Experimentos
