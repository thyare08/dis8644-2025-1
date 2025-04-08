# sesion-05a
### AC
Oscilación ondulada. Energía domiciliaria
### DC
Oscilación cuadrada. Recta.
Baterías

3V batería

Pila AA: 1.5V

### Circuito _Atari Punk Console_


Condensador, el sonido es cambio.
Cono de parlante se va hacia afuera, presión atmosférica. El sonido mecánicamente comprime localmente la materia, aumento temporal en la presión atmosférica, después esa oscilación se propaga y acaba por ser ruido que nosotros podemos percibir.

Según conectamos el positivo en caimán a un parlante el sonido puja hacia afuera o hacia adentro, puede haber un cambio. Si se conecta directo se gasta la batería y se puede pujar demasiado y puede estropearse la bocina.
Capacitores y bobinas C y L, son resistencias pero no lineales, dependen de la frecuencia de la corriente, importa la oscilación de la onda.

Corriente continua tiene frecuencia 0. Un capacitor tiene un voltaje, solo deja pasar las oscilaciones, deja de ser la parte constante. El capacitor elimina DC. Elimina las variaciones porque eso es lo que importa en el sonido. Resistor es plano, atenúa siempre igual. El capacitor le importa la frecuencia de la onda, depende de la frecuencia y el voltaje.

Lo que le interesa al sonido para escuchar es la diferencia. El parlante a 9V está al límite pero si lo filtramos es seguro. Capacitor sirve para hacer filtros **ECUALIZADOR** un C. Logra hacer barreras al sonido.

### _Modding_ para el _Atari Punk Console_

Resistencia > protección. Condensador > protección. 1K es una resistencia mínima que puede tener. Dentro del 555 existe un transistor que es susceptible a quemarse.

Capacitor de desacoplamiento. De desacople _DC COUPLING_

¿Cómo se sumaban las resistencias en serie y en paralelo?
* R1 + R2 -> equivalente(en serie)
* Req= R1*R2/R1+R2 = R equivalente (en paralelo)

Los condensadores son inversos a la resistencia en el cálculo de suma
Con condensadores
* Suma de condensadores en paralelo > se suman directamente Ceq= C1+C2
* Suma de condensadores en serie Ceq= C1*C2/C1+C2

C1 modifica la altura, grave y agudo _pitch_ del sonido, frecuencia física perceptual.

Si antes que C1 incorporo un interruptor con un condensador, la corriente corre en paralelo y los condensadores se suman, se aumenta la tonalidad y puede bajar la altura. Pueden haber muchos condensadores, y muchas al mismo tiempo, muchas en serie, por ejemplo 5 frecuencias distintas. Estados, escalas y riqueza musical.

* Interruptor en resistencia, habilitador o deshabilitador del circuito.
* Patas de protección, se corta el paso de voltaje a través de la resistencia de protección pata 7. Pata 4 también puede haber un interruptor.
* Cortar la alimentación también es un lugar de alimentación.

Carril SPDT. Switch que decide si las ranuras están conectadas, no es un ON/OFF sino que decide variabilidad.

La resistencia experimental se puede "romper" a dos posibles interruptores y dos resistencias experimentales distintas.
Experimentación manual.

### Siguiente encargo. Rehacer el _Atari Punk Console_ y experimentar, registrar. Para el viernes encontraremos los materiales que nos hace falta.
Crear un esquemático APC propio.

Revisar _555 Timer Circuits_.
