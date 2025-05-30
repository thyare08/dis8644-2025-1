# sesion-12a
## Módulo de la mañana

Readymag, una página para hacer portafolios

Las luces amarillas de un semáforo duran aproximadamente 4 segundos, al menos en Santiago de Chile.

https://www.digikey.com.mx/es/resources/conversion-calculators/conversion-calculator-555-timer

Digamos que el verde dura 60 segundos, el amarillo 4 segundos y el rojo 60 segundos.

Como son múltiplos de 4, quedarían en 15 pulsos para el rojo y verde, mientras que el amarillo tendría un pulso, que duraría 4 segundos.

Estamos viendo cómo podríamos armar un semáforo.

Francisco Stephens propuso que a través de un transistor podría llevar una señal de sí mismo hacia el comienzo del circuito con el 555. 

Ojo con el transistor, está lleno de variables.

Ya que el 4017 tiene 10 patas que dan outputs yo primero propuse el decir interconectar 3 chips 4017 entre sí y poder conseguir los 30 outputs que necesitaríamos a través del pin 12. 

Después se me ocurrió el separar los 4 primeros pines de output del 4017 para la primera luz verde; después el pin 5 sería para la luz amarilla, que podría funcionar a partir de un 555 monostable, donde se conectaría a clock enable/inhibit para que pudiese continuar y pasar a los pines 6, 7, 8, 9 de output.

Estamos revisando el datasheet del 4017.

Necesita un mínimo de 3V y un máximo de 18V.

El clock inhibit extiende la señal recibida por el pin que está actuando en ese instante.

Al ver el diagrama de tiempo/timing diagram:

La pata de reset toma prioridad por encima del clock inhibit, si es que recibe una señal exterior.

El diagrama de lógica conversacional es donde están los componentes interconectados.

Cascading es la interconexión que necesitaría una compuerta AND, que comprueba si una señal es equivalente a otra, y que dejara pasar la continuación del circuito.

Ahora pasamos a revisar las notas.

## Módulo después del break

Vamos a conectar 3 módulos; vamos a ir parte por parte probando y recibiendo señales de aviso a partir de un led que pondremos en cada circuito.

1ro Vamos a hacer un detector de sombra, algo que me avise si es que hay una sombra, una máquina que me promueva elogios de la sombra.

2do. Un temporizador para que tenga una duración la detección de la sombra.

3ro. Secuenciador con el 4017
