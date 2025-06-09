# sesion-12a

27-05-2025

## Apuntes

Pd: Había escrito en Github apuntes sobre la clase y no se realizó mi _commit changes_ , así que rescaté información de bitácoras de mis compañeros :(

* Comenzamos hablando sobre el Chip 555 + Chip 4017 y como lo relacionamos con los semáforos

|Luz|Tiempo|
|---|---|
|Amarilla|4 segundos|
|Roja|60 segundos|
|Verde|60 segundos|

* El tiempo para mantener encendido el semáforo depende del---> **CLK**
* Transistores: Semiconductor, que actúa como amplificador o conmutador de señales. Permite controlar el flujo de corriente eléctrica usando una pequeña señal de entrada y amplificandola en la salida. (IRFZ44N - MPS 2222A)
* El tiempo de duración depende de las resistencias y condensadores
* Carry out: Avisa cuando se sobrepasa la capacidad estimada

**¿Qué es un diagrama de tiempo?**

* Es una gráfica de formas, donde se representa las ondas digitales, permite visualizar los pulsos, cuanto dura el pulso y la posición del inhibidor entre varias señales y como varía cada señal.
* El propósito principal es mostrar los cambios que se pueda realizar en un circuito.

**¿Qué es un diagrama de lógica convencional?**

* Es una representación gráfica que utiliza símbolos para representar operaciones y el orden en el que deben ejecutarse. Son útiles para visualizar y comprender la lógica de un sistema.

**¿Qué es un diagrama de lógica combinacional?**

* Es una representación visual de un circuito digital en el que la salida depende de la combinación de las entradas y de su constitución interna.

* **Cascading** _**The CD4017**_: La cascada de CD4017 se refiere a la conexión de chips CD4017 uno detrás del otro para aumentar el conteo o la división.
* 4017: cuenta hasta 10
* 4022: cuenta hasta 8
* **¿Cómo subir fotos a los archivos?**: Sync Fork > Sesion > Archivos > Add file > Upload files > Commit
* Proyecto 02: en Kicad y Protoboard

## Detector de sombras + Temporizador + Secuenciador

* El circuito se divide en tres partes: primero tiene que funcionar el detector de sombras, si este está correcto debería funcionar el segundo (el temporizador) y por último agregar el secuenciador.

![captura1](https://github.com/user-attachments/assets/64b78347-7405-49a6-b744-26e35d3bcb8e)

<https://github.com/user-attachments/assets/1fca4051-7cf6-449b-8ad7-74852ac973f2>

<https://github.com/user-attachments/assets/45728457-4e39-43be-84b8-086956eaa0c8>
