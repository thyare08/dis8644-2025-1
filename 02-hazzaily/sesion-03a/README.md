# sesion-03a

25 de Marzo de 2025.

- **Tipos de resistencias en un circuito:**

Foto de mi croquera.

![Foto_tipos_de_resistencias](https://github.com/user-attachments/assets/f9dc4088-c273-4cd7-91df-364c29fc7110)

En cuanto a la resistencia en paralelo, eso significa que: Si R1 = R2, entonces Rer = R1/2.

Dentro de los resistores podemos encontrar distintas nomenclaturas que nos permiten identificar las distintas cantidades de Ohm que posee cada uno. Por ejemplo:

Foto de tabla de Ohmios.

![Tabla_de_Ohmios](https://github.com/user-attachments/assets/27f602f3-79c2-478d-9772-39110b611026)

**CHIP 555:**

El chip 555 es un circuito integrado que se utiliza en la generación de temporizadores, pulsos y oscilaciones. Se puede utilizar para proporcionar retardos de tiempo, como un oscilador, y como un circuito integrado flip flop (es un circuito que tiene una entrada de habilitación que controla si el circuito está bloqueaddo o activo). Fue diseñado por Hnas Camenzind en 1971 y se encuentra presente en múltiples dispositivos electrónicos, juguetes y electrdomésticos

Este chip puede funcionar de 3 maneras distintas:

 1. **Biestable:** Es un circuito integrado que alterna entre dos estados estables (activado y desactivado).

 2. **Monoestable:** También se conoce como el mode de una sola vez, esto porque el output es un pulso simple, corto y positivogenerado por un input simple, cuya duración se determina por los valores de resistencia y capacitancia del circuito.

 3. **Astable:** En este modo el chip funciona como oscilador que genera una onda cuadrada ajustable al modificar los valores de resistencia y condensador conectado al chip.

Basandonos en el último, que es el modo Astable, podemos desarrollar un circuito como este:

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
