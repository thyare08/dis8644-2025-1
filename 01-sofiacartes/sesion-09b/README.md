# sesion-09b 09/05


## Chip 8403

![PAM8403](https://github.com/user-attachments/assets/77990228-3c5f-446f-af10-8bf4bbe240da)

_imágen rescadada de: <https://vishaworld.com/products/pam8403-5v-two-channel-stereo-mini-class-d-3w-3w-audio-amplifier>_

Es un amplificador de audio estéreo clase D, combinación única de potencia, eficiencia y tamaño compacto.

Se distingue por su relación de potencia-tamaño. Este chip es capaz de entregar hasta 3W por canal en una carga de 4Ω, operando con una fuente de alimentación de 5V. 

**Amplificador de audio estéreo clase D:** 

Son amplificadores conmutados, bien en relación a la etapa de salida, bien en la parte de alimentación o bien en todo el conjunto. 


## SRD05 / Relé de 01 canal

![srd05](https://github.com/user-attachments/assets/cff2cdcd-6604-4ff7-8ff0-142d6a39c7d0)

_imágen rescatada de: <https://bracsan.pe/producto/modulo-relay-5v-10a-1-canal-srd05-x1pcb/>_

Permite controlar el encendido/apagado, de equipos de corriente alterna. En otras palabras, provee el aislamiento y conmuta las cargas resistivas de corriente alterna. 

Su configuración es SPDT (un polo, dos tiros).

**Pequeña señal de control con ruido mecánico.**

## Circuito pwm - realizado en clases en tinkercad

<img width="677" alt="Circuito pwm " src="https://github.com/user-attachments/assets/6b430a90-d6de-4452-a5f8-6ecda5163f80" />

### BOM:

|Componente| Cantidad |Unidad|
 |----|------|------|
 |resistencia|2|1k|
 |chip |1|555|
 |capacitor|1|474n|
 |capacitor|1|100n|
 |diodo|2||
 |led|1|red|
 |potenciómetro|1|100k|
 |bateria|1| 9v|

## Circuito pwm con variación - realizado en clases en tinkercad

<img width="1315" alt="Circuitopwmconvariación" src="https://github.com/user-attachments/assets/adc2e5a1-1e4a-4fcc-9d06-603f7f83f895" />

### BOM:

|Componente| Cantidad |Unidad|
 |----|------|------|
 |resistencia|2|1k|
 |chip |1|555|
 |capacitor|1|474n|
 |capacitor porlarizado|1|100uf|
 |diodo|2||
 |led|1|red|
 |potenciómetro|1|100k|
 |bateria|1| 9v|

 
_información sacada de:_

_1. <https://maxelectronica.cl/reles-electromecanicos/494-rele-electromecanico-modelo-srd-05vdc-sl-c-5v.html#:~:text=Este%20rel%C3%A9%20de%205%20volts,circuito%20impreso%20de%20orificio%20pasante.>_

_2. <https://www.electrohobby.es/amplificador/178-amplificador-estereo-pam8403.html>_

_3. <https://www.sarte-audio.com/sites/default/files/los_amplificadores_en_clase_d-1.pdf>_


