# sesion-06a

## proyecto 01 - grupo 04

tomamos el esqueleto base del _"atari punk console"_ el cual modificamos principalmente para aletrar la frecuencia del parlante, mediante botones e interruptores

___circuito atari punk console___

![WhatsApp Image 2025-04-13 at 19 34 12](https://github.com/user-attachments/assets/267c2a69-acd2-4915-a2d4-307851fd5c5f)

___esquematico incial___

![esquematico inicial](https://github.com/user-attachments/assets/29d8da02-e3d8-45dc-826c-3487da9dcc38)

https://github.com/user-attachments/assets/c9842fb0-37ba-478e-acf6-78a376ede468

## 01 - integracion de interruptor

hicimos el ejercicio de cambiar las resistencias experimentales (en este caso la R1), que eran los __LDR__, lo cuales permitian cambiar la frecuencia del parlante mediante aproximacion, decidimos integrar el el interruptor para cortar la energia hacia al parlante desde cero a uno, donde cero es no hay paso de energia y donde un si hay paso de energia

conectando el iterruptor, no lo hicimos directamente a la protoboard, sino paralelamente al parlante, lo cual nos dio como resultado una baja en intensidad de la corriente que pasa al parlante y no la corta a cero, inesperdao pero interesante

___proceso con interruptor___

https://github.com/user-attachments/assets/c925b018-7fd8-4000-ae01-b360d9f27ea8

![WhatsApp Image 2025-04-13 at 17 38 09](https://github.com/user-attachments/assets/10f210cc-c513-4227-8e87-99c0804f16a9)

## 01.1 - experimentacion con componentes externos

usando la base anterior del interruptor, nos aventuramos a usar un componente externos a los que usamos en el taller como reemplazo de la R2, usamos unan caja de clip de metal, y los resultados fueron interesantes ya que conectamos dos caimanes a la caja la cual estaba separada y al chocar genera enterferencia en el parlante

https://github.com/user-attachments/assets/6b9b32cf-27b5-4d45-b3d7-dab10e0680be

## 02 - integracion de boton

integramos el boton como un "puente" entre la energia y el parlante, la diferencia entre ell boton y el interruptor en este caso es que la comunicacion parlante-fuente de poder es en que el estado cambia cuando se mantiene presionado el boton, una vez se presione cambia la frecuencia del parlante, usamos los leds como feedback de el paso de energia en el circuito

https://github.com/user-attachments/assets/9e36eba8-5350-4d1f-8f8d-8dc676832207

## 03 - botones en paralelo ("piano")

ya con el primer boton integrado, logramos crear una secuencia de botones en paralelo que provocan distintos cambios en la frecuena del sonido del parlante, lo cual denominamos como _"piano"_

https://github.com/user-attachments/assets/81ee4759-0f37-4b5d-94a1-204632bcf14a

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
