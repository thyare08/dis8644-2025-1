# sesion-07b

## Módulo de la mañana

Hay una nueva carpeta en el GitHub: 00-libsKicad-teee.

Library son los símbolos para el esquemático; “modules” son las huellas de estos símbolos.

Ahora vamos a aprender cómo el KiCad aprende a cargar estas librerías para poder ser usadas en futuros proyectos.

la esquina inferior derecha de un archivo .sch de KiCad (screenshot 1 de hoy); si hago doble clic, se puede cambiar el formato, la compañía, el título, la fecha de creación.

![1ra screenshot](./archivos/7bScreenshot-(1).png)

![2da screenshot](./archivos/7bScreenshot-(2).png)

Vamos a cargar 555 well oriented, preferencias manage symbol libraries; después presiono la carpeta en la esquina inferior izquierda, busco mi archivo de 555 well oriented que descargue y lo cargo.
![3ra screenshot](./archivos/7bScreenshot-(3).png)
![4ta screenshot](./archivos/7bScreenshot-(4).png)

Puse una resistencia, la seleccioné y presioné F para poder abrir el selector de huellas, para poder asignar la huella desde ahora en adelante, no el valor aún, ya que cada uno va a ser distinto.

Los encapsulados de los chips se llaman DIP (Dual In-line Package).

Como el parlante no quiere estar pegado a la placa, vamos a usar un terminal block en su huella. En el esquema estará el simbolo del parlante para que la persona que lo vea pueda reconocer que ahí estará el componente.

Vamos a colocar agujeros para poder colocar caimanes en nuestro esquemático con un “conn" de 1x1 pin.

Pin es una punta; el socket es donde se puede poner el pin.

Existen 2 switches, uno que es directo en la placa y otro que sería externo.

Para saber si este circuito funciona, se puede poner en una esquina del esquematico un LED y esto comprueba si es que la alimentación es correcta.

![5ta screenshot](./archivos/7bScreenshot-(5).png)

Para que nada explote ni nada así cuando se conecta con la polaridad inversa, es colocarle un diodo, con la alimentación en la parte superior de nuestro esquemático.

![6ta screenshot](./archivos/7bScreenshot-(6).png)

## encargo-16: cotizar udpudu en JLCPCB de forma productiva

Donde esté, reconocerá las dimensiones que establecí en KiCad y la cantidad de capas, donde cambié a 30 en la cantidad de PCB.

![1ra screenshot](./archivos/encargo16-(1).png)

El grosor de la PCB será de 1.2mm, debido a que es la opción más barata. Según su grosor, la PCB de 1.6mm aumenta su precio calculado y de envío, mientras que los grosores de 1 mm y 0.8mm tendrán el mismo valor que la de 1.2mm, y si se fuese a un grosor aún menor que este, el precio también aumentaría.

Entre los colores de la PCB, las opciones moradas y verdes serían las más apropiadas, ya que son las de menor precio.

Entre el precio de construcción de las placas, elegiría el de 3 días, ya que este saldría sin un precio añadido.

Y por último, entre los costos y medios de envío, DHL es la opción más conveniente, demorando entre 2-4 días hábiles en caso de que se necesitase con un tiempo límite corto para algún proyecto. Sino, FedEx ofrece un precio ligeramente menor con una demora de 6-10 días hábiles.

![2da screenshot](./archivos/encargo16-(2).png)

Finalmente, el precio total aproximado quedaría en 65.47$ dólares americanos.

![3ra screenshot](./archivos/encargo16-(3).png)

## encargo-17: cotizar udpudu en JLCPCB de forma experimental

Como cotización experimental, como material de base seleccioné el flexible, con la idea de que se podría ocupar de maneras interesantes al momento de crearle un case, aunque no estoy seguro de si los componentes no sufrirán alguna deformación.

En cantidad pensé en 50 para poder tener una para cada persona del taller, más extra de personas que tal vez se interesaran en el lab de interacción digital.

Ya que es un producto de consumo, no cambie este parámetro ni a aeroespacial ni a médica.

En el espesor lo dejé en 0.12mm, que sería el punto medio para este tipo de PCB.

El color lo cambié a negro, que aunque sea un aumento de casi 20 dólares en precio, se veía mucho mejor en mi opinión.

![1ra screenshot](./archivos/encargo17-(1).png)
![2da screenshot](./archivos/encargo17-(2).png)
