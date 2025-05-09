# ⋆₊˚⊹♡ Clase  09b - Receso de clases ♡⊹˚₊⋆

_Viernes 9/05/2025_

***

## Observaciones

<!---Recordar para programar "md" (markdown): 
- https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet 
- https://www.markdownguide.org/basic-syntax/--->

La clase comenzó con referentes y referencias: Gordon Matta-Clark, entre otros.
Tras hablar de la posición en la universidad en el mundo (según varios rankings). 
Conversamos sobre los primeros auxilios psicológicos y algunos hablaron de sus logros y cosas buenas que habían pasado en la semana, en conjunto a los profes.
Tras ello nos quedan las últimas 7 semanas de clases. Vamos a usar nuevas piezas para aprender a usarlas

***

## Bitácora digital

### Parte 1: Piezas nuevas traídas a la clases

<br>

- [PAM 8403](https://afel.cl/products/amplificador-stereo-clase-d-2x3w-pam8403?srsltid=AfmBOoq8AjxWD2ZoGiEjyWEiV9xWqypejVilDozwdgQ8L9h4xyjweiaL): Es un módulo y amplificador digital dual relacionado al audio. Usa tecnología SMD (todo soldado por un lado, hecho por una máquina). 
  
- [RELE de 01 Canal](https://afel.cl/products/rele-de-01-canal): Un Relé (en inglés Relay) es una pieza electrónica que funciona como un interruptor controlado por la energía presente en un circuito electrico. Esta pieza posee una bobina (almacena energía de forma pasiva) y un electroimán (requiere de bobina para funcionar, permitiendo prender o apagar según la presencia de corriente).  Su funcionamiento permite encender u apagar secciones de un circuito y controlar la potencia que ingreso, pudiendo considerarse un amplificador eléctrico. Existen variedades de relés en el mercado.

Con estas piezas en mano nos disponemos a recordar los conocimientos relacionados con el chip 555: astable (estado variable constante) y monoestable (estado permanente hasta que se perturbe).

Power Supply (ps, una batería)

Modularidad. 

<br>

Una vez descargada exporté todos los documentos para poder analizar las partes que componen dicho documento.

#### Archivo diagrama

<br>

![image](https://github.com/user-attachments/assets/1d75f11d-24b3-47ab-bf4b-419806a514bf)

_▼ Captura del diagama_

![image](https://github.com/user-attachments/assets/89d3fa22-9fe0-4084-8983-71362949c108)

_▼ Captura de las huellas del archivo_

<br>

**Análisis:** En comparación con el esquema realizado en clases, a este se les añadió 4 perforaciones (MountingHole) númeradas del H1 al H4. Las huellas de estas piezas son "MountingHole_3.2mm_M3". Por lo que pude apreciar, no es necesario que estos elementos se encuentren posicionados en una parte en específico (no como en la placa PCB). Fuera de eso, el circuito es similar al que realizamos la clase pasada.

<br>

#### Archivo PCB

<br>

![image](https://github.com/user-attachments/assets/1eeafae9-e1a3-48ab-a9e8-1bb8bc84d94d)

_▼ Visualización completa de la placa. Se observa una sobreposición de los elementos delanteros con los de atrás_

<br>

![image](https://github.com/user-attachments/assets/d0e02dd7-7054-48a4-9e6f-41f502c87625)

_▼ Visualización de la parte frontal (F.) de la Placa (Cu, Silkscreen, Mask, Edge.cuts, Courtyard, Fab)_

<br>

![image](https://github.com/user-attachments/assets/ccf3fa42-4a23-4081-9ff4-391ff9d46601)

_▼ Visualización de la parte trasera (B.) de la Placa (Cu, Silkscreen, Mask, Edge.cuts, Courtyard, Fab)_

<br>

**Análisis:** La placa se ve completa y separada por cada parte. Los esenciales son los conectores de Cu (cobre), los cortes de los bordes (dimención del circuito) y los agujeros por donde entrarán las piezas. Sin estos el circuito como tal no sería funcional. Los demás parametros ayudan a generar una guía para sabe en qué lugar se instala qué pieza, para darle un sentido de identidad y estética, entre otros.

<br>

#### Simulación en 3D

![image](https://github.com/user-attachments/assets/da022933-a232-4cbb-bcba-57e27ec1fce3)

_▼ Visualización de la parte frontal_

<br>

![image](https://github.com/user-attachments/assets/70a61d89-3d09-44f1-a958-a4ec43d4da33)

_▼ Visualización de la parte trasera_

<br>

**Análisis:** Usando esta herramienta se puede ver una aproximación del resultado final antes de mandarlo a fabricar. Es la última oportunidad para poder realizar observaciones y cambios tanto en los componentes como en el circuito como tal.

<br>

***

### Parte 2: Programas, páginas, herramientas para poder trabajar desde el PC

<br>

**- [OPENSCAD](https://openscad.org/) -**

Es un software CAD (Computer-Aided Design), es decir, un software de diseño asistido por ordenador. ["Esta tecnología permite la agilización del trabajo, automatizando los procesos manuales del proceso de diseño de producto, reduciendo errores, ganando velocidad y aumentando la calidad"](https://9altitudes.es/aprende-y-conecta/articulos/que-es-cad-para-que-sirve-y-que-ventajas-tiene#:~:text=El%20software%20de%20dise%C3%B1o%20asistido,y%20tridimensionales%20de%20objetos%20f%C3%ADsicos). 

En este caso, OpenScad es un programa gratuito y de código abierto (cualquiera puede inspeccionar, modificar y mejorar el código fuente) enfocado en ["la creación de modelos 3D mediante la programación. Los usuarios tienen el control total sobre el proceso de modelado, permitiendo modificar cualquier paso en cualquiera de las etapas del modelado, o crear diseños definidos mediante parámetros configurables"](https://www.3dnatives.com/es/openscad-modelador-3d/#!).

<br>

**- [MAKER WORLD](https://makerworld.com/es) -**

Es un sitio web colaborativo u portal comunitario creado por "Bambu Lab". Este funciona como una especie de repositorio en el que tanto "Creadores de modelos 3D" como "consumidores" pueden interactuar con Expertos dedicados al sector del modelado y la impresión 3D para poder conseguir los mejores resultados, independiente si se trata de forma virtual (programas, herramientas, errores, etc) o de forma física (enfocados en las impresoras y máquinas). Son muchas las formas de prestar ayuda a quien acude al sitio, reduciendo las barreras técnicas.

El fundamento de la creación de esta web es ["La idea de unir las fuerzas de diseñadores, expertos en laminación, proveedores de filamentos y consumidores. Esta colaboración garantiza que no solo los modelos, sino también el conocimiento sobre la laminación y la alegría de la creación se compartan dentro de la comunidad".](https://www.impresoras3d.com/makerworld-el-portal-comunitario-de-bambu-lab/#:~:text=MakerWorld%20se%20basa%20en%20la,compartan%20dentro%20de%20la%20comunidad.)

<br>

**- [GitHub CLI](https://cli.github.com/) -**

   (descargar carpetas de Github)

- https://github.com/oskitone/poly555 (Oskitone - proyectos con cada pieza)

<br>

***

#### Oportunidades: Google Summer of Code 2025 

https://summerofcode.withgoogle.com/

<br>

***

### Salida a terreno independiente: Tiempo de decaimiento temprano

Exposición realizada por el Núcleo de Artes Sonoras: Mónica Bate, Jorge Cabieses, Rainer Krause, Francisco Sanfuentes, Matias Serrano, Lucas Soffia.



▼ Este es un texto.

<br>

***

### Posdata

La clase tuvo mucho contenido de golpe, me maree de escuchar y saltar de un lado a otro. Me pondré al día cuando se suba el video. (っ- ‸ - ς)

***

°˖✧◝(⁰▿⁰)◜✧˖°
