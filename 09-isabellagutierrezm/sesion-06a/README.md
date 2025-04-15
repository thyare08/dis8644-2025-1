# sesion-06a
## Proyecto 01
Este proyecto surge como inspiración de los circuitos eléctricos y experimentos vistos en clase. Los resultados obtenidos nos han impulsado en la creación de este sintetizador que tiene como base el **oscilador “Atari Punk Console”**, generando una versión,  la cual requiere de **un usuario que pueda conectarse a dicha máquina, para ser la resistencia y desencadenar el sonido**, a través del uso del parlante. Para ello se han realizado modificaciones en los componentes, (tipo, capacidad, entre otros) y la estructura física, permitiendo alterar los sonidos generados por la **conexión humano-máquina.**

Como fue mencionado anteriormente, el proceso del aparato se remonta a los **experimentos realizados en las clases**. Tras haber tomado el proceso y los resultados, proseguimos a tomar enfoque en qué tipo de dispositivo podemos realizar, con los conocimientos adquiridos, destacándose por desarrollar un sintetizador que pueda interactuar de forma más íntima con el usuario, y **generar una experiencia personal que pueda ser trabajada de forma única o grupal**. Una máquina que pueda percibir aquellos **procesos naturales que no son capaces de percibir por el humano**.


Para ello catalogamos los sensores según el uso que podemos darles:


- **Sensor infrarrojo** (presencia y cercanía al objeto):Es un dispositivo **optoelectrónico** que detecta y mide la radiación infrarroja  emitida por los objetos.

- **Rayos infrarrojos:** Radiación electromagnética que posee una menor longitud de onda que la luz visible, que nuestros ojos son incapaces de percibir la radiación , pero se puede detectar como una **sensación de calor.**

Pudimos observar el funcionamiento de este sensor al estudiar los elementos que componen el **“dron de luces”** presentado en la sesión “05a”, el cuál vuela a una altura variable que es continuamente modificada, por la **información que recibe el sensor al tener contacto con cualquier superficie** (una mano, el suelo, etc.), como mantenerlo estático al percibirlo debajo. 

El uso que decidimos destinar a esta pieza es el de activar la máquina cuando identifica una presencia u objeto que se aproxima a cierta distancia del dispositivo.

## Componentes agregamos al circuito:

Los componentes que utilizamos para complementar los que ya tenemos, como el CHIP 555, parlante, condensador, resistencias y sintetizador 

 - **Cables tipo Caimán:** Son utilizados para hacer pasar corriente, sin necesidad de soldar. En este caso la contaremos a nuestros dedos, para que transmita el pulso del usuario y se escuche a través del parlante 
  
 - **CHIP 741:** Es un amplificador operacional, abreviado como op-amp, que  depende de un componente externo, y también tienen una pequeña dependencia a la temperatura.

   ## Proceso
![WhatsApp Image 2025-04-14 at 9 57 12 PM](https://github.com/user-attachments/assets/c299ac5b-6c52-439f-9335-00f9782de4f2)

## Esquemático - Primera parte 

![WhatsApp Image 2025-04-14 at 9 16 33 PM](https://github.com/user-attachments/assets/3dd10f62-5c41-4f81-95bd-aff92467df84)


![WhatsApp Image 2025-04-14 at 10 10 57 PM](https://github.com/user-attachments/assets/03d5d335-aec2-4837-8cb9-53150997acca)


https://github.com/user-attachments/assets/01c84a79-8003-42ce-b24c-b0f0ae260781


En esta ocasión probamos conectando un LDR al caimán, donde el sonido queda estático  


https://github.com/user-attachments/assets/6e3b1046-6087-439d-90f5-5783a0b47423

 Pero nos dimos cuenta de que faltaba un componente!!!

 ![WhatsApp Image 2025-04-15 at 12 00 28 AM](https://github.com/user-attachments/assets/979a5d7e-6f49-4dcd-9412-947ec612061e)

## Arreglo de errores
 ![WhatsApp Image 2025-04-15 at 12 06 05 AM](https://github.com/user-attachments/assets/041c3b2a-5799-4a44-9650-d4b17ef6e887)

 

https://github.com/user-attachments/assets/547e6b82-f461-43aa-b481-85769ec32518

## Experimentación 

Cambiamos el **LDR** que estaba en los cables amarillos, por un **pedazo de membrillo**, y funciona!!!

![WhatsApp Image 2025-04-15 at 12 16 26 AM](https://github.com/user-attachments/assets/f76a36e3-8174-494a-9bb7-d52c60df6218) 

https://github.com/user-attachments/assets/fafc23d4-49af-4e43-bb54-dee9a7d308ee

## Primera parte del esquema corregido

![WhatsApp Image 2025-04-15 at 3 10 30 AM](https://github.com/user-attachments/assets/47625dfd-8b80-44e5-ad6f-5b12937dec05)

## Bill of materials esquema 1
 

| Componente       | Qty | Nombre(s) | Valor/tipo |
|-----------------------|---------|------------|----------------|
| Chip 555              | 1       | U1         |                |
| Resistencia           | 2       | R1, R2     | Variable, 1k   |
| Condensadores         | 3       | C1,C2,C3   | 100n, 100u     |
| Parlante              | 1       |  LS1       |      2w        |

## Esquema completo

![WhatsApp Image 2025-04-15 at 3 31 32 AM (1)](https://github.com/user-attachments/assets/132ddb01-a23e-4f2c-a78a-8fe81fba02f0)


## Bill of material final

| Componente       | Qty | Nombre(s) | Valor/tipo |
|-----------------------|---------|------------|----------------|
| Chip 555                 | 2       | U1, U2         |                |
| Resistencia              | 4       | R1, R2, R3, R4        | Variable, 1k, 10k, 1k      |
| Condensadores      | 6       | C1, C2, C3, C4, C5, C6         | 100n, 100n, 1uF, 470n, 470n, 10uF        |
| Parlante                  | 1       |  LS1         |      2w          |
| Potenciómetro                  | 1       |  P1         |      B500K          |
| Led                  | 1       |  L1         |      3,3w          |
| Interruptor                  | 1       |  IN1         |               |









   

