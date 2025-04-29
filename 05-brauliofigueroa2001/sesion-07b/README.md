# sesion-07b
### clase viernes 25 de abril
**no asistí a esta clase porque me sentí muy mal anímicamente en la mañana y no tuve ganas de ir**

de todas formas en base a la clase online subiré mis apuntes

### primera parte: asignar huellas
- misaa abrió kicad y por discord nos compartieron el 555 personalizado con las patitas ordenadas, que es más cómodo de utilizar porque lo hemos visto en clases y en la pcb
- para instalar este 555 debemos descargar el archivo compartido en discord y descomprimirlo, es un archivo zip. Luego dentro de KICAD debemos seleccionar la biblioteca que esta en los íconos de arriba, aquí dentro debemos abrir un ícono de una biblioteca
- debemos clickear el que dice libraries en las carpetas que descargamos y dentro de este existe un archivo kicad_sym el cuál es el 555 actualizado
- clickeamos y ponemos aceptar, el error que tuve y no me di cuenta fue que no veía el botón de aceptar en las bibliotecas porque la ventana estaba muy grande y en la clase online no se veía esa parte porque la tapaba la cámara.
- después de aceptar abrimos el panel de componentes y buscamos "555_ordenado", aparecerá una pestañita que dice 555 well ordened y ahi clickeamos y tenemos nuestro 555 actualizado
- **huellas**
- para el siguiente paso debemos asignar huellas al componente que crearemos, en este caso pondremos una nueva resistencia y sobre ella la tecla "f" de footprints, aquí se abrirá el menú de huellas y debemos clickear el ícono de 3 libritos, que son la biblioteca. En esta sección aparecen los distintos tipos de huellas de los componentes, nosotros buscamos una resistencia axial, seleccionamos medidas según nuestras preferencias y hacemos click
- se nombra también el resistor radial el cual físicamente es distinto a la resistencia axial, lo que cambia es el encapsulado
- ahora en segundo lugar debemos agregar un condensador (capacitor en kicad) el cual se busca con la letra C de capacitor y nuevamente repetimos lo mismo, debemos asignarle un valor, los dejaron en discord para revisarlos e ir al dia
- utilizaremos un capacitor de disco "c disc" que son las lentejitas que siempre usamos en la PCB, seleccionamos el tipo de capacitor disc que nos asignaron en discord, en este caso es uno de 6mm
- ahora debemos agregar un condensador polarizado, el símbolo de este condensador es distinto al normal porque este tiene un signo + y uno de los rectangulos del ícono está pintado y el otro no
- le asignamos huella a este condensador polarizado, en este caso usaremos una de capacitor radial, de 6.3mm
- ahora debemos poner un led en nuestro esquemático
- abrimos la biblioteca de huellas y asignamos un huella de led de 0.5 mm
- aparecen tambien leds de 3 patas los cuales son denominados led bicolor
- mostraron tambien que al apretar el 555 diseñado por misaaa y si está bien hecho, debería aparecer el package en las huellas
- los encapsulados de los 555 se llaman dip que significa dual in line package
- existen distintos tipos de dip, como el dip 6 de 6 patitas, dip 28 que es el de arduino, existen arduinos mas gruesos y delgados
- ahora pondremos un speaker pero hay un problema, ¿cómo le ponemos una huella a un speaker?
- misaaa propone que para solucionar esto ocupemos un tipo de conector específico que se llama "terminal block", son unos conectores que se atornillan
- le vamos a agregar un tipo de huella que se llama conn
- debemos buscar en las huellas "terminal block" para asignar nuestra huella al parlante, en este caso usaremos la TerminalBlock:TerminalBlock_MaiXu_MX126-5.0-02P_1x02_P5.00mm
- lo que importa es que el pitch debe ser de 5 mm porque así suelen ser los terminal block que podemos encontrar
- después de agregar la huella del parlante lo que falta es  GND Y VCC, no tienen huella porque no tienen forma física todavía
### parte 2: desarollo de esquemático
- primero conectamos nuestra pata 1 del 555 a GND
- creamos otro capacitor "C3" y lo conectamos a nuestra pata 5, el c3 va a GND
- ahora pata 8 y pata 4 a VCC
- conectamos pata 2 y pata 6 entre sí
- duplico mi resistencia, ahora tengo R2 y la conecto a la pata 7, duplico un vcc y conecto mi resistencia R2 a este vcc
- interconecto un condensador polarizado entre mi pata 2 y GND
- ahora debo conectar mi pata 3 a una resistencia, de la resistencia al LED y del LED a GND, ojo con que quede bien orientado LED porque sino se nos puede quemar ojo ojo
- luego conecto un condensador polarizado directo a mi pata 3 sin pasar por la resistencia y conecto el condensador al parlante
- el parlante lo conecto a GND
- ahora agregaremos un caimán, lo buscamos como conn y debe ser 01x01 que es de 1 pin
- a raiz de una pregunta de felix de cual es la diferencia entre este y el socket, misaa responde que uno es una punta y el otro es un hoyito para colocar una punta, a raiz de esto aaron responde que está lleno de este lenguaje de "que se mete dentro de que, que sigue aqui" y habla sobre un blog que se llama cdm.link que hablan de un esfuerzo para destruir todo este lenguaje violento que se utiliza en este mundo
- colocamos el pin 01x01 con el circulito hacia la derecha
- 
  
