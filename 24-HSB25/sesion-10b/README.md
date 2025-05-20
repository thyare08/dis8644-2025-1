# sesion-10b

EN ESTA CLASE no pude asistir debido a que me encontraba fuera de Santiago por problemas de fuerza mayor, pero de igual manera quize hablar con mis compañeros para saber que paso en la clase.

Para comenzar, cada uno de nosotros armó un circuito PWM con un LED de diferente color: rojo, verde o azul, respectivamente.

Notamos que, para el LED verde, una resistencia de 1kΩ podría ser excesiva, por lo que decidimos reemplazarla por una de 220Ω para mejorar su brillo. Esto es relevante porque el ojo humano es especialmente sensible a la luz verde, por lo que percibimos este color con mayor intensidad.

Los LEDs RGB combinan tres emisores de luz de diferentes colores (rojo, verde y azul) en un solo componente. Cada uno de estos LEDs puede variar su intensidad de brillo, lo que permite generar una amplia gama de colores mediante la mezcla de luces. Como están ubicados muy cerca entre sí, la luz que emiten se fusiona visualmente.

Estos LEDs RGB suelen presentarse en dos configuraciones: de cátodo común o de ánodo común. Con este montaje, replicamos el principio de funcionamiento de una rosa cromática, ya que al combinar los tres LEDs, pudimos observar cómo sus luces se mezclaban para formar nuevos colores.

# FALSTAD

Falstad es el nombre común con el que se conoce al Simulador de Circuitos Electrónicos Falstad, una herramienta en línea gratuita muy utilizada para visualizar y simular el comportamiento de circuitos eléctricos y electrónicos en tiempo real. Fue desarrollado por Paul Falstad, un programador y físico aficionado, y se ha convertido en una herramienta muy popular en entornos educativos y entre personas que aprenden electrónica.

En esta sesión trabajamos con el LM324N, un chip clásico muy utilizado en electrónica. Este circuito integrado posee cuatro amplificadores operacionales (OP-AMPs) en su interior y cuenta con 14 patas (pines).

- ¿Qué es un OP-AMP?
Un amplificador operacional (abreviado como OP-AMP) puede pensarse como una "caja negra" que realiza operaciones matemáticas basadas en la comparación de voltajes entre sus entradas. Es un componente activo (requiere alimentación externa) y versátil, usado en múltiples aplicaciones: amplificadores, comparadores, filtros, sumadores, etc.

- Alimentación de los OP-AMP
Una dificultad que presentan los OP-AMPs es su alimentación con dos polaridades: algunos circuitos requieren ±12V (positivo y negativo), ya que no todos los diseños funcionan correctamente con una sola fuente de 0V y 12V. Este aspecto complica su implementación si no se tiene una fuente simétrica.

- El LM324N vs. el 741
LM324N: Contiene cuatro OP-AMPs en un solo encapsulado.

741: Otro chip clásico, pero solo con un OP-AMP.

- Pinout y documentación
Cuando se busca información de un chip, como el LM324N, se recomienda escribir “pinout” junto al nombre en buscadores. Así se accede rápidamente al esquema de conexiones sin tener que buscar el significado de cada pata individualmente.

# Construcción del UDPUDU

![UDPUDU1](https://media.discordapp.net/attachments/1318882679659171892/1372986482549198918/IMG_7502.jpg?ex=682d620e&is=682c108e&hm=a647956703994809dbbd3ef9a9497edbcc142c056328215d014d595cbd6b7c37&=&format=webp&width=875&height=544)
