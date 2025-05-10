# sesion-07a
# clase 22/04
## Bandcamp

Bandcamp es una tienda de discos en línea y una comunidad musical donde fanáticos apasionados descubren, se conectan y apoyan directamente a los artistas que aman. Abrió su web en septiembre de 2008, y en 2012 posee un catálogo de más de 5 millones de canciones, más de 600.000 álbumes procedentes de 183 países.​ 

## Noise Toys

Noise Toys es una serie de sintetizadores listos para usar, creados por el trío de Brooklyn Loud Objects, conocido por construir y programar su propio hardware de audio. Los Noise Toys son versiones portátiles de los chips musicales que Loud Objects utiliza en sus actuaciones en directo, y están disponibles en cinco sabores sonoros diferentes. Cada Noise Toy está programado con su propio patrón de sonido generativo de 1 bit, provisto de un interruptor de encendido basculante de estilo antiguo, dos botones que modulan el sonido y una toma de salida de audio.

https://loudobjects.bandcamp.com/album/noise-toys

![Loud Objects](https://github.com/user-attachments/assets/d5000f77-77ce-4aaa-b508-dfb54c5dda8d)

## introducción a KiCad
KiCad facilita el diseño de esquemáticos para circuitos electrónicos y su conversión a placa de circuito impreso, permitiendo vistas en 3d de lo que sería la placa final en fisico.

KiCad cuenta con 2 etapas:

la primera tiene que ver con todo los esquemático (sch), aquí es donde entran los componentes a utilizar, la asignación de huellas, la creación de una cédula, etc.

Asignar huellas: Sirve para poder observar la fisicalidad de los componentes que se usaron en el esquemático, es una forma de graficar todo lo que se usara para la creación de nuestro circuito que luego será llevado a una placa.

## pasos para la creación de un nuevo proyecto de esquemático (etapa 1) 
1. Crear una carpeta (para proyectos)
2. Crear un nuevo archivo
3. Abrir carpeta SCH
## notas sobre comandos/ creando el esquemático
- Preferencias: para navegar (command + ,)
     - shift para navegar
- Añadir simbolo
     - (A)
- Editar campo de valor
     - seleccionar componente + v
-  Hacer conexiones a través de cables
     - (w)
     - ° o la burbuja quie decir que el espacio se encuentra disponible para ser conectado
     - opciones de visualización - colores: para cambiar el color del cable
- Mover componentes juntos (agrupados)
     - (G)
- Utilizar el simbolo -X para marcar que no hay una conexión en cierto punto
  
- Propiedades del símbolo: permite ver la hoja de vida de un componente
   
- (R_POT): Potenciometro

- Anotar esquémas: enumerar los componentes según van apareciendo (indica los pasos hechos)

- Control de reglas eléctricas (ERC)

- Asignar huellas
     - F sobre el componente para asignar la huella directamente
     - nombre - valor - encapsulado

- El visor me permite ver la fisicalidad y caracteristícas de un componente

- Ajustes de página: para rellenar cédula

- DIP: Dual in-line package 
## comandos 
x = reflejar

q = x (que no hay nada ahí)

a = añadir

r = rotar

m = mover

w = conexión entre cables

t = info/ texto

f = nombre del componente

v = asignar valor 

command = zoom

command s = save

command d = duplicar

pitch: distancia entre los pads o pines (espaciado)

![sch] <img width="893" alt="Captura de pantalla 2025-05-09 a la(s) 11 20 09 p m" src="https://github.com/user-attachments/assets/4a36ff67-4704-41e3-a0bf-33838d5eea48" />

## Editor de placas (etapa 2) *anotaciones*
Para las pistas NO se puede por encima 
Vía: Es un enlace que pasa de un lado de la placa hacia otro
Pista roja: indica que va por arriba 

## encargo 14
Para el esquemático en KiCad repliqué uno de los apc que vimos en alguna de las sesiones anteriores, este contaba con botones, pero sin embargo y una de las dudas que me surgió fue como poner los botones, con que nombre buscar el componente para poder añadirlo.

![esquemático](https://github.com/user-attachments/assets/076944f8-427e-4462-bcda-d495d3373f1b)

## encargo 15
Dudas sobre KiCad:

¿Cómo poner botones?, ¿nombre del componente?, ¿switch, btn , push?

¿Cómo reordenar el 555?

¿Cómo rellenar la tabla de info para el esquema? (sheet, title, size, date, rev)

¿Cómo hacer una BOM?

Necesito repasar como poner y agregar huellas, y repasar el pcb editor
