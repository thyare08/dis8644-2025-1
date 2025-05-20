# sesion-11a
20/05/2025
**Componentes:**
* r          * +9vol
* c          * led
* d          * op-amp
* ic         * ldr
* pot        * relé
* bat        * proto
* ps         * sn (estaño)
* pcb        * perfboard

**Circuitos:**
*APC
*PWM
*astable + monostable = APC 

**Aplicaciones:**
* apc
* brillo - led
* on/off - ampolleta
* sinte - udpudu

## Estudio de chips y modulos
Día de hoy: uso de motor 

transistor mosfet: tiene 3 patas, envía una señal para dejar pasar la energía. Controla el flujo y se activa solo con un voltaje de entrada

<img width="538" alt="Captura de pantalla 2025-05-20 a la(s) 11 59 55 a m" src="https://github.com/user-attachments/assets/c5429569-fe9b-417c-ba9a-9056cab15d57" />

motor pwm: la velocidad o potencia del motor se ajusta al variar el ancho de los pulsos de voltaje que se le suministran, en lugar de variar la tensión de forma continua. 

<img width="538" alt="Captura de pantalla 2025-05-20 a la(s) 12 01 59 p m" src="https://github.com/user-attachments/assets/e834d21e-12d2-4060-835e-7089c33935ae" />

conectar al circuito a un transistor que se conecta a un motor.

<img width="538" alt="Captura de pantalla 2025-05-20 a la(s) 12 02 47 p m" src="https://github.com/user-attachments/assets/940674a3-9faf-492f-8575-2e74fa4538e8" />

<img width="538" alt="Captura de pantalla 2025-05-20 a la(s) 12 03 35 p m" src="https://github.com/user-attachments/assets/80985710-d376-47af-a9b4-d159a968ee41" />

https://github.com/user-attachments/assets/e2bf2f33-2f52-4a92-a823-d0fa2a2c49e9

luego se cambió el potenciometro por un ldr y una resistencia 

<img width="544" alt="Captura de pantalla 2025-05-20 a la(s) 12 29 58 p m" src="https://github.com/user-attachments/assets/2e1cb681-bab8-4b1b-8cee-035ff27a9033" />

ps: power supply 

* 9v - * portátil
       * accesible
       * recargable
       * alto voltaje

* usb -  * portátil (power balk)
   o
transfo. * accesible
         * recargable
         * voltaje 5v 
     
traer el viernes una power balk y un cable usb para romper 


## encargo-22: documentación textual del proceso de ensamblado de udpudu

Herramientas y materiales necesarios:

1. Cautín
2. Estaño
3. Alicates de corte
4.  Esponja o lana metálica para limpiar la punta del cautín

## Pasos a seguir
**PASO 1: Juntar los componentes necesarios**

* Verificar y revisar la BOM, asegurarse de tener todos los elementos necesarios.
* Organizar los componentes por tipo: resistencias, condensadores, etc.

**PASO 2: Verificar funcionamiento e insertar componentes**

* Rehacer el circuito en la protoboard para verificar su funcionamiento y hacer cambios de componentes.
* Una vez verificado el circuito y que todo funcione, insertar los componentes en la PCB.

Tips:

Doblar las patas de los componentes para que no se salgan al dar vuelta la PCB.

Si hay polaridad, verificar orientación (ej: condensadores electrolíticos, diodos, LEDs).

**PASO 3: Soldar**

* Calentar el cautín.

* Limpiar la punta del cautín antes de cada soldadura.
* Aplicar calor a la pista de cobre y la pata del componente al mismo tiempo.
* Aplicar el estaño sobre la unión (no sobre la punta del cautín).
* Quitar el estaño y luego el cautín.
* Verificar que la soldadura haya quedado bien (evitar soladurad frías, opacas o con forma de bola).

**PASO 4: Cortar excesos**

*Una vez que todos los componentes estén soldados, usar el alicate para cortar las patas sobrantes lo más cerca posible de la soldadura (también se peude usar un cortauñas).

IMPORTANTE: tomar la pata que se cortará para que no salte ni mate a nadie.

**PASO 5: Verificar**

* Revisar visualmente que no haya puentes de soldadura.
* Verificar orientación de componentes.
*( Opcional) Usar un multímetro para chequear continuidad y valores de resistencias.

**PASO 6: Energizar y probar**

* Conectar la alimentación
* Verificar funcionamiento del circuito

## encargo-23: documentación visual del proceso de ensamblado de udpudu

**Asegurarse de tener todos los elementos necesarios**

<img width="935" alt="Captura de pantalla 2025-05-19 a la(s) 10 00 50 p m" src="https://github.com/user-attachments/assets/2bab76e1-87d4-4673-8ad7-4d3d1ef42970" />

*foto por @/ AlanisMria en discord*

**Rehacer el circuito en la protoboard**

<img width="558" alt="Captura de pantalla 2025-05-19 a la(s) 10 03 39 p m" src="https://github.com/user-attachments/assets/99c189c2-c9d1-4a94-89af-dbda8d4de0d2" />

**Insertar los componentes en la PCB**

<img width="558" alt="Captura de pantalla 2025-05-19 a la(s) 10 05 17 p m" src="https://github.com/user-attachments/assets/da666302-5cdf-4df9-9dcd-c2aa5c4ebbe1" />

<img width="762" alt="Captura de pantalla 2025-05-19 a la(s) 10 07 39 p m" src="https://github.com/user-attachments/assets/17ab7bee-2691-45ce-b0b1-eb7fd74903ab" />

**Soldar**

<img width="523" alt="Captura de pantalla 2025-05-19 a la(s) 10 09 09 p m" src="https://github.com/user-attachments/assets/eb7a0278-1dda-449c-ba13-2c386c0f26bf" />

**Cortar excesos**

<img width="479" alt="Captura de pantalla 2025-05-19 a la(s) 10 11 03 p m" src="https://github.com/user-attachments/assets/0cc78e93-0cb4-4f80-80d4-e9df662f8e10" />

<img width="557" alt="Captura de pantalla 2025-05-19 a la(s) 10 11 40 p m" src="https://github.com/user-attachments/assets/579e92b5-759d-4bd6-a769-03d9d3904f17" />

**Energizar y probar**

<img width="895" alt="Captura de pantalla 2025-05-19 a la(s) 10 12 39 p m" src="https://github.com/user-attachments/assets/0e560c28-e727-485e-a3ae-6ae44d97dd30" />

*foto por @/ AlanisMria en discord*









