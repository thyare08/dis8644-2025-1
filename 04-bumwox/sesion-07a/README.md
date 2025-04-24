# sesion-07a

## kicad

__características de los componentes__

- símbolos
- valores
- __"rating"__: cuanto aguanta el componente
- __"footprint"__: huella, fisicalidad con el componente

## etapas kicad

- __esquemas__: hacer el esquemático (SCH)
 - que componentes, símbolos, valores, etc
- traspaso al mundo físico
 -footprint, la base de los componentes que se usan y verlo en 3d
- __ruteo__: diseño de la fiscalidad 

## proyecto en kicad, 555 + variaciones

__atajos__

- __r__: rotar
- __m__: mover
- __a__: añadir
- __shift + rueda panel táctil/mouse__: arriba/abajo
- __ctrl + rueda panel táctil/mouse__: izquierda/derecha
- __v__: valor del componente
- __ctrl + z__: deshacer movimiento
- __esc__: para volver al cursor
- __w__: para conectar los componentes
- __q__: para poner l x cuando los pin no se usan y especificar
- __x__: se refleja en  eje x
- __y__: se refleja en el eje y
- __t__: texto
- lista erc para ver problemas/errores de el esquemático
- lista de componentes en el símbolo de bandera, además de mostrar las librerías
- __pitch__: distancia entre las patas que atraviesan la placa

## editor de placas en kicad

__7 capas importantes__

- __edge.cuts__: fibra con la que se hace la placa
- __f.cu y b.cu__: aplicar los dibujos de cobre por arriba y abajo
- __f silkscreen y b silkscreen__: dibujos en blanco sobre la placa
- __f mask y b mask__: carcasa negra de a placa, esmalte protector de cualquier placa

- coordenadas de el puntero en el mapa del editor de placas
  
## 14. atari punk console + variacion de proyecto - 01 en kicad

el esquema que hice esta basado en una de las variaciones del proyecto pasado, el cual era la incorporacion de un interruptor al circuito para variar el parlante

__esquematico final hecho en kicad__

<img width="715" alt="image" src="https://github.com/user-attachments/assets/9d5354af-04d2-4b84-9b90-760360470422" />

(R1 y R2 son resistencias experimentales en este caso LDR, despues de haberlo terminado me di cuenta que me falto la sigla al lado del valor valor del componente TT)

## 15. dudas + aprendizajes

__dudas__

- como puedo exportarlo a imagen o como exportarlo para que no pierda claridad y se mas facil de visualizar completo?
- como puedo organizar mejor la composicion del esquema en tanto a mover datos por ejemplo de la unidad del 555, lo que me complico fue tener que mezclar las conexiones que en un punto me costo bastante ver cual conectaba con cual

__aprendizajes__

- creo que aprendi una gran herramienta, quizas le tenia un poco de miedo ya que sea veia complicada pero en el proceso lo he encontrado bastante entretenido, ya que siento que estoy armando un puzle, y lo mejor de todo es que lo entiendo lo que veo y hago, asi que es realmente satisfactorio poder hacerlo con mis propias manos 👌

## 15.1 [noise toy](https://loudobjects.bandcamp.com/album/noise-toys) -  ___"manatees"___

  es una serie de sintetizadores listos para usar creados por el trío ___"loud objects"___, conocido por construir y programar su propio hardware de audio

___"noise toys"___ son versiones portátiles de los chips musicales que ___"loud objects"___ utiliza en sus actuaciones en directo, y están disponibles en cinco sabores sonoros diferentes, cada ___"noise toys"___ está programado con su propio patrón de sonido generativo de 1 bit, provisto de un interruptor de encendido basculante de estilo antiguo, dos botones que modulan el sonido y una toma de salida de audio

[___ejemplo de como funcionan en conjunto los "noise toys"___](https://www.physicaleditions.com/product/noise_toys)

el ___"noise toys"___ que me traje es la version ___"manatees"___ que fisicamente es igual a las demas versiones, haciendo la distintcion en el codigo para que pueda funcionar, los componentes que se pueden observar son un interruptor de encendido basculante de estilo antiguo, dos botones que modulan el sonido y una toma de salida de audio, no puse sacar otras especificaiones de los componentes, como valores por ejemplo, yaque la pagina la estan actualizando por lo que no pude acceder a caracteristicas mas detalladas

## acercamiento del ___"noise toys"___ + prueba hecha por mi

__componentes generales__
  
![acercamiento_01](https://github.com/user-attachments/assets/28879c5e-9d3f-4533-8e5f-52c364fff6d6)

__rueda para controlar volumen__

![acercamiento_02](https://github.com/user-attachments/assets/3f011f08-3708-4c9b-af82-4a08088163f8)

__placa por abajo__

![acercamiento_03](https://github.com/user-attachments/assets/fe3d780d-e441-4a1b-b97a-d59996cff720)

__componentes generales__

![acercamiento_04](https://github.com/user-attachments/assets/7d2e5e31-e00d-4f8a-8866-4f0f745f0517)

__funcionamiento__

https://github.com/user-attachments/assets/3825f748-96d2-4492-93df-75817617861c

tambien encontre una [guia](https://makezine.com/article/maker-news/how-to-build-the-noise-to/) que nos ayuda a crear un ___"noise toys"___ con detalle de compopnentes, y pasos a seguir para construirlo, que tambien incluye un cast con __"kick pearson"__ el creador de __"make electronic music"___
