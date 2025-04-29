# sesion-03a

Clase 5: Martes 25 de Marzo del 2025.

- **Parte 1:** Apuntes en clases.
- **Parte 2:** Investigar historia de **"chip 555"**.
- **Parte 3:** Encargo 06.
- **Parte 4:** Encargo 07.

## Apuntes

Foto de mi bitácora

![IMG_8566](https://github.com/user-attachments/assets/44586b50-c0c0-4203-9e21-ce30c7b68b3e)

Foto de mi bitácora

![IMG_8567](https://github.com/user-attachments/assets/fcc0a78f-661e-4b09-a5eb-3e15e0056ea9)

**Parte 2** Investigar la historia del chip 555:

## Chip 555

![Chip555](https://github.com/user-attachments/assets/aa78c873-98b3-45bb-bdac-65a4320570ae)

- Fue diseñado por Hans R. Camenzind en 1971.

![Hans_R_Camenzind (creador de chip555)](https://github.com/user-attachments/assets/2b0ad239-cb89-49f2-aa53-a9292f318a43)

- **¿Para que sirve?**
  - Su principal función es la producción de pulsos de temporización con una gran precisión.
  - Puede generar pulsos de microsegundos hasta horas.
  - Funciona como un circuito flip-flop y tiene tres modos operativos: **monostable, biestable y astable**.

![02_555_monoestable-simple-1](https://github.com/user-attachments/assets/296e5dc7-9649-4469-a6b9-b145af49e825)

![04_555_biestable](https://github.com/user-attachments/assets/d38bf966-b2f7-4ce4-98c8-f2530ae9caf1)

![05_555_astable-1](https://github.com/user-attachments/assets/e4683aa2-957a-484e-97dd-4186eb433275)

- **¿Qué es?**
  - El temporizador toma su nombre del hecho de que el modelo original incluía tres resistencias de 5 kΩ cada una.
  - Es un componente esencial en la electrónica, es versátil y eficiente.
  - Es un circuito integrado (CI) que funciona como temporizador y oscilador.
  - Contiene 25 transistores, 15 resistores y 2 diodos.
- **Características**
  - **Tensión de alimentación:** Funciona entre 4.5V y 15V, lo que permite su uso en una amplia gama de aplicaciones.
  - **Corriente de salida:** Puede manejar hasta 200mA, suficiente para activar la mayoría de los dispositivos periféricos.
  - **Estabilidad de temperatura:** El temporizador 555 es altamente estable, con fluctuaciones mínimas en sus tiempos de operación, incluso ante cambios de temperatura.
  - **Versatilidad**: Debido a sus múltiples modos de operación, se puede utilizar en una variedad de aplicaciones.

## Aplicaciones

![chip 555](https://github.com/user-attachments/assets/f9ec60a6-ff7f-467d-b34f-04e71dfa56e2)

Los pines del 555 tienen las funciones siguientes:

- Pin 1: GND. Masa.
- Pin 2: Trigger. Si se produce un pulso a 1/3 de la tensión +V o menos, se genera el disparo.
- Pin 3: Output. Salida de onda cuadrada.
- Pin 4: Reset. En estado bajo (0V) se anula la tensión de salida. Para evitar falsos resets se conecta este pin a +V.
- Pin 5: Control Voltage. Puede hacer modular la salida del 555 aplicando tensión o señal en este pin. Cuando no se usa conviene conectarlo a masa a través de un condensador de 10 o 100nF.
- Pin 6: Threshold. Entrada de un comparador interno responsable del estado del flip flop.
  Pin 7: Discharge. Permite descargar el condensador asociado, pasando la salida de estado alto a bajo cuando la tensión de este pin alcanza 2/3 de +V.
- Pin 8: +V. Tensión de alimentación, según la hoja de características, entre 4,5V y 16V.

**Parte 3:** Encargo-06.

- escuchar disco de banda alemana **Einstürzende Neubauten** e investigar intrumentos utilizados en sus canciones.

Einstürzende Neubauten

- **¿Quienes son?**

Einstürzende Neubauten es una banda alemana de música experimental e industrial, formada en Berlín Occidental en 1980. Son conocidos por su uso innovador de instrumentos no convencionales, como herramientas de construcción y objetos metálicos, para crear paisajes sonoros únicos y a menudo estridentes.

![images](https://github.com/user-attachments/assets/5204ddfb-87fa-4e21-bbba-3db4f5e825aa)

Disco escuchado: **Halber Mensch**

![HalberMenschAlbumCover](https://github.com/user-attachments/assets/17e003aa-51d9-4cf2-90ca-30e02780bde4)

- Este álbum es considerado uno de los trabajos más influyentes y radicales de la banda, y es ampliamente reconocido como un clásico de la música industrial y experimental. Tiene sonidos intensos y ruidosos creados con objetos como tuberías, metales y madera. Voz que dice vocales gritados y emotivos del líder (Blixa Bargeld).

- Las letras de las canciones abordan temas como la alienación, la deshumanización y la crítica social, reflejando la atmósfera de tensión y cambio político en Alemania en la época.
- "Halber Mensch" es un álbum desafiante y provocador que sigue siendo influyente en la música experimental y underground hasta hoy en día.

**Parte 4:** Encargo 07.

- Ejercicio con chip 555 en clases.

Circuito esquematico a realizar

![esquematico-astable](https://github.com/user-attachments/assets/f962d256-14e8-4536-8015-732d4ed8edd1)

Es un circuito esquematico astable, esto quiere decir, que es un circuito electrónico que no tiene un estado estable, sino que alterna entre dos estados inestables. En cada estado permanece un tiempo determinado.

**Foto de mi bitácora:** _Bill of materials_

![IMG_8568](https://github.com/user-attachments/assets/0759de1b-60b6-48df-914a-fb18863f9100)

**Resultado del circuito**

![IMG_8552](https://github.com/user-attachments/assets/838e2a88-e791-4e15-9055-051dcdeee706)

**Video**

<https://github.com/user-attachments/assets/84a7cd49-4066-4ddd-b7a8-5679c94bc09d>

**Observación:** Cuando se activa un circuito con un chip 555, este produce pulsos de temporización o oscilaciones eléctricas, es decir, que el diodo LED enciende y se apaga en una misma frecuencia.

**Circuito esquematico con potenciometro**

![imagen-10](https://github.com/user-attachments/assets/14dd0bed-7bf6-47d1-8bab-12f1bc6e510b)

**Resultado del circuito**

![IMG_8553](https://github.com/user-attachments/assets/67a3acf5-c759-4d13-bc9c-56cf74bae49f)

**Video**

<https://github.com/user-attachments/assets/74888089-93e1-4065-8e4d-90378e56a652>

**Observación:** Lo que sucede cuando se le agrega un potenciómetro a un circuito con chip 555, es que puede variar la resistencia del circuito y, por lo tanto, la cantidad de corriente que fluye, es decir, uno puede controlar la velocidad de encendido y apago del LED de forma alternada.
