# sesion-04b

## clase viernes 4 de abril

### apuntes

llegué tarde otra vez, nunca más voy a llegar tarde.

### apuntes sueltos

- interfaz, ¿qué está comunicándome a mí la electrónica que está dentro?
- ¿se refiere a todo lo del objeto que interactúa conmigo de alguna forma?
- HCI: Human Computer Interface
- en un objeto electrónico, el que mostraron en clases que era una especie de juguete, preguntarse: ¿por qué un botón hace algo y el otro otra cosa?¿por qué los dós no actúan al mismo tiempo?, las respuestas a estas preguntas son decisiones de diseño que se tomaron al momento de crear la electrónica del objeto.
- cómo la superficie interactúa con el usuario después de resolver la electrónica dentro.
- nombraron a Elías Zacarías, su github es battlecoder, diseñó la insoladora ---> revisar en github.
- ¿por qué los computadores no pueden generar números aleatorios? --> el aleatorio nunca ha sido realmente aleatorio, no existe.
- diagrama de bloque: cómo están conectadas las cosas
- ejemplo de esto: un atari punk posee un 555 astable conectado a uno inestable
- la idea de explicar el cómo funciona la electrónica, partir de la idea hasta lo más detallado posible poco a poco
- falstad.com--> osciloscopio
- revisar musicfromouterspace.com
- lehle.com ---> lo más fino en pedales dijo aaron montoya
- katode--> especializada en componentes electrónicos para pedales.

### más apuntes en otro bloque

- revisamos un moog, llevaron uno a clases, me pareció una máquina increíble, nunca había visto uno en persona
- revisamos un video de wendy carlos, creadora de switched on bach, una serie de interpretaciones de las famosas melodías de bach pero a través de sintetizadores, fue de las pioneras que demostraron que los sintetizadores podían ser utilizados para hacer música de verdad, ya que hasta ese momento, no eran tomados muy en serio musicalmente hablando.
- monoestable significa que posee 1 estado de estabilidad

### circuito del día

![IMG_20250408_014645](<https://github.com/user-attachments/assets/71e68bd3-6d92-405b-af8b-ff3b2250432f>

diagramamos de forma que entendemos que la entrada es por la izquierda, salida a la derecha, voltaje positivo arriba y voltaje negativo abajo.

<https://github.com/user-attachments/assets/d7729c86-7298-476a-a743-4879be39f2cc>

- hacer un botón experimental el findesemana
- usar info para mandarla a otra cosa
- astable controla al monoestable
- las placas verdes son las pcb

- **proj1: bajando opacidad a la caja negra**
- escoger un aparato elecrónico que no funciona (o estén dispuestos a destruir) y abrirlo para explorar su interfaz, diseccionar, analizar, obviamente debe estar desconectado y apagado, no trabajar a pata pelá
- ¿de dónde obtiene energía este aparato?
- qué interacción ofrece desde afuera? hay botones? perillas? cuántos? qué grados de control entrega? hay varias? cómo se interconectan? hay números? textos o dibujos? versiones? números de serie?
- realizar diagrama de flujo, qué placas requieren alimentación? dónde llegan las interacciones? usar lenguaje simbólico propio
- cómo se utiliza el aparato? cómo me indica ese modo de uso?
- documentar en fotografías

## desarrollo de encargo

![minime](https://github.com/user-attachments/assets/0f7f5a01-8f04-4125-91b0-57689ec4e58b)

El objeto utilizado fue una cámara instax mini 8, la cámara ya estaba mala por lo cual fue fácil acceder a abrirla, en verdad la rompí porque no podía abrirla.

- **¿De dónde obtiene energía este aparato?**

- la cámara obtiene energía mediante el uso de 2 pilas doble AA que van puestas en el compartimiento de pilas, lo cual va conectado a la pcb principal

- **¿Qué interacción obtiene desde afuera?**

- las interacciones que ofrece el objeto desde afuera a simple vista son 5.
- La primera interacción es para encender la cámara y es con un botón que se ubica en el costado inferior izquierdo al lado del obturador, este botón tiene una forma curvilinea, al apretarlo la cámara despliega el lente hacia afuera y abre el obturador.
- La segunda interacción que nos ofrece es el botón para sacar fotos, está ubicado en el costado superior derecho y es redondo, este se presiona hacia adentro y se saca la foto.
- La tercera interacción que ofrece la cámara es una especie de manilla alrededor del lente que se gira, este sirve para cambiar los modos de la cámara, a diferencia de las otras 2 interacciones, esta manilla posee luces que se prenden  por encima las cuáles nos indican en cuál modo de filtro fotográfico estamos. La cámara por sí sola prende luces de color rojo para indicarnos cuál filtro o modo de foto es mejor para el contexto en el cuál estamos realizando la fotografía. Además de esto, para saber en cuál modo/filtro estamos, la cámara posee 5 dibujos distintos los cuáles describen específicamente el modo.
- Además de todo esto la cámara también posee un flash, pero a diferencia de otras cámaras fotográficas, este se activa por sí solo al momento de sacar la foto.
- La última interacción que nos ofrece desde afuera se realiza mediante la parte posterior de la cámara en la cuál se encuentra una pequeña ranura que nos permite abrir la cámara, tiene forma cuadrada. Cuando abrimos esta ranura encontraremos la película o el rollo fotográfico el cuál es una caja negra rectangular, esta caja una vez dentro, no permite abrir la ranura otra vez hasta que saquemos las 10 fotografías pertinentes que nos ofrece en primer lugar. Al momento de sacar la primera foto saldrá impresa por la parte superior de la cámara una foto en negro que sirve para calibrar la cámara, después de esta primera foto podremos comenzar a sacar fotos con normalidad.
- Por último ofrece en la parte superior derecha por el costado de la cámara, una pequeña ranura que sobresale la cuál posee una cuerda puesta sobre si misma, esto sirve para amarrarse la cámara en la muñeca y evitar caídas del objeto mientras tomamos fotos, es una medida de seguridad y comodidad para el usuario.

## el interior de la cámara

![IMG_20250411_010156](https://github.com/user-attachments/assets/d2dd0c99-e21c-40e0-bb4a-e544fdd9a986)

![IMG_20250411_010009](https://github.com/user-attachments/assets/124bca62-4153-46fa-a3f8-89bd52a0239e)

![IMG_20250411_005845](https://github.com/user-attachments/assets/799607fe-2e78-4aec-9826-e57d5326e9b1)

![IMG_20250411_005959](https://github.com/user-attachments/assets/400e969a-f013-4eec-9179-659d39bfb712)

![IMG_20250411_005919](https://github.com/user-attachments/assets/2706ac8d-3caa-4497-8de7-382dc9ea59ea)

![IMG_20250411_010035](<https://github.com/user-attachments/assets/323749f8-2b44-48ec-a8b4-71e783ed0bde>

### funcionamiento del interior

- la verdad me costó mucho entender el interior de la cámara y el cómo funciona, es de una dificultad mayor a la que pensaba y como tal no lo logré, pero sí rescaté algunas cosas mediante la observación de la PCB y los cables que van conectados entre sí

- . Como se muestra en la segunda foto, podemos ver que hay un condensador de gran tamaño, este mismo en la esquina derecha posee 2 cables que salen de él hacia la PCB principal, un cable rojo y un cable blanco. El cable rojo va conectado a un punto de la PCB que posee la sigla MC-, desconozco qué significa, por otra parte, el cable blanco va conectado a la parte MC+.
  . El flash de la cámara que está puesto en la PCB, posee 3 cables, uno rojo que va conectado a XE- (desconozco que significa), uno blanco que va conectado a XE+, cabe destacar que al lado de estas letras hay un chip de 8 patitas parecido al 555, que en su superficie posee los números 6519 y abajo P4009, desconozco la función de este chip. Por último el flash posee un cable gris que sale del interior de este mismo que se mete por debajo de la pcb principal a la cuál no tengo acceso porque no la pude sacar
  . En la parte inferior de la PCB se encuentran una serie de chips de distintos tamaños y números de los cuáles desconozco su función y no logro entenderla, entre estos chips están: BLQD,S33,D5N,PZ, 11 3, RSF 10377A. Lo otro que logro identificar además de los chips es una resistencia de 100 v, dice R100 y tiene forma cuadrada
  . También en esta parte de la PCB y en general hay muchas letras y números los cuáles no sé qué función tienen ni qué significan, entre estos se encuentran:
- XE, positivo y negativo
- MC, positivo y negativo
- Q
- SP
- SSYG
- SCAMG
- TM
- SSY
- IC
- CN1
- SM
- SMG
- DIS
- TPVB12
- Algunos de estas siglas (SCAMG,TM,SSY,SSYG,SM,SMG,SP,SCAM) van conectados a través de cables de distintos colores (amarillos,naranjas,blancos,rojos,morados,azules,verdes) hacia la parte de abajo de la PCB a la cuál no tengo acceso para poder ver hacia qué se conectan en ese lugar.

## encargo Switched On Bach

Switched On Bach fue creado por Wendy Carlos en octubre del año 1968 y fue lanzado en ese mismo año por Columbia Records. Éste álbum es una recopilación de piezas de Johann Sebastian Bach pero traspasadas al mundo de los sintetizadores. Carlos estudió y se graduó en Física y Música en Brown University, en su nativa Rhode Island, antes de mudarse a Nueva York en 1962 para estudiar Composición en Columbia University, donde estudió y trabajó con varios técnicos y músicos electrónicos en el Electronic Music Center de Princeton.

**un poco del contexto de cómo partió todo**

- Wendy Carlos había conocido al ingeniero Robert Moog en un evento de la Sociedad de Ingenieros de Audio en 1964, iniciándose una interesantísima asociación en la que Carlos contribuyó con consejos, peticiones y asistencia técnica en el desarrollo del famoso Sintetizador Moog. Carlos convenció a Moog de agregar un teclado sensitivo al toque para mejorar la dinámica de la interpretación, entre otras cosas que se fueron sumando a los sucesivos modelos. Moog reconoció siempre los aportes de Carlos y le dio su respectivo crédito. En 1966, Carlos ya era propietario de un pequeño Moog, el cual utilizó para grabar efectos de sonido y jingles para comerciales de televisión, que le proporcionaron algún dinero.

- Uno de los momentos clave de su historia fue cuando conoce a Rachel Elkind, que era una ex cantante que trabajaba también en los estudios Gotham y tenía un pasado en el jazz. Formaron una amistad y comenzaron a compartir hogar, estudio e ideas.

- El estudio casero incluía un grabador de ocho canales que el propio Carlos había construido usando partes de grabadores Ampex y EMI, el cual incluía un sistema llamado Sel-Sync patentado por Ampex que permitía que señales ya grabadas fueran monitoreadas por el cabezal de grabación en lugar de el de reproducción, con lo cual era posible mantener múltiples pistas en perfecta sincronía.

-Wendy Carlos cuenta que tardó 5 meses y mil horas en producir Switched On Bach, porque los sintetizadores no eran muy buenos y se desafinaban, por ende tenía que detenerse en múltiples ocasiones a revisar las grabaciones.

- Contó con colaboración de su amigo Benjamin Folkman y Rachel Elkind, que fueron piezas fundamentales en el álbum
- En 1969 entró sorpresivamente en la lista Billboard 200 y alcanzó el puesto 10, permaneció 59 semanas en cartelera
- Entre 1969 y 1972 permaneció como #1 en la lista de Billboard Classical Albums
- En 1970 obtuvo tres Grammy: mejor álbum clásico, mejor performance clásico para solista instrumental y mejor ingenieria de grabación de disco.

### opinión personal

el álbum me pareció muy original, creo que hay que ser un genio para poder reinterpretar una obra tan conocida de la música clásica y hacerlo de forma increíble. musicalmente hablando me pareció muy atractivo, creo que me gusta más que la obra original, no soy fan de la música clásica pero el cómo interpreta Wendy carlos las canciones hacen que sea mucho más interesante de escuchar. Los sonidos de los sintetizadores hacen que se genere un ambiente inmersivo cuando lo escuchas, esta obra es como si alguien que toca música clásica hubiera viajado al futuro a hacer su obra otra vez, para mí, es completamente adelantada a su época y me alegra mucho que haya tenido el reconocimiento que merecía.

![image](https://github.com/user-attachments/assets/c98699ee-e892-49f4-a041-ddcc22051345)

foto de la portada del álbum
