# sesion-06a

## atari punk console

tomamos el esqueleto base del _"atari punk console"_ el cual modificamos principalmente para aletrar la frecuencia del parlante, mediante botones e interruptores

___esquematico incial___

![esquematico inicial](https://github.com/user-attachments/assets/29d8da02-e3d8-45dc-826c-3487da9dcc38)

https://github.com/user-attachments/assets/c9842fb0-37ba-478e-acf6-78a376ede468

## 01 - integracion de interruptor

hicimos el ejercicio de cambiar las resistencias experimentales, que eran los __LDR__, lo cuales permitian cambiar la frecuencia del parlante mediante aproximacion, decidimos integrar el el interruptor para cortar la energia hacia al parlante desde cero a uno, donde cero es no hay paso de energia y donde un si hay paso de energia

conectando el iterruptor, no lo hicimos directamente a la protoboard, sino paralelamente al parlante, lo cual nos dio como resultado una baja en intensidad de la corriente que pasa al parlante y no la corta a cero

___proceso con interruptor___

https://github.com/user-attachments/assets/c925b018-7fd8-4000-ae01-b360d9f27ea8

## 02 - integracion de boton

integramos el boton como un "puente" entre la energia y el parlante, la diferencia entre ell boton y el interruptor en este caso es que la comunicacion parlante-fuente de poder es en que el estado cambia cuando se mantiene presionado el boton, una vez se presione cambia la frecuencia del parlante, usamos los leds como feedback de el paso de energia en el circuito

https://github.com/user-attachments/assets/9e36eba8-5350-4d1f-8f8d-8dc676832207

## 03 - botones en paralelo ("piano")

ya con el primer boton integrado, logramos crear una secuencia de botones en paralelo que provocan distintos cambios en la frecuena del sonido del parlante, lo cual denominamos como _"piano"_

https://github.com/user-attachments/assets/81ee4759-0f37-4b5d-94a1-204632bcf14a
