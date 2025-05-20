# sesion-10b
## Módulo de la mañana



## Módulo después del break



## encargo-22: documentación textual del proceso de ensamblado de udpudu / encargo-23: documentación visual del proceso de ensamblado de udpudu
<ins> Paso 1: </ins> Vamos a agarrar y ordenar nuestros componentes, según lo que indica en el BOM, asegurándonos de que sean de los valores adecuados.
![Foto con todos los componentes ordenados](./sesion10b/archivos10b-encargo22&23-(1))


<ins> Paso 2: </ins> Como primer componente a soldar, tomamos nuestro DIP Socket de 8 patas, que será colocado al centro, donde está la serigrafía de U1. Este componente no tiene polaridad, así que no causa problema en qué dirección sea fijado, mientras que las 8 patas sean insertadas en los agujeros correspondientes de la PCB.

Como era el primer componente que soldamos en esta PCB, la hicimos a mano alzada, sin soportes que sostuvieron ni el componente ni la PCB para que estuviese estable, pero en los componentes siguientes identificamos el problema y lo abordamos con nuestros elementos de la clase.

MUY IMPORTANTE
Debido a que después el chip que irá dentro de este socket es un chip 555, es muy importante que ninguna de las soldaduras de las patas del socket vaya a tocarse entre sí, debido a que esto causará un cortocircuito, que haría que no funcione el chip, pudiendo llegar a quemarlo, y de esta manera dejase de funcionar el circuito.

Esto también debería estar presente para todas las soldaduras de aquí en adelante para no causar accidentes, ni tener que comprar nuevos componentes para reemplazar los no funcionales.

<ins> Paso 3: </ins> Ahora vamos a pasar a soldar las resistencias, donde vamos a ocupar masking tape por la parte superior de la placa, para que quede fija en la posición más cerca posible de la superficie de la placa y después proceder a soldar. Estas 3 resistencias de 1k irían en las posiciones de R2, R3 y R4.

Ya que las resistencias no tienen polaridad, no hay que preocuparse con la dirección en la que son soldadas.

En este punto agarramos un cuaderno y fijamos el borde de la PCB a un lado de este cuaderno, para que no se “escape” mientras cada componente está siendo soldado.


<ins> Paso 4: </ins> Nuestro diodo será el primer componente de nuestro circuito que tiene polaridad, así que nos aseguramos de que la parte blanca/plateada donde está la franja siga el sentido que está establecido en la serigrafía, que sería con el lado negativo hacia la derecha en la huella D1 del PCB.

<ins> Paso 5: </ins> Ahora soldamos el condensador cerámico 104 en la serigrafía C3, justo a la derecha del DIP Socket y justo debajo del Pudú.

Este componente no tiene polaridad, así que se solda sin necesidad de colocarlo con una dirección específica.


<ins> Paso 6: </ins> Soldamos el condensador electrolítico de 1 µF en la posición de C4, asegurándonos de que su polaridad sea correcta, que el lado negativo según lo indicado por la serigrafía presente en la PCB; en este caso, el lado negativo estaría en la orientación hacia abajo.


<ins> Paso 7: </ins> Soldamos nuestro condensador electrolítico de 47 µF de la misma manera que el anterior condensador electrolítico en la serigrafía C5, donde el negativo quedaría al lado derecho en este caso.


<ins> Paso 8: </ins> Agarramos nuestros LEDs, donde nos aseguraremos que la pata más corta (negativa) quede en el agujero inferior que tiene forma cuadrada, que corresponde a D2 y D3. 


<ins> Paso 9: </ins> Para el componente que corresponde a la serigrafía J2, ya que no teníamos el terminal block para soldar y de esta manera alimentar el circuito, le soldamos un conector broche para la batería, donde el lado negativo (negro) va al agujero cuadrado correspondiente a GROUND, mientras que el cable rojo iría al agujero circular donde está +9V y corresponde al VCC. 


<ins> Paso 10: </ins> Usamos una pata de una resistencia para poder simular el interruptor que haría que este estuviera prendido o apagado el circuito entre la pata central y derecha de la serigrafía con un botón encendido, que está justo entremedio del conector broche y el led D3.


<ins> Paso 11: </ins> como también faltó el otro terminal block para la serigrafía LS1 de la parte derecha del circuito, conectaremos de forma manual el parlante, siguiendo lo que hemos aprendido de la simbología del agujero cuadrado y circular para distinguir negativo de positivo.
