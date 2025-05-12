# sesion-03a

25 de Marzo de 2025.

- **Tipos de resistencias en un circuito:**

Foto de mi croquera.

![Foto_tipos_de_resistencias](https://github.com/user-attachments/assets/f9dc4088-c273-4cd7-91df-364c29fc7110)

En cuanto a la resistencia en paralelo, eso significa que: si R1 = R2, entonces Req = R1/2.

Dentro de los resistores podemos encontrar distintas nomenclaturas que nos permiten identificar las distintas cantidades de Ohm que posee cada uno. Por ejemplo:

Foto de tabla de Ohms.

![Tabla_de_Ohmios](https://github.com/user-attachments/assets/27f602f3-79c2-478d-9772-39110b611026)

- **CHIP 555:**

Este chip puede funcionar de 3 maneras distintas:

 1. Astable.

 2. Monoestable.

 3. Biestable.

Basándonos en el primero, que es el modo Astable, podemos desarrollar un circuito como este:

![esquematico-astable](https://github.com/user-attachments/assets/69685efc-7cfc-48f7-87e1-6f9daf064c8f)

GIF del circuito realizado con el chip 555.

![chip_555](https://github.com/user-attachments/assets/7311f830-d76b-42da-a32b-8e681d865b49)

- El gif lo hice tomando fotos de los momentos claves del LED interactuando con el circuito (encendido/apagado), luego seleccioné una opción que tiene mi teléfono para crear gifs y lo subí a mi nube, lo descargué en mi computador y lo arrastré a GitHub.

Para realizar este circuito debemos tener en cuenta la tabla BOM:

![Tabla_BOM_chip_555_01](https://github.com/user-attachments/assets/c3a0c72d-6409-4f10-b477-f4a86b3d5bf0)

Al realizar distintas modificaciones en la protoboard podemos notar distintos cambios, como por ejemplo:

 1. **Reemplazar R2 por un potenciómetro:** Al utilizar el ptenciómetro podemos ajustar la velocidad de la oscilación de la luz, mientras más a la izquierda parpadea más lento, mientras que más a la derecha parpadea más rápido.

 2. **Reemplazar el condensador de 10F por uno de 1F:** Al igual que en el caso anterior, podemos notar un aumento o disminución de la velocidad de oscilación cada vez que giramos la perilla, pero este camnbio es mucho más notorio debido a que el cambio es mucho más rápido que en el ejemplo anterior.

**Encargo 06** Escuchar un álbum de **Einstürzende Neubauten**, incluyendo investigación de los instrumentos que usan.

Foto de mi croquera.

**Encargo 07:** Apuntes del chip 555, incluyendo fotos, diagramas de los usos de este chip.

Foto de mi croquera.

![Croquera_chip_555](https://github.com/user-attachments/assets/faf99b57-b08c-4a25-8506-d0ad4c28080a)

- Historia: El chip 555 es un circuito integrado que se utiliza en la generación de temporizadores, pulsos y oscilaciones. Se puede utilizar para proporcionar retardos de tiempo, como un oscilador, y como un circuito integrado flip flop (es un circuito que tiene una entrada de habilitación que controla si el circuito está bloqueaddo o activo). Fue diseñado por Hnas Camenzind en 1971 y se encuentra presente en múltiples dispositivos electrónicos, juguetes y electrdomésticos.

Este chip tiene diversas configuraciones que sirven para distintas cosas, estas son:

 1. **Astable:** En este modo el chip funciona como oscilador que genera una onda cuadrada ajustable al modificar los valores de resistencia y condensador conectado al chip.

![Astable](https://github.com/user-attachments/assets/4919be99-c050-41fd-9432-9a1bd4b29d2e)

 2. **Monoestable:** También se conoce como el mode de una sola vez, esto porque el output es un pulso simple, corto y positivogenerado por un input simple, cuya duración se determina por los valores de resistencia y capacitancia del circuito.

![Monoestable](https://github.com/user-attachments/assets/68948f76-8c03-4a7b-bfc1-1c10b6356843)

 3. **Biestable:** Es un circuito integrado que alterna entre dos estados estables (activado y desactivado).

![Biestable](https://github.com/user-attachments/assets/7fbb1048-916c-4674-b920-5d47d794e9dd)

- Patillas o Pin: Los 555 poseen 8 patillas que tienen una función específica cada una como se puede observar en el siguiente ejemplo.

![Tips](https://github.com/user-attachments/assets/3f294aa5-4b1d-452c-8bbd-81ea7a64f6f0)

- **Patilla 1 GND:** Es la patilla de la conexión a Tierra y a ella siempre se conecta la masa o el negativo de la pila (0V = cero voltios).
- **Patilla 2 Disparo (TRIGGER):** esta patilla hará que se active o no la señal de salida de la patilla 3.
- **Patilla 3 Salida (OUT):** En este pin se puede observar el resultado de la configuración del temporizador eléctrico ya sea como monoestable, astable u otra opción.
- **Patilla 4 Reinicio (RESET):** Para un nivel de voltaje por debajo de 0.7 V, tiene la función de poner el pin de salida a nivel bajo. Para evitar el reinicio se deberá conectar este pin a alimentación.
- **Patilla 5 Control de voltaje (CTRL o CONT):** Al utilizar el circuito integrado LM555 como controlador de voltaje, el voltaje en esta terminal puede variar teóricamente desde Vcc hasta aproximadamente 0 V, en la práctica la variación es de Vcc – 1.7 V hasta casi 2 V menos.
- **Patilla 6 Umbral (THR o THRES):** Corresponde a la entrada de un comparador interno de umbral el cual se emplea para poner la señal de salida a un nivel bajo.
- **Patilla 7 Descarga (DIS o DISCH):** Permite descargar el condensador externo al circuito integrado 555 para su funcionamiento.
- **Patilla 8 Voltaje de alimentación (Vcc o Vdd):** Terminal positiva de la alimentación, normalmente son valores de 4.5 V hasta 16 V.
