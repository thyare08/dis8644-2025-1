# sesion-06a

## proyecto 01 - grupo 04

tomamos el esqueleto base del _"atari punk console"_ el cual modificamos principalmente para alterar la frecuencia del parlante, mediante botones e interruptores

___circuito atari punk console___

![Circuito inicial (1)](https://github.com/user-attachments/assets/7c2c735d-090f-40ac-bf55-433cc590ef26)

___esquemático inicial___

![8](https://github.com/user-attachments/assets/ae5d5bd5-2b3c-453f-b7b8-5736a613c7cc)

https://github.com/user-attachments/assets/c9842fb0-37ba-478e-acf6-78a376ede468

## 01 - integración del interruptor

hicimos el ejercicio de cambiar las resistencias experimentales (en este caso la R1), que eran los __LDR__, lo cuales permitían cambiar la frecuencia del parlante mediante aproximación, decidimos integrar el interruptor para cortar la energía hacia al parlante desde cero a uno, donde cero es no hay paso de energía y donde un sí hay paso de energía

conectando el interruptor, no lo hicimos directamente a la protoboard, sino paralelamente al parlante, lo cual nos dio como resultado una baja en intensidad de la corriente que pasa al parlante y no la corta a cero, inesperado pero interesante

___proceso con interruptor___

https://github.com/user-attachments/assets/c925b018-7fd8-4000-ae01-b360d9f27ea8

![WhatsApp Image 2025-04-13 at 17 38 09](https://github.com/user-attachments/assets/10f210cc-c513-4227-8e87-99c0804f16a9)

## 01.1 - experimentación con componentes externos

usando la base anterior del interruptor, nos aventuramos a usar un componente externos a los que usamos en el taller como reemplazo de la R2, usamos unan caja de clip de metal, y los resultados fueron interesantes, ya que conectamos dos caimanes a la caja la cual estaba separada y al chocar genera interferencia en el parlante

https://github.com/user-attachments/assets/6b9b32cf-27b5-4d45-b3d7-dab10e0680be

![Variación pulsador, interruptor y caja](https://github.com/user-attachments/assets/ae7817ff-45d7-4247-b003-7f83755227d3)

![Variación interruptor, pulsador y caja metálica](https://github.com/user-attachments/assets/0b5f8a28-8946-4610-a0a7-f48cdbf57ce3)

## 02 - integración de botón

integramos el botón como un "puente" entre la energía y el parlante, la diferencia entre el botón y el interruptor en este caso es que la comunicación parlante-fuente de poder es en que el estado cambia cuando se mantiene presionado el botón, una vez se presione cambia la frecuencia del parlante, usamos los leds como feedback del paso de energía en el circuito

https://github.com/user-attachments/assets/9e36eba8-5350-4d1f-8f8d-8dc676832207

![image](https://github.com/user-attachments/assets/f514babf-ab69-4763-80a5-6c2e6193bbb4)

![image](https://github.com/user-attachments/assets/70343a13-2945-4440-8f2c-47be0a60ac18)

## 03 - botones en paralelo ("piano")

ya con el primer botón integrado, logramos crear una secuencia de botones en paralelo que provocan distintos cambios en la frecuencia del sonido del parlante, lo cual denominamos como _"piano"_

https://github.com/user-attachments/assets/81ee4759-0f37-4b5d-94a1-204632bcf14a

![Variación pulsadores, LDR e interruptor](https://github.com/user-attachments/assets/78f6d7cf-3101-4b0d-a2c6-dd3cf3b7af5c)

![Variacion pulsadores, LDR e interruptor](https://github.com/user-attachments/assets/9432e544-c3ce-41df-9091-686b7fbee21a)

## 03.1 - piano y LDR

a la variación de piano le agregamos un LDR como la R1 para ver la reacción del sensor y el botón con el parlante

https://github.com/user-attachments/assets/b1021b9f-e474-430e-954b-7aea467dbd21

## componentes

| componentes |  cantidad (utilizados) | especificaciones |
|----------|----------|----------|
| condensadores    |  5  | 153x1, 474x3, 10ufx1   |
| bateria   | 1   | 9v   |
| botones    | 3   |    |
| interruptor    | 1   |    |
| parlante    | 1   |    |
| protoboard    | 2   |   |
| chip 555   | 2   |    |
| resistencias    | 7   | 1kx3, 10kx2, 100kx1, 470kx1   |
| caimanes   | 4   |    |
