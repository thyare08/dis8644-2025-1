# sesion-02a

## Apuntes
>
> ### Carpetas y archivos
>
> Nombres sin espacios " ", solo guiones "-" y "_" o camelCase (ej: valorTotal)
> Sin letras mayúsculas en nombres de archivos y/o carpetas
> Asegurarse que el archivo tenga la extensión deseada (.exe .txt. .md .stl ...)
>
> ### [Github personal web page](https://youtu.be/o5g-lUuFgpg?si=7qb0U5vslgImk-H2)
>
> nombrePerfil.github.io = pagina web personal gratis (html, md compatible)
>
> CNAME (Cannonical NAME record). Maps one domain name to another eg: originalName.github.io -> clicheSurame.com (dominio nuevo se tiene que comprar)
>
> [Profile readme generator](https://youtu.be/onUx22pgiBM?si=5ASsmWzo5xztjWpg)
>
> ### [Tinkercad](https://www.tinkercad.com)
>
> simulación circuitos electricos
>
> ### Circuitos
>
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
>
> * [Paralelo](https://youtu.be/5uyJezQNSHw?si=AVs_V-hrtPFCKdkU) -> se divide la corriente pero se mantiene el voltaje. Si un componente falla, no falla todo el circuito
>
>> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img align="middle" src="https://github.com/FranUDP/dis8644-2025-1/blob/main/25-FranUDP/sesion-02a/circuitoParaleloClass.jpg" width=400>
>><br/>
>
> * [Serie](https://youtu.be/VV6tZ3Aqfuc?si=LqOyVR3KekmErDvc) -> Se divide/multiplica el voltaje. Si un componente falla, falla todo el circuito.
>
>> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img align="middle" src="https://github.com/FranUDP/dis8644-2025-1/blob/main/25-FranUDP/sesion-02a/circuitoSerieClass.jpg" width=400>
>>
___

## encargo-04

### Pueblo nuevo
>
> Escuché el disco Tecnoasuar de CASTEX y S3T3 (lo elegí pq el autocorrector de mi cerebro acostumbrado al inglés le cambió el titulo a *Tecnosaur*). Lo primero que llamó mi atención fue que la canción "Música con computadores" no sonaba como un dinosaurio robótico, sino como una clase de música grabada con un microfono antiguo. Tras escuchar el resto del álbum estaba seguro que tenía relación con algo pedagógico, lo cual se me hiso bien extraño, por que nunca habia escuchado de un disco cuyas canciones fuesen hechas como ejemplos prácticos para enseñar.
>
>Tras leer la descripción del álbum me di cuenta que el disco que escuché no era un conjunto de ejemplos prácticos (o quizas sí, no se suficiente de musica para decirlo), sino que es un homenaje a un disco que sí tenia como objetivo enseñar música y a su creador José Vicente Asuar, un pionero de la música electroacústica en Chile, creador del primer laboratorio de música electrónica en latinoamérica y del sintetizador COMDASUAR.
>
>Fuera del contexto del álbum, encontré curioso que en el disco, el componente vocal no tiene emoción ni un ritmo musical, a diferencia de otras obras de música electrónica ej: *"Around the world"* de Daft Punk, es como si un computador hubiese "cantado" la parte vocal.
___

## encargo-05
>
> ### Resistencias
>>
>> <img align="left" src="https://github.com/FranUDP/dis8644-2025-1/blob/main/25-FranUDP/sesion-02a/FotoLibroArduinoResist.jpg" width=600> De acurdo a la tabla vista en la foto, las siguientes resistencias tendrian los siguientes colores (4 y 5 bandas, sin banda de tolerancia):
>>
>> 1 Ohm ![#4e4e4e](https://placehold.co/15x15/4e4e4e/4e4e4e.png) ![#9d3a1f](https://placehold.co/15x15/9d3a1f/9d3a1f.png) ![#4e4e4e](https://placehold.co/15x15/4e4e4e/4e4e4e.png)
>>
>> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![#4e4e4e](https://placehold.co/15x15/4e4e4e/4e4e4e.png) ![#4e4e4e](https://placehold.co/15x15/4e4e4e/4e4e4e.png) ![#9d3a1f](https://placehold.co/15x15/9d3a1f/9d3a1f.png) ![#4e4e4e](https://placehold.co/15x15/4e4e4e/4e4e4e.png)
>>
>> <br/>
>>
>> 10 Ohm ![#9d3a1f](https://placehold.co/15x15/9d3a1f/9d3a1f.png) ![#4e4e4e](https://placehold.co/15x15/4e4e4e/4e4e4e.png) ![#4e4e4e](https://placehold.co/15x15/4e4e4e/4e4e4e.png)
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
>>
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
>>
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
>>
>> 1. LED (Ø3.5mm) + LED Ø11mm + potenciómetro
>>
>> <img align="left" src="https://github.com/FranUDP/dis8644-2025-1/blob/main/25-FranUDP/sesion-02a/exp1.jpg" width=450> <img src="https://github.com/FranUDP/dis8644-2025-1/blob/main/25-FranUDP/sesion-02a/exp1D.jpg" width=300>
>>
>> Tras medir ambas LEDs con un multimetro y ver que ambas se encendian con el mismo voltaje, con Martin las conectamos en serie para ver la differencia de brillo entre ambas.
>> El LED más grande tiene un voltaje máximo más alto que el led más pequeño (3.3V v/s 2V) y se ilumina más.
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
>>
>> 2. LED (x2) + resistencia (x3) + potenciómetro
>>
>> <img align="left" src="https://github.com/FranUDP/dis8644-2025-1/blob/main/25-FranUDP/sesion-02a/exp2.jpg" width=450> <img src="https://github.com/FranUDP/dis8644-2025-1/blob/main/25-FranUDP/sesion-02a/exp2D.jpg" width=300>
>>
>> Conecté 2 LEDs a los extremos de un potenciómetro para ver si lograba que una se apagara al aumentar la resistencia.
>> No logré que se apagara alguna de las LEDs.
>><br/>
>><br/>
>><br/>
>>
>> 3. LED white + LED red + resistencia + potenciómetro
>>
>> <img align="left" src="https://github.com/FranUDP/dis8644-2025-1/blob/main/25-FranUDP/sesion-02a/exp3.jpg" width=450> <img src="https://github.com/FranUDP/dis8644-2025-1/blob/main/25-FranUDP/sesion-02a/exp3D_1.jpg" width=300>
>>
>> Tras ver que el LED blanco se apagaba al conectarlo junto con uno rojo, armé un circuito para ver que pasa si un LED recive el flujo de electrones antes que el otro.
>> Cambia la intensidad del LED rojo en &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; una curva + - +, pero el LED blanco se mantiene apagado.
>>
>> 4. LED white + LED red + resistencia + potenciómetro
>>
>> <img align="left" src="https://github.com/FranUDP/dis8644-2025-1/blob/main/25-FranUDP/sesion-02a/exp4.jpg" width=450> <img src="https://github.com/FranUDP/dis8644-2025-1/blob/main/25-FranUDP/sesion-02a/exp4D.jpg" width=300>
>>
>> Decidí conectar los LEDs independiente uno del otro y ver que pasaba.
>> Al aumentar el voltaje del LED rojo (y disminuir la del blanco), el LED blanco se apaga, sin embargo el LED rojo no se apaga al reducir su voltaje.
>><br/>
>><br/>
>><br/>
>><br/>
