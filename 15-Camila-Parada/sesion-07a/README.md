# ⋆₊˚⊹♡ Clase 07a - Kicad y placas PCB ♡⊹˚₊⋆

##### _Martes 21/04/2025_

***

### Observaciones

<!---Recordar para programar "md" (markdown): 
- https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet 
- https://www.markdownguide.org/basic-syntax/
- El Domingo 30 de marzo cumplí 25... no se porqué me gustaría sentirme orgullosa de ello, que se me reconociera --->

Esta clase se centró en el aprendizaje de Kicad, por lo que fue primordial el tener un portátil con el cual trabajar.
El primer módulo se centró en aprender a cómo construir el esquemático y colocar las "huellas" (asociar piezas reales al listado de materiales).
La segunda parte de la clase se centró en orientar los materiales dentro de una placa PCB ficticia y a poder revisarlos en 3D.

<br>

***

### Bitácora digital

<br>

Cuando llegue a la sala estaban hablando de proyectos y programas que no alcancé a escuchar mucho. A la par hicierom circular por la clase varios proyectos enfocados en generar música y sonido, los cuales pude registrar mediante fotografías con mi teléfono.

<br>

### Bleep labs - "The Pico Paso"

![WhatsApp Image 2025-04-22 at 9 32 46 AM](https://github.com/user-attachments/assets/3b5edad9-1c76-4d5f-a6fe-d986e128c815)

![WhatsApp Image 2025-04-22 at 9 32 46 AM (1)](https://github.com/user-attachments/assets/6740cae8-6caf-4e10-816a-b072130bb96a)

_▼ Sitio web asociado: https://bleeplabs.com/product/the-pico-paso/_

<br>

### Loud Objects - "Noise Toys"

![WhatsApp Image 2025-04-22 at 9 32 47 AM](https://github.com/user-attachments/assets/ed01f290-bd0a-4aa0-aa67-b771a06f4842)

![WhatsApp Image 2025-04-22 at 9 32 47 AM (1)](https://github.com/user-attachments/assets/0a0ae4f6-4e2b-4f81-9c20-5d57fc69e416)

![WhatsApp Image 2025-04-22 at 9 32 49 AM](https://github.com/user-attachments/assets/b0d29e64-3aee-4258-b791-250bd2e9760b)

![WhatsApp Image 2025-04-22 at 9 32 49 AM (1)](https://github.com/user-attachments/assets/9c2cca9e-2406-4ab5-9a65-aa09307756c0)

_▼ Sitio web asociado: https://loudobjects.bandcamp.com/merch_

<br>

### Matías Serrano Acevedo - "Tarjeta de presentación"

![WhatsApp Image 2025-04-22 at 9 32 48 AM](https://github.com/user-attachments/assets/e7eeb9a0-9add-4826-b6cf-022a932e0a20)

![WhatsApp Image 2025-04-22 at 9 32 48 AM (1)](https://github.com/user-attachments/assets/1ac94898-b72a-4ec2-aab6-6ebe95be71d8)

_▼ Sitio web asociado: http://misaa.cc/home.html_

<br>

Después empezamos a hablar a rasgos generales sobre el programa Kicad, que es un repertorio de componentes
La primera etapa es el esquema. Se indican los componentes, el nombre, el valor. Solamente simbolo y conexión. Sin las dimenciones físicas.
Luego, para poder pasarlo a formato físico está el proceso de Footprint (huella), en la que se van colocando las dimenciones de los elementos para ir editando la placa ficticia.

En el siguiente proceso podrá ser visualizada en 3D la Placa de ruteo, que indica donde se van a colocar las partes exactas.

Este tipo de proyectos (Kicad) se pueden respaldar en github.

Al crear un archivo nuevo hay que permitir que se cree una carpeta con los documentos nuevos.
Aparecen 2 documentos: uno tipo sch y otro pcb. Procedemos a abrir el documento tipo sch, en el cual se trabajará el esquemático.
Apretamos el botón "Place symbols" (botón a), que abre una ventana emergente en la que se muestra una pantalla negra y un listado de cosas. Colocamos una resistencia, y usamos "r" para poder rotar. Para agregarle valor hay que presionar "v". Importante seleccionar el componente y no las letras.
Se colocan más componentes: un ne555, condensadores (uno polarizado), un led, conexión a tierra y conexión a energía.
Tras ello se presiona "w" para poner la herramienta de cables. Para mover el componente solo (sin las conexiones de cables) hay que presionar "m" y moverlo. Para trasladar el componente con el cable hay que precionar "g" y moverlo.
Ya que en este caso el Chip 555 tiene una terminal que no se va a conectar, hay que presionar el boton "q" para indicar que la pata número 5 no tendrá conexión. Después seguimos avanzando y realizando un esquema simple.

<br>

![image](https://github.com/user-attachments/assets/f4f262c6-3bb1-4873-951d-807e0c5dda59)

<br>

![image](https://github.com/user-attachments/assets/5c025e70-b67c-4716-b859-4b0b59735c3a)

<br>

Package-> Es el encapsulado y protege a la pieza. DO35 es la forma, o mejor dicho, el tipo de encapsulado.

En el siguiente módulo terminé desconcentrandome, por lo que decidí consultar el "Manual de supervicencia" del profesor Matías.

https://misaa.notion.site/Manual-de-supervivencia-para-KiCAD-8cc756e79ced4271ad575874aaa3497e

***

### Encargo clase 7a
 
#### 1.1 Esquemático "Atari Punk Console" en KiCad

<br>

Dado que ya tenía hecho el esquemático del circuito dibujado en Ilustrator, solo tuve que buscar los componentes e ir montando de nuevo la estructura. Con las piezas que no conocía su nombre u código decidí buscarlas en google. Tras ello sólo quedó acomodar las partes y asignar los valores.

<br>

![image](https://github.com/user-attachments/assets/a4d9139a-9d36-4ed3-a2d9-b81be012ac17)

_▼ Imagen del diagrama final en Kicad_

<br>

El archivo final se encuentra en la carpeta "diagram", puesto que al intentar subirlo a este documento github me lanzó el error "We don't support that file type", escribiendo muchas líneas de códigos (más de 300).

<br>

***

#### 1.2 Preguntas sobre "Manual de supervivencia para KiCAD"

<br>

1-. ¿Cómo poder ordenar las patitas del chip N555 u otros componentes?}

<br>

2-. ¿KiCad StepUp? Ayuda a poder descargar archivos en 3D

https://github.com/easyw/kicadStepUpMod/

<br>

***

#### 1.3 Película "Una mente brillante (2001)"

<br>

No es una tarea como tal, pero el profesor me dijo que sería un buen ejercicio verla.

Encontré la película en este link: https://www.genteclic.com/una-mente-brillante-2001-ver-pelicula-online/

<br>

***

### Posdata

Aquí aguantando contra viento y marea (っ- ‸ - ς)

***

##### _°˖✧◝(⁰▿⁰)◜✧˖°_
