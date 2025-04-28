# sesion-07b
Hay una nueva carpeta en el GitHub: 00-libsKicad-teee.

Library son los símbolos para el esquemático; “modules” son las huellas de estos símbolos.

Ahora vamos a aprender cómo el KiCad aprende a cargar estas librerías para poder ser usadas en futuros proyectos.

![1ra screenshot](./archivos/7bScreenshot-1.png)

la esquina inferior derecha de un archivo .sch de KiCad (screenshot 1 de hoy); si hago doble clic, se puede cambiar el formato, la compañía, el título, la fecha de creación.

(espacio para escreenshots)

Vamos a cargar 555 well oriented, preferencias manage symbol libraries; después presiono la carpeta en la esquina inferior izquierda, busco mi archivo de 555 well oriented que descargue y lo cargo.

Puse una resistencia, la seleccioné y presioné F para poder abrir el selector de huellas, para poder asignar la huella desde ahora en adelante, no el valor aún, ya que cada uno va a ser distinto.

Los encapsulados de los chips se llaman DIP (Dual In-line Package).

Como el parlante no quiere estar pegado a la placa, vamos a usar un terminal block en su huella. En el esquema estará el simbolo del parlante para que la persona que lo vea pueda reconocer que ahí estará el componente.

Vamos a colocar agujeros para poder colocar caimanes en nuestro esquemático con un “conn" de 1x1 pin.

Pin es una punta; el socket es donde se puede poner el pin.

(espacio para screenshot)

Para saber si este circuito funciona, se puede poner en una esquina del esquematico un LED y esto comprueba si es que la alimentación es correcta.

Existen 2 switches, uno que es directo en la placa y otro que sería externo.

(espacio para screenshot)

Para que nada explote ni nada así cuando se conecta con la polaridad inversa, es colocarle un diodo, con la alimentación en la parte superior de nuestro esquemático (screenshot).

