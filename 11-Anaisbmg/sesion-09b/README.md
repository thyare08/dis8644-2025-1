# sesion-09b

09-05-2025

## pam 8403

![pam8403](https://github.com/Anaisbmg/dis8644-2025-1/blob/main/11-Anaisbmg/sesion-09b/archivos/pam8403.jpeg)

![detallepam8403](https://github.com/Anaisbmg/dis8644-2025-1/blob/main/11-Anaisbmg/sesion-09b/archivos/detallepam8403.jpeg)
*ambas fotos sacadas por mi

módulo mini amplificador estéreo 3w pam8403

es un amplificador de audio estéreo clase D. se distingue por la potencia, eficiencia y tamaño compacto, es un chip que ya tiene sus conexiones listas y funciona por módulo.

### srd05

![relé](https://github.com/Anaisbmg/dis8644-2025-1/blob/main/11-Anaisbmg/sesion-09b/archivos/rel%C3%A9.jpeg)

![reésalida](https://github.com/Anaisbmg/dis8644-2025-1/blob/main/11-Anaisbmg/sesion-09b/archivos/rel%C3%A9salida.jpeg)
*ambas fotos sacadas por mi

srd-05vdc-sl-c

relé de 01 canal permite controlar el encendido y apagado de cargas eléctricas, eliminando el contacto directo entre el sistema de control y la carga.

### 555

#### astable (oscilador)

genera pulsos constantes → genera una señal continua alta/baja (1/0) (sí/no)
la frecuencia y el ciclo de trabajo se controlan con resistencias y un condensador.

#### monoestable (temporizador)

da un pulso de salida cuando se activa, está normalmente en estado apagado
cuando recibe un pulso, la salida cambia, definido por una resistencia y un condensador.

### módulo

electrón (e-), materia, componentes (baterías, power supply, condensadores, resistencias, led, cables, potenciómetro, ldr, etc.), circuitos (apc, as, ms, pls), caja negra (módulo)

### diagrama de flujo

ejemplo: detecta sombra → timer → interruptor → ampolleta

### *duty*

es tiempo/período que pasa encendido se genera un promedio:

existe uno 5 y 0, pero se mantiene más en 5, pero aún va a 0; el promedio podría ser 4

existe uno 5 y 0, y el tiempo en cada uno de estos es el mismo; el promedio podría ser 2,5

existe uno 5 y 0, pero se mantiene más en 0, pero aún va a 5; el promedio podría ser 1

## circuito pwm

bom

|Componente| Cantidad |Unidad|
|---|---|---|
|chip |1|555|
|resistencia|2|1k|
|capacitor|1|474n|
|capacitor|1|100n|
|led|1|red|
|diodo|2||
|potenciómetro|1|500k|
|bateria|1|9v|

![circuitoPWM](https://github.com/Anaisbmg/dis8644-2025-1/blob/main/11-Anaisbmg/sesion-09b/archivos/circuitoPWM.png)

|Componente| Cantidad |Unidad|
|---|---|---|
|chip |1|555|
|resistencia|2|1k|
|capacitor|1|474n|
|capacitor polarizado|1|100uf|
|led|1|red|
|diodo|2||
|potenciómetro|1|500k|
|bateria|1|9v|

![foto](https://github.com/Anaisbmg/dis8644-2025-1/blob/main/11-Anaisbmg/sesion-09b/archivos/foto.png)
*es el de abajo c:

## encargo-18: de tinkercad a protoboard

<https://github.com/user-attachments/assets/4d91e212-cf3a-4007-b8a4-8b6d037d3462>

copiado directo desde galeria

[pwm.anaisbmg](https://youtube.com/shorts/mt0j7jvq76E?feature=share)

link a youtube

## encargo-19: cultura electrónica y laurie anderson

O Superman fue la primera canción que escuché de Laurie Anderson, sin saber que era de ella. la escuché en videos de TikTok y YouTube. al realizar los encargos, siempre busco en YouTube y en Google para tener un poco de contexto sobre la persona, me impresionó. luego empecé a indagar más sobre ella y considero que es increíble, ya que su capacidad de exploración y las performances que realiza son totalmente sorprendentes para mí.

me llama mucho la atención su exploración material, como la creación de nuevos instrumentos; por ejemplo, el violín que transforma de algo tan clásico a algo completamente electrónico. eso me parece sorprendente. me genera una sensación similar a la que tuve al escuchar a Clara Rockmore o al ver la performance Duets on Ice, que esta finaliza cuando se derrite por completo el hielo de sus pies, considerando que esta con patines de hielo.

seguí investigando y descubrí que ella se destaca en diversas áreas. además, busca aprender nuevas habilidades para no encasillarse en una temática específica, lo cual me parece totalmente admirable como persona.

algunas de las performances que destaco son: Pillow Speaker, Laurie Anderson and Her Musical Head y Laurie Anderson and Her Clone, precisamente por lo que mencionaba antes: su exploración material, su conexión con la electrónica, su ironía y otras características que la hacen única.
