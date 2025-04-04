# sesion-04a
## clase martes 1 de abril
## apuntes de la clase

Este día llegué un poco tarde (bastante) por lo que me perdí un poco el comienzo de la clase lamentablemente, Sin embargo, hay apuntes de todas formas.

### taller: La última hoja del cuaderno porque se me acabó, 01/04/2025.

100 Days Of Drawing guide, libro de Jennifer Orkin Lewis ---> Misaa lo mencionó en clases así que lo anoté porque puede servirme, en el comienzo de la clase estaban hablando acerca de la inspiración y me quedé con la frase popular "Que la inspiración te encuentre trabajando". Aprecio los espacios en los cuáles se habla temas mas allá de lo académico y se entra un poco más en lo mental/emocional, es curioso ver como los profesores que también son personas, pasan y pasaron por procesos muy similares a los tuyos, siempre es grato escuchar sus consejos y experiencias.

**apuntes sueltos, tipeos**:

- Si voy a commits, puedo revisar los cambios que han habido, las cosas que borró el profe en rojo y las cosas que agregó, están en verde.
- Tenemos 1 semana para poder encontrar un objeto roto, desarmado, el viernes lo van a explicar de forma más detallada
- Proyecto 1 --> temible.
- 1. Explicación textual del dispositivo, declaración inicial del proyecto
  2. Diagrama de objetos, dibujos de la electrónica (Anatomía de la fisicalidad del dispositivo), en texto, imágen, diagramas de flujo, ilustraciones, contexto con humanos en uso
  3. Bitácora multimedia de proceso
  4. Esquemático de electrónica, con todos los componentes y justificaciones, citas, bill of materials
  5. Presentación oral con soporte en markdown en github
  6. Funcionamiento, si es estable o no, frágil/robusto
 
### comienzo de la clase como tal, Atari Punk Console y más.

- Atari Punk Console (APC): Circuito fácil de adaptar, es muy escalable y personalizable
- Escuchar 1 Bit Symphony Álbum
- Modulación: es el cambio de valor
- Existen muchas variaciones de cómo hacer el Atari Punk Console, no existe una establecida
- Más adelante ocuparemos el software Kicad
- 555 timer circuit --> página con mucha info acerca del maravilloso 555

**armado del circuito posterior al de la semana pasada (me perdí el de la semana pasada pero igual se logró)**
  
  - No tenía más hojas de cuaderno por lo que no pude anotar tantas cosas acerca del desarrollo del circuito, subo foto que dejó profe Misaa en el github, es el circuito que hicimos en clases.

  ![atariPunk_v1](https://github.com/user-attachments/assets/8f7c5e69-a4e9-421e-99f5-290d514b93e8

  **tipeos, cosas aprendidas durante el armado del circuito**

  - Los capacitores suman su valor si los pongo en paralelo
  - Si cambio los capacitores por uno de más valor, el sonido es más grave, en cambio, si el valor de los capacitores es menor, el sonido será más agudo
  - Si utilizo un potenciómetro en vez de un LDR (fotoreceptor) puedo hacer que el sonido suene de forma más escalada, una compañera de la clase logró un sonido bastante escalado.
  - Capacitores se suman en paralelo, resistencias se suman en serie: **NO OLVIDAR**
  - Me comienzo a familiarizar un poco más con el 555 y también con los esquemáticos, en un principio era más como conectar cables por conectar, ahora estoy entendiendo mejor para qué sirve cada componente y estoy siendo más consciente de lo que estoy haciendo, es un gran avance.
  - Andrés me ayudó mucho con mis dudas, generalmente suelo quedarme atrás pero Andrés es un gran ayudante, explica todo con paciencia y siempre está dispuesto a ayudar, Andrés lo más grande.
  - A modo de reflexión, me falta estudiar más acerca de las piezas por mi cuenta, sobretodo del 555 y para qué es específicamente cada "patita", lograr entenderlo bien.
  - No pude subir videos del circuito a github, averiguar cómo hacerlo.

### fotos de lo que fue el circuito ya armado completamente:

![1743743697695](https://github.com/user-attachments/assets/c9ecbb9e-ad2e-4a11-a491-4d745c706ef3)
![1743743678014](https://github.com/user-attachments/assets/0bb3b5f3-e160-400e-88c6-1c872729eba0)


## encargo 10: 1 bit symphony.

![1bit01](https://github.com/user-attachments/assets/a8fc0246-ed0e-413a-9387-23922a71d50b)


Nos pidieron escuchar el álbum 1 bit symphony de Tristan Perich, 1-Bit Symphony es una composición en cinco movimientos en un sólo microchip. Aunque guardado en una caja de CD, 1-Bit Symphony no es una grabación en el sentido tradicional, sino que literalmente realiza un performance de la música en vivo cuando se prende. Un circuito electónico completo (programado por el artista y montado a mano) toca la música a través de una toma de auriculares que se conecta a la misma caja. Fue creado en 2010 y es la primera obra de Tristan Perich. Dejo algunas fotos de la obra y también de una muestra que tuvo en barcelona en 2015.

![image](https://github.com/user-attachments/assets/7103af3c-3365-4785-9fbd-cc26ec860218)

![image](https://github.com/user-attachments/assets/ee72c7e5-c08b-4b09-93a7-deb2a42eb383)

![image](https://github.com/user-attachments/assets/cc31f170-c7a6-4532-868c-a17e3fde6309)

### 1 bit symphony, angels barcelona, 2015.

![image](https://github.com/user-attachments/assets/fad53412-7c08-46dc-a228-eb8a99895ee7)

![image](https://github.com/user-attachments/assets/bd3241cf-2caf-46ab-bf91-90c223ca1d6f)

![image](https://github.com/user-attachments/assets/87832fdc-dab5-43c0-8008-7f7a2216d1e8)

Encontré una entrevista a Tristan Perich en el sitio web "composer focus", llamada: Insight 1 bit symphony. Dejo la traducción porque está en inglés.

**¿Cómo surgió la idea de 1-Bit Symphony?**

1-Bit Symphony llevaba tiempo gestándose. En 2004, cuando empecé a trabajar en mi primer álbum, 1-Bit Music, aún no tenía claro qué quería transmitir con el sonido y el concepto, y desde su lanzamiento sentí la necesidad de profundizar en ello. Tras haber decidido lanzar un álbum como microchip, me sumergí de lleno en la música y exploré las diversas ideas musicales que había estado considerando en mis composiciones acústicas. Fue una gran experiencia pasar unos meses trabajando en un medio sonoro muy específico. La idea de crear una sinfonía electrónica me abrió un amplio abanico de posibilidades. Creo que al final dije lo que quería decir.

**¿De dónde viene tu interés en el género bit?**

De niño, era un friki total, un apasionado de las matemáticas, la física y la programación. Aunque también componía partituras para conjuntos acústicos, la programación informática se mantenía a distancia. No sentía que tuviera nada que decir sobre el sonido electrónico. Todo cambió cuando empecé a programar microprocesadores como el que protagoniza 1-Bit Symphony. De repente, la computación, algo que antes era abstracto y virtual, se arraigó en el hardware. Cobró presencia física, y casi podía sentir los electrones moviéndose dentro del microchip mientras ejecutaba las líneas de software. El código se volvió algo más tangible, y el sonido electrónico era su forma de hablar. El sonido era crudo, áspero, primitivo y fresco. Mis amigos exploraban sonidos similares en la escena chiptune y toqué algunos conciertos con ellos. Finalmente, mis ideas compositivas volvieron a la música compuesta, y ahora considero que el violín u otros instrumentos acústicos están estrechamente relacionados con los altavoces que reproducen formas de onda de 1 bit.

**¿Cómo se te ocurrió la presentación de la obra? ¿Por qué no una simple grabación tradicional en CD?**

Trabajar con 1 bit me permite prescindir de muchas capas complejas de hardware y centrarme en la relación entre el código, los datos que genera y el sonido. Cuando el microchip emite unos y ceros, son pulsos eléctricos intermitentes. Al conectarlo a unos auriculares, la electricidad activa el electroimán, moviendo la membrana del altavoz y creando sonido. Al liberar el circuito completo como un objeto físico, me permitió enfatizar el proceso del sonido electrónico. Una grabación no es lo mismo que una interpretación, y en este caso, escuchar el álbum físico es una experiencia profundamente diferente a escuchar un MP3 de la música. Esto no significa que me importe si la gente escucha la música en sus reproductores de MP3. Simplemente es diferente. (Tampoco se puede grabar exactamente la pista final infinita).

**¿Cómo fue el proceso de programación y montaje del dispositivo?**

Escribo código en ensamblador, un lenguaje de programación estrechamente relacionado con la funcionalidad del hardware. Programé un sistema para crear partituras musicales, que codifiqué como secuencias de números. Ese código se transfiere al chip en un proceso muy similar a sincronizar un reproductor de música. Los dispositivos fueron ensamblados por un fantástico equipo de asistentes aquí en mi estudio de Nueva York.

**¿Cada interpretación de 1-Bit Symphony es idéntica o habrá variaciones?**

Nada es idéntico en nuestro mundo analógico. Dicho esto, los sistemas digitales funcionan con un subconjunto de información del mundo que nos rodea, y en ese ámbito… sí, cada reproducción de 1-Bit Symphony es teóricamente igual a todas las demás. La partitura es la misma, el código es el mismo, y no hay aleatoriedad ni interactividad. Sin embargo, una variación es que cada chip funciona a una velocidad de reloj ligeramente diferente, por lo que algunos dispositivos tienen un tono más agudo o más grave que otros.

**Describe tu proceso creativo al escribir la música para esta composición. ¿Empiezas con lápiz y papel o con un soporte de 1 bit desde el principio?**

Para mí, componer es una combinación de varios sistemas, desde tocar instrumentos de teclado hasta trabajar con secuencias numéricas, pasando por esbozar ideas en software de audio y probarlas en hardware. Crecí componiendo con lápiz y papel, y mi proceso se ha desarrollado a partir de esas raíces.

**¿Cuáles han sido tus mayores influencias como compositor?**

Como muchos compositores de mi generación, mi mayor influencia fue, sin duda, Philip Glass, cuyas primeras obras épicas son la personificación de la belleza del proceso. Además de compositores como él y Steve Reich, me inspira la obra de músicos electrónicos como Ryoji Ikeda y SND.

**¿Qué te depara el año 2011?**

Este año estoy empezando a trabajar en proyectos muy grandes: obras de una hora para conjuntos de 50 violines y 50 altavoces, un concierto para piano solo en un mar de cuarenta altavoces. Estoy construyendo una instalación de audio con 1500 altavoces afinados microtonalmente para abarcar cuatro octavas. Y sigo explorando constantemente cómo la línea puede llenar el espacio con mis dibujos a máquina.

### Opinión personal

Me sorprendí totalmente el cómo está grabado este álbum, es algo que aún no logro comprender bien. Me gustaría que existiera una forma de ver cómo funciona todo el circuito mientras se reproducen los sonidos y la música, el qué hace cada componente para que suene de tal forma y por qué no todos los tracks suenan iguales, creo que lo que me gustaría es que se pudiera ver con un microscopio. Estoy escuchando el álbum mientras escribo estos apuntes y la verdad es totalmente hipnótico. Creo que se forma alguna especie de ruido blanco que te atrapa totalmente en lo que estás escuchando y te desconecta de cualquier otro estímulo, quedé atrapado completamente en un trance mientras lo escuchaba. Cuando terminó el último track "Movement 5" que dura 14 minutos con 51 segundos, hubo un silencio total en mi habitación, como si me acabara de desconectar de un estímulo muy fuerte y atrapante, siento que es para escucharlo cuando necesitas concentrarte mucho, a mi me generó una especie de hiperfoco. Creo que es una maravilla el saber que algo así fue creado, nunca había conocido un disco que se reproduciera en el momento en que se activa el mecanismo de los chips, es como ese pensamiento de que hay personas tocando la música adentro de la radio, algo similar sucede dentro de esto pero con la magia de la electrónica, absolutamente increíble.










  
