# sesion-10b
## Módulo de la mañana
Circuit Bend Speak & Spell

Hack of the Month Club -- Proyecto #3: Jumping Speakers

Hoy vamos a hacer entrega formal de udpudu.

Vamos a aprender a revisar las cosas 2 veces antes de soldarlas.

Vamos a documentar muy fuertemente.

En docente/7b está udpudu oficial, el que fue mandado a hacer en China.

Me entregaron mi PCB udpudu. 

csv comma separated values

Hicimos nuestra BOM, tambien un pdf de la capa frontal.

Vamos a hacer una guía de ensamblaje de nuestro udpudu.

## Módulo después del break

Hicimos la guía de ensamblaje de nuestro udpudu, como se puede observar en los encargos 22 y 23.

## encargo-22: documentación textual del proceso de ensamblado de udpudu / encargo-23: documentación visual del proceso de ensamblado de udpudu
<ins> Paso 1: </ins> Vamos a agarrar y ordenar nuestros componentes, según lo que indica en el BOM, asegurándonos de que sean de los valores adecuados.

![Foto con todos los componentes ordenados](./archivos/10b-encargo-22&23-(1).jpg)

![Foto con todos los componentes ordenados y una PCB que tiene los componentes puestos en su posicion](./archivos/10b-encargo-22&23-(2).jpg)

![Foto mas de cerca con los componentes en sus posiciones correspondientes](./archivos/10b-encargo-22&23-(3).jpg)

<ins> Paso 2: </ins> Como primer componente a soldar, tomamos nuestro DIP Socket de 8 patas, que será colocado al centro, donde está la serigrafía de U1. Este componente no tiene polaridad, así que no causa problema en qué dirección sea fijado, mientras que las 8 patas sean insertadas en los agujeros correspondientes de la PCB.

![Foto de la PCB con el DIP Socket puesto](./archivos/10b-encargo-22&23-(4).jpg)

Como era el primer componente que soldamos en esta PCB, la hicimos a mano alzada, sin soportes que sostuvieron ni el componente ni la PCB para que estuviese estable, pero en los componentes siguientes identificamos el problema y lo abordamos con nuestros elementos de la clase.

![Foto de soldado sin soportes para la PCB](./archivos/10b-encargo-22&23-(5).jpg)

MUY IMPORTANTE
Debido a que después el chip que irá dentro de este socket es un chip 555, es muy importante que ninguna de las soldaduras de las patas del socket vaya a tocarse entre sí, debido a que esto causará un cortocircuito, que haría que no funcione el chip, pudiendo llegar a quemarlo, y de esta manera dejase de funcionar el circuito.

Esto también debería estar presente para todas las soldaduras de aquí en adelante para no causar accidentes, ni tener que comprar nuevos componentes para reemplazar los no funcionales.

<ins> Paso 3: </ins> Ahora vamos a pasar a soldar las resistencias, donde vamos a ocupar masking tape por la parte superior de la placa, para que quede fija en la posición más cerca posible de la superficie de la placa y después proceder a soldar. Estas 3 resistencias de 1k irían en las posiciones de R2, R3 y R4.

Ya que las resistencias no tienen polaridad, no hay que preocuparse con la dirección en la que son soldadas.

![Foto de las resistencias en sus posiciones](./archivos/10b-encargo-22&23-(7).jpg)

![Foto de las resistencias en sus posiciones y fijadas con masking](./archivos/10b-encargo-22&23-(8).jpg)

En este punto agarramos un cuaderno y fijamos el borde de la PCB a un lado de este cuaderno, para que no se “escape” mientras cada componente está siendo soldado.

![Foto de PCB con soporte de masking tape](./archivos/10b-encargo-22&23-(6).jpg)

<ins> Paso 4: </ins> Nuestro diodo será el primer componente de nuestro circuito que tiene polaridad, así que nos aseguramos de que la parte blanca/plateada donde está la franja siga el sentido que está establecido en la serigrafía, que sería con el lado negativo hacia la derecha en la huella D1 del PCB.

![Foto de PCB con el diodo con polaridad correcta montada](./archivos/10b-encargo-22&23-(9).jpg)

<ins> Paso 5: </ins> Ahora soldamos el condensador cerámico 104 en la serigrafía C3, justo a la derecha del DIP Socket y justo debajo del Pudú.

Este componente no tiene polaridad, así que se solda sin necesidad de colocarlo con una dirección específica.

![Foto de PCB en angulo donde esta el condensador ceramico](./archivos/10b-encargo-22&23-(10).jpg)

<ins> Paso 6: </ins> Soldamos el condensador electrolítico de 1 µF en la posición de C4, asegurándonos de que su polaridad sea correcta, que el lado negativo según lo indicado por la serigrafía presente en la PCB; en este caso, el lado negativo estaría en la orientación hacia abajo.

![Foto de PCB con el condensador electrolitico C4 en su polaridad correcta](./archivos/10b-encargo-22&23-(11).jpg)

![Foto de PCB con el condensador electrolitico C4 en su polaridad correcta en angulo](./archivos/10b-encargo-22&23-(12).jpg)

<ins> Paso 7: </ins> Soldamos nuestro condensador electrolítico de 47 µF de la misma manera que el anterior condensador electrolítico en la serigrafía C5, donde el negativo quedaría al lado derecho en este caso.

<ins> Paso 8: </ins> Agarramos nuestros LEDs, donde nos aseguraremos que la pata más corta (negativa) quede en el agujero inferior que tiene forma cuadrada, que corresponde a D2 y D3. 

![Foto de PCB con el condensador electrolitico C5 en su polaridad correcta y los LED en su posicion](./archivos/10b-encargo-22&23-(13).jpg)

<ins> Paso 9: </ins> Para el componente que corresponde a la serigrafía J2, ya que no teníamos el terminal block para soldar y de esta manera alimentar el circuito, le soldamos un conector broche para la batería, donde el lado negativo (negro) va al agujero cuadrado correspondiente a GROUND, mientras que el cable rojo iría al agujero circular donde está +9V y corresponde al VCC. 

![Foto de PCB con su conector broche soldado en J2](./archivos/10b-encargo-22&23-(14).jpg)

<ins> Paso 10: </ins> Usamos una pata de una resistencia para poder simular el interruptor que haría que este estuviera prendido o apagado el circuito entre la pata central y derecha de la serigrafía con un botón encendido, que está justo entremedio del conector broche y el led D3.

![Foto antes de colocar la pata de resistencia](./archivos/10b-encargo-22&23-(16).jpg)

![Foto de la resistencia que cortaremos u ocuparemos su pata como cable](./archivos/10b-encargo-22&23-(15).jpg)

<ins> Paso 11: </ins> como también faltó el otro terminal block para la serigrafía LS1 de la parte derecha del circuito, conectaremos de forma manual el parlante, siguiendo lo que hemos aprendido de la simbología del agujero cuadrado y circular para distinguir negativo de positivo.

![Foto del circuito casi terminado, usando caimanes para conectar el parlante](./archivos/10b-encargo-22&23-(17).jpg)

<ins> Paso 12: </ins>  Insertamos el chip 555 en el PIN Socket, de manera que su corte o circulo característico esté hacia arriba, de esta manera las conexiones de todas sus patas serán las correctas.

![Foto del como se coloca el 555](./archivos/10b-encargo-22&23-(18).jpg)

<ins> Paso 13: </ins>  Finalmente, para probar el circuito conectamos caimanes que nos permitieran conectar una resistencia variable, en este caso usamos un LDR.


