# sesion-07a

## taller martes 21 de abril

### primera parte, desde las 8:30 a las 9:00 aprox

Llegué temprano este día, creo que le hace bien a uno mismo andar bien con la hora y no andar apurado y corriendo para todos lados, influye muchísimo en el ánimo o al menos a mi personalmente si.

### algunas cosas dichas al principio

- aaron nombró a un amigo suyo que era guitarrista en una banda que le gustaba, se llama roy macdonald y es un capo
- rafael lozano-hemmer es un artista que trabaja en un contexto de exhibiciones con obras muy intensas, roy trabaja como programador para lozano hemmer
- openframeworks ---> arturo castro manejó la página mucho tiempo pero después de que él la dejó la página se vino abajo, agregar que hay muchas instalaciones de museo que estan hechas con openframeworks
- zach lieberman y future sketches

### de aquí para abajo ya eran las 9 así que comenzamos a entrar en materia

- componente ---> ¿qué es un componente?
- cada componente tiene 3 características
- símbolo, valor, rating, footprint
- para hacer la placa debemos tener en cuenta los componentes
- la primera etapa se llama esquema, esto incluye, qué componentes hay, que símbolos tienen, como se conectan, que valor tienen, esta parte aún no se mete a trabajar en la fisicalidad de la placa
- después de esto, hay una herramienta para observar cuál es la base, se puede ver la huella pero no se puede ver qué hizo esa huella
- luego, en 3d puedo ver los componentes sobre la huella
- los pasos a seguir serían: 1. esquemático, 2. dibujo sch, 3. asignar huellas, 4. ruteo

### ¿cómo comenzar a trabajar en kicad?

- comenzamos a trabajar con un nuevo proyecto
- de nombre le pusimos mi primer kicad, debemos crear nueva carpeta para proyecto
- a partir de esto se crearon 2 archivos los cuales son miprimerkicad._pcb y miprimerkicad._sch, de los cuales debo abrir el segundo
- para trabajar de forma más cómoda, me voy a establecer configuración y apreto la pestaña que dice preferencias, aqui puedo configurar como quiero manejar el software, si quiero más velocidad en el mouse, utilizar de forma distinta a la convencional el programa, etc. En este caso lo configuramos para que fuera más cómodo el hacer zoom, desplazar de izquierda a derecha y de arriba a abajo.
- después de esto, seguimos trabajando, en la barra que hay a la derecha de la pantalla, hay una serie de herramientas que utilizaremos, en este caso, la primera que usamos fue la de añadir símbolo que es un cuadrado con una flechita dentro. Al apretar esta herramienta se abre una pestaña la cuál tiene todos los nombres de los símbolos que tenemos en el programa, tales como resistencias, leds, chips, condensadores, etc.
- la primera que usamos es una resistencia, la cual estaba denominada como "R_US", cuando creo la resistencia, la coloco y clickeo rodeándola, apreto la tecla v. Hacer esto despliega un menú el cuál me permite cambiar el valor de la resistencia que utilicé, donde dice value borro el valor y pongo el nuevo valor, en este caso 1K
- ahora agrego un NE555P
- con ctrl+d puedo ir duplicando los valores
- si rodeo y apreto ctrlc + ctrlv puedo copiar resistencias, funciona igual que illustrator
- D--> 1n4148, es el nombre que le pusimos al primer diodo
- w---> significa wire, es una herramienta para poner cables en nuestro esquemático
- al acercar un cable a otro o querer conectar 2 elementos, sale un signo + en verde, para saber cuando están conectados la pelotita que aparece antes de conectarlo, al conectarlo, desaparecerá
- un círculo significa que el componente está listo/libre para ser conectado
- con la tecla g de grab puedo agarrar y arrastrar el cable
- puedo ir clickeando el cable mientras lo muevo, de esta forma voy marcando segmentos y ángulos, algo asi como checkpoints
- si apreto la letra E sobre el componente, puedo ver información mucho más completa del componente
- si hago click en el componente y después X, se refleja en el eje X, lo mismo pasa con el eje Y
- con la herramienta texto (T) puedo escribir, me recuerda a indesign, es bueno sentirse familiarizado con los comandos jeje
- hay una pestaña de errores y avisos , los errores son rojos y los avisos son amarillos, según aaron los avisos son más buena onda y te dejan piola, pero los errores no
- **ahora viene una parte importante**
- el proceso de agregar huellas, cuando uso kicad con spice, hay componentes que son únicos de spice
- para agregar huellas, se abre la biblioteca de huellas la cuál despliega 3 rectángulos con información
- a la izquierda, está la biblioteca con todas las huellas, al centro las mías y mis componentes y a la derecha las recomendaciones
- también podemos aplicar filtros de huella apretando un ícono cuadrado arriba a la izquierda, podemos buscar por # número de pata? no entendí bien aquí
- el viernes enseñarán formas de asignar huellas de manera más sencilla, la verdad en este punto de la clase me perdí mucho, mi concentración duró hasta el break

### algunas cosas que también anoté pero no es un paso a paso

- el concepto de package, el encapsulado, el encapsulado alude a la forma del componente
- a la izq tenemos los componentes THT y SMD, averiguar cuál era la diferencia
- googlear en mousser ---> en una parte misa googleó un potenciómetro en mousser para encontrar el componente específico que estaba buscando
- CSV es un formato que permite hacer tablas separadas por comas
- ícono del BOM está arriba a la derecha
- después de hacer todo lo de huellas, se van a cambiar la edición de placas
- actualizar placa del esquema
- a la derecha hay capas, en kicad ocupamos 7 capas
- aquí se habló de los conceptos f Cu y b Cu, creo que se referían a front y a back
- todos los items tienen un lado para front y otro lado para back
- en esta parte estaban desarrollando el esquemático pero en otra especie de tablero, era de colores y es lo que utilizamos para luego mandar a imprimir, a estas alturas ya no entendía mucho, fue mucha información
- lo que vi después es que al terminar de poner los componentes del chip, se puede hacer una visualización en 3d de cómo va quedando nuestra PCB, se veía lindo
- otra cosa que anoté "primero selecciono capa edge cuts para determinar el tamaño de mi placa"
- otra cosa parte 2 "si clickeo componente, salen lineas blancas que me indican dónde va el componente o dónde quedaría mejor en la pcb
- nombraron a KELLY HEATON, 16n faderbank
- misaa dijo que su pelicula favorita era holly motors, creo que la veré para ver que onda
- al final de la clase vimos algunos ejemplos de pcbs que eran desarrolladas de forma más artística, habían cosas muy interesantes y bellas

### encargo 14

**desarrollar esquemático en kicad de atari punk console modificado realizado en proyecto 1**

adjunto esquemático desarrollado en kicad de la modificación realizada al atari punk console en el proyecto 1, que fue realizado en colaboración de francisco stephens, jose morales y braulio figueroa

![esquematicomodificado](https://github.com/user-attachments/assets/dd02dd16-74ef-4803-86c8-20e7aa23e26b)



