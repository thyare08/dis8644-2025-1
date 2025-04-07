# sesion-04a

# Apuntes Clases

# Atari Punk Console (APC)

La Atari Punk Console es un sencillo generador de sonidos electrónicos DIY (hazlo tú mismo) que produce tonos tipo arcade, similar a los de los videojuegos de los años 80. Fue diseñada por Forrest M. Mims III y se basa en un circuito con temporizadores NE555 o 556.

![APC](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT7WPWkH25Q5zxH3y6ZZlH6ezT51beVe26jGQ&s)

# ¿Qué hace?

- Genera sonidos tipo "retro" o "8 bits".
- Usa potenciómetros para controlar el tono y la duración de los pulsos.
- Suena como un videojuego antiguo (de ahí el nombre "Atari").

# ¿Qué componentes usa?

- 1 chip 555 o 556 (dos temporizadores en uno)
- Resistencias y condensadores
-2 potenciómetros (para variar el sonido)

Bocina o salida de audio

# ¿Por qué es popular?

-  Fácil de construir (ideal para principiantes en electrónica)
- Barata
- Muy divertida para experimentar con sonidos

![APCWORK](https://upload.wikimedia.org/wikipedia/commons/thumb/f/fa/APC_with_2_555_%28pin_out%29_and_bridge_added.png/400px-APC_with_2_555_%28pin_out%29_and_bridge_added.png)

# Explicación técnica simplificada

- El primer temporizador 555 genera una señal continua (oscilador astable).
- Esa señal se manda al segundo 555, que la convierte en pulsos más cortos o largos (oscilador monoestable).
- El resultado es un sonido que cambia según cómo ajustes los potenciómetros.
- Esa señal se puede enviar a un parlante o amplificador para que se escuche.
- 




