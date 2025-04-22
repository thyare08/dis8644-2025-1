# ⋆₊˚⊹♡ Clase 06b - Feriado ♡⊹˚₊⋆

##### _Viernes 18/04/2024_

***

### Observaciones

<!---Recordar para programar "md" (markdown): 
- https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet 
- https://www.markdownguide.org/basic-syntax/
- El Domingo 30 de marzo cumplí 25... no se porqué me gustaría sentirme orgullosa de ello, que se me reconociera --->

La clase pasada falté a la entrega del día martes por encontrarme enferma de gastroenteritis, por lo que no supe que pasó más allá de revisar los repositorios de los estudiantes y leer las indicaciones de los profesores para la clase.

***

### Bitácora digital
<br>
Cuando llegue a la sala estaban hablando de proyectos y programas que no alcancé a escuchar mucho. A la par hicierom circular por la clase varios proyectos enfocados en generar música y sonido, los cuales pude registrar mediante fotografías con mi teléfono.

![WhatsApp Image 2025-04-22 at 9 32 46 AM](https://github.com/user-attachments/assets/3b5edad9-1c76-4d5f-a6fe-d986e128c815)

![WhatsApp Image 2025-04-22 at 9 32 46 AM (1)](https://github.com/user-attachments/assets/6740cae8-6caf-4e10-816a-b072130bb96a)

<br>

![WhatsApp Image 2025-04-22 at 9 32 47 AM](https://github.com/user-attachments/assets/ed01f290-bd0a-4aa0-aa67-b771a06f4842)

![WhatsApp Image 2025-04-22 at 9 32 47 AM (1)](https://github.com/user-attachments/assets/0a0ae4f6-4e2b-4f81-9c20-5d57fc69e416)

<br>

![WhatsApp Image 2025-04-22 at 9 32 49 AM](https://github.com/user-attachments/assets/b0d29e64-3aee-4258-b791-250bd2e9760b)

![WhatsApp Image 2025-04-22 at 9 32 49 AM (1)](https://github.com/user-attachments/assets/9c2cca9e-2406-4ab5-9a65-aa09307756c0)

<br>

![WhatsApp Image 2025-04-22 at 9 32 48 AM](https://github.com/user-attachments/assets/e7eeb9a0-9add-4826-b6cf-022a932e0a20)

![WhatsApp Image 2025-04-22 at 9 32 48 AM (1)](https://github.com/user-attachments/assets/1ac94898-b72a-4ec2-aab6-6ebe95be71d8)

<br>

Después empezamos a hablar a rasgos generales sobre el programa Kicad, que es un repertorio de componentes
La primera etapa es el esquema. Se indican los componentes, el nombre, el valor. Solamente simbolo y conexión. Sin las dimenciones físicas.
Luego, para poder pasarlo a formato físico está el proceso de Footprint (huella), en la que se van colocando las dimenciones de los elementos para ir editando la placa ficticia.

En el siguiente proceso podrá ser visualizada en 3D la Placa de ruteo, que indica donde se van a colocar las partes exactas.

Este tipo de proyectos se pueden respaldar Kicad en github.

Al crear un archivo nuevo hay que permitir que se cree una carpeta con los documentos nuevos.
Aparecen 2 documentos: uno tipo sch y otro pcb. Procedemos a abrir el documento tipo sch, en el cual se trabajará el esquemático.
Apretamos el botón "Place symbols" (botón a), que abre una ventana emergente en la que se muestra una pantalla negra y un listado de cosas. Colocamos una resistencia, y usamos "r" para poder rotar. Para agregarle valor hay que presionar "v". Importante seleccionar el componente y no las letras.
Se colocan más componentes: un ne555, condensadores (uno polarizado), un led, conexión a tierra y conexión a energía.
Tras ello se presiona "w" para poner la herramienta de cables. Para mover el componente solo (sin las conexiones de cables) hay que presionar "m" y moverlo. Para trasladar el componente con el cable hay que precionar "g" y moverlo.
Ya que en este caso el Chip 555 tiene una terminal que no se va a conectar, hay que presionar el boton "q" para indicar que la pata número 5 no tendrá conexión. Después seguimos avanzando y realizando un esquema simple.

![image](https://github.com/user-attachments/assets/f4f262c6-3bb1-4873-951d-807e0c5dda59)

![image](https://github.com/user-attachments/assets/5c025e70-b67c-4716-b859-4b0b59735c3a)

Package-> Es el encapsulado y protege a la pieza. DO35 es la forma, o mejor dicho, el tipo de encapsulado.



***

### Encargo clase 6a

#### 1.1 Instalación  KiCad

<br>

Comencé por buscar la página de descarga del programa mediante Google. Tras ello ingresé al link de la página original (https://www.kicad.org/) y luego le di click en el botón azul "Download". Al hacer eso me redirige a una página de descargas en la que me consulta acerca del sistema operativo de mi portatil, que en este caso es Windows 10 con un sistema operativo de 64 bits.

<br>

![image](https://github.com/user-attachments/assets/9ab6a211-0e6d-4d04-9a75-e93190988f10)

<br>

Conociendo esa información me dispuse a obtener la descarga de la versión 9.0.1 para un procesador de 64x. Ya bajado el archivo fui a la carpeta de "Descargas", donde decido abrirlo para comenzar con la instalación.

<br>

![image](https://github.com/user-attachments/assets/b37005dd-2d5e-4bf0-b3de-ff2489161964)

<br>

Tras ello me aparece una interface que ya reconocía, puesto que es la que trae por defecto varios programas al momento de istalarlos.

<br>

![image](https://github.com/user-attachments/assets/728eed79-861c-4f5b-a41a-7551b5f54aa4)

<br>

Le di continuar y permití que se instalara para todos los usuarios disponibles en la computadora. Acepté dando los permisos de administrador. Lo que continua es realizar la selección de los componentes que quiero instalar, que en este caso los incluyo todos. Además, puedo ver que el programa pesa 5,8 GB aprox.

<br>

![image](https://github.com/user-attachments/assets/32280c94-5d0d-4c94-becc-1a5b40e4403c)

<br>

La siguiente decisión a tomar es elegir la carpeta en la cuál será instalado el programa. Dado que no dispongo de demasiado almacenamiento en el disco duro que incluye por defecto el PC termino recurriendo a la memoria externa que incluye el dispositivo, ya que dispone de mayor cantidad de espacio disponible (742 GB).En este caso para poder usar elemento tuve que crear ua carpeta adicional que nombré como "Kicad".

<br>

![image](https://github.com/user-attachments/assets/f47b4eac-04fa-4bbf-8369-1c00308a5055)

<br>

Ya lista la instalación el programa se abre. Y me deja ver la interface de este, que por suerte está en español.

<br>

![image](https://github.com/user-attachments/assets/3e678766-125a-4056-a33b-be3517b0f88c)

<br>

Después me puse a ver que información contiene la carpeta del programa.

<br>

![image](https://github.com/user-attachments/assets/a10be77c-870d-4df0-ae08-47a07515b14c)

<br>

Y en la subcarpeta "bin" encuentro el acceso al programa como tal.

<br>

![image](https://github.com/user-attachments/assets/e244b639-4675-4612-97ec-3b865c04b14e)

<br>

***

#### 1.2 Documental Sisters With Transistors

<br>

Pendiente...

<br>

***

### Posdata

La semana pasada fue horrible, espero que esta sea mejor ૮◞ ﻌ ◟ა

***

##### _°˖✧◝(⁰▿⁰)◜✧˖°_
