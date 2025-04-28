# sesion-06a

## proyecto 01 - grupo 04

tomamos el esqueleto base del _"atari punk console"_ el cual modificamos principalmente para alterar la frecuencia del parlante, mediante botones e interruptores

___circuito atari punk console___

![Circuito inicial (1)](https://github.com/user-attachments/assets/7c2c735d-090f-40ac-bf55-433cc590ef26)

<https://github.com/user-attachments/assets/c9842fb0-37ba-478e-acf6-78a376ede468>

___variación con LDR___
![Variación LDR e interruptor](https://github.com/user-attachments/assets/e1cba1e0-da43-4620-9937-608314c05b12)

![Variacion LDR e interruptor (1)](https://github.com/user-attachments/assets/fbdf0739-2229-4918-aae8-4a5d2cfdaeac)

de acá empezamos con las primeras variaciones!

## 01 - integración del interruptor

hicimos el ejercicio de cambiar las resistencias experimentales (en este caso la R1), que eran los __LDR__, lo cuales permitían cambiar la frecuencia del parlante mediante aproximación, decidimos integrar el interruptor para cortar la energía hacia al parlante desde cero a uno, donde cero es no hay paso de energía y donde un sí hay paso de energía

conectando el interruptor, no lo hicimos directamente a la protoboard, sino paralelamente al parlante, lo cual nos dio como resultado una baja en intensidad de la corriente que pasa al parlante y no la corta a cero, inesperado pero interesante

___proceso con interruptor___

<https://github.com/user-attachments/assets/c925b018-7fd8-4000-ae01-b360d9f27ea8>

![WhatsApp Image 2025-04-13 at 17 38 09](https://github.com/user-attachments/assets/10f210cc-c513-4227-8e87-99c0804f16a9)

## 01.1 - experimentación con componentes externos

usando la base anterior del interruptor, nos aventuramos a usar un componente externos a los que usamos en el taller como reemplazo de la R2, usamos unan caja de clip de metal, y los resultados fueron interesantes, ya que conectamos dos caimanes a la caja la cual estaba separada y al chocar genera interferencia en el parlante

<https://github.com/user-attachments/assets/6b9b32cf-27b5-4d45-b3d7-dab10e0680be>

![Variación pulsador, interruptor y caja (2)](https://github.com/user-attachments/assets/f4fabfc1-c263-4797-915b-7a25bd5d4147)

![Variación interruptor, pulsador y caja metálica (1)](https://github.com/user-attachments/assets/2a731b85-cb8a-43ff-a9c3-63ef86621b08)

## 02 - integración de pulsador

integramos el pulsador como un "puente" entre la energía y el parlante, la diferencia entre el pulsador y el interruptor en este caso es que la comunicación parlante-fuente de poder es en que el estado cambia cuando se mantiene presionado el pulsador, una vez se presione cambia la frecuencia del parlante, usamos los leds como feedback del paso de energía en el circuito

<https://github.com/user-attachments/assets/9e36eba8-5350-4d1f-8f8d-8dc676832207>

![Vriacion potenciometro, pulsador e interruptor (2)](https://github.com/user-attachments/assets/f85c423f-ba7f-45ab-8f46-4b055fdb25a4)

![Variacion potenciometro, pulsador e interruptor (4)](https://github.com/user-attachments/assets/8808812d-61ed-449d-ae51-0612a74db720)

## 03 - pulsadores en paralelo ("piano")

ya con el primer pulsador integrado, logramos crear una secuencia de pulsadores en paralelo que provocan distintos cambios en la frecuencia del sonido del parlante, lo cual denominamos como _"piano"_

<https://github.com/user-attachments/assets/81ee4759-0f37-4b5d-94a1-204632bcf14a>

## 03.1 - piano y LDR

a la variación de piano le agregamos un LDR como la R1 para ver la reacción del sensor y el pulsador con el parlante

<https://github.com/user-attachments/assets/b1021b9f-e474-430e-954b-7aea467dbd21>

![Variación pulsadores, LDR e interruptor (1)](https://github.com/user-attachments/assets/60ba4e28-c733-40fd-92b3-24a30b753222)

![Variacion pulsadores, LDR e interruptor (1)](https://github.com/user-attachments/assets/88af819e-a85e-414b-8d78-eff851963ecb)

## bill of materials

| componentes |  cantidad (utilizados) | especificaciones |
|----------|----------|----------|
| condensadores cerámicos   |  4  | 153x1, 474x3   |
| condensadores electrolíticos | 1  | 100ufx1  |
| bateria   | 1   | 9v   |
| pulsadores    | 3   |    |
| interruptor    | 1   |    |
| parlante    | 1   |    |
| protoboard    | 2   |   |
| chip 555   | 2   |    |
| resistencias    | 8   | 1kx3, 10kx3, 100kx1, 470kx1   |
| caimanes   | 4   |    |
| LDR   | 1  |    |
