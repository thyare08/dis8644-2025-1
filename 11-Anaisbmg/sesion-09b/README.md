# sesion-09b

09-05-2025

## apuntes


### pam 8403

módulo mini amplificador estéreo 3w pam8403

es un amplificador de audio estéreo clase D. se distingue por la potencia, eficiencia y tamaño compacto, es un chip que ya tiene sus conexiones listas y funciona por módulo.


### srd05

srd-05vdc-sl-c

relé de 01 canal permite controlar el encendido y apagado de cargas eléctricas, eliminando el contacto directo entre el sistema de control y la carga.

### 555

*astable (oscilador)*

genera pulsos constantes → genera una señal continua alta/baja (1/0) (sí/no)
la frecuencia y el ciclo de trabajo se controlan con resistencias y un condensador.

*monoestable (temporizador)*

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

### circuito pwm 

bom

|Componente| Cantidad |Unidad|
|---|---|---|
|chip |1|555|
|resistencia|2|1k|
|capacitor|1|474n|
|capacitor|1|100n|
|led|1|red|
|diodo|2||
|potenciómetro|1|100k|
|bateria|1|9v|
