### sesion-06a

## Entrega Proyecto 01: 

#LDA: Light Dependent Awelita

# Premisa:

- Elegir Temática

- Definir Usuario
 
- Definir Función

## Elegir Temática: 

<https://www.555-timer-circuits.com>

![Foto de los ejemplos que más nos gustaron(las4 en una misma foto)](tme-p1-circuitos.png)

Miramos los distintos ejemplos en esta página, y destacamos los que más nos llamaron la atensión.


![Foto esquemático original del pryecto dark detector](tme-p1-esquemaDark.png)

<https://www.555-timer-circuits.com/dark-detector.html>

 Este proyecto consiste en un circuito que sensa la luz a través de un LDR. Una alarma se activa cuando el nivel de luz detectado es menor a cierta cantidad determinada por la configuración del sistema.

## Definir Usuario:

![Foto user persona](tme-p1-user.png)

USER PERSONA


- Nombre: Gloria Fernández 
- Edad: 89 años
- Género: Femenino
- Estado civil: Viuda
- Ciudad: Chillán

Biografía: 

Gloria vive una casa con su hijo, su nuera y sus dos nietos. Trabajó de como educadora de párvulos hasta los 72 años. Todos los días desayuna entre las 10:30 y las 12:00, almuerza entre las 13:30 y las 16:30, y toma once entre las 19:30 y las 22:00. el horario en el que realiza sus *hobbies* va desde las 14:00 hasta las 21:30.

Motivación:

Busca realizar actividades que la ayuden a distraerse y a hacer que el tiempo pase más rápido. puede pasar horas entretenida con actividades como leer, tejer, bordar, armar rompecabezas y resolver sopas de letras.

## Definir Función a Partir de la Problemática: 

Problemática: 

Identificamos una problemática en aquella situación cuando una persona, en este caso un adulte mayor, realiza actividades que requieren concentración, durante extensos periodos. Cuando estos períodos coinciden con la puesta del sol, el usuario sigue realizando su actividad a oscuras.

Esto ocurre porque la disminución de la luz es paulatina, y sucede a una velocidad que permite que nuestro ojo se vaya acostumbrando a ella automáticamente. Por eso a veces pareciera que oscureció de golpe en la noche 

![Figura 1.13 del archivo retinaAdaptTesis.pdf](tme-p1-tesisF1.13.png)

<https://uvadoc.uva.es/handle/10324/22376>

Si bien, no hay estudios que comprueben que hacer atividades a oscuras dañe la vista, hacer actividades a oscuras requiere un mayor esfuerzo, por lo tanto te cansa más y dificulta hacerlo por períodos prolongados.

Definición Función: 

![Figura 1.13 del archivo retinaAdaptTesis.pdf](tme-p1-alarmaNoche.png)
Imagen generada por Ia mediante chatGPT

Un objeto que cuando se oscurezca emita una alarma para alertar al usuario, y que este recuerde encender una luz para que no suene. Esta alarma sonará durante 300s y después el istema se suspenderá hasta que vuelva a detectar luz.

# Diseño: 

## Investigación 1: Iluminación

![foto de algo con luz ahaha.pdf](tme-p1-fotoLuz.png)

<https://pin.it/83V7VnPhr>

La luz es un fenónemo que scede como efecto secundario de la radiación electromagnética. Esta es percibida por el ojo humano dentro de un espectro visible con longitudes de onda entre 380 y 750mm.

<https://es.wikipedia.org/wiki/Luz>

La intensidad de la luz se mide en lúmenes(lx), se mide con un instrumento llamado luxómetro.

Para trabajar / leer se recomiendan entre 300-500lx

| Ejemplo de valores lux         |            |
|--------------------------------|------------|
| Luz solar                      | 40.00 lx   |
| Lugar de trabajo en la oficina | 300-500 lx |
| Sala de estar                  | 50-200 lx  |
| Noche de luna                  | 0,3 lx     |
  
## Investigación 2: ¿Cómo lograr que suceda?

Podemos seprar en 2 nuestros objetivos del funcionamiento electrónico del objeto:

- Emitir sonido cuando sense

- Que el sonido no sea permanente

Para cada uno de los objetivos que tenemos ya tenemos un circuito conocido.

Con el circuito  Dark Detector podemos hacer que el cirtuito emita una alarma cuando haya poca luz.

![Foto esquemático original del proyecto dark detector](tme-p1-esquemaDark.png)

Con el circuito monoestable podemos lograr que cuando se recibe un estímulo, este quede corriendo durante un tiempo y después apagarse.

![Foto esquemático original del circuito monoestable](tme-p1-esquemaMonoestable.png)

La idea es "fusionar" ambos circuitos para lograr que la parte del Dark Detector(A) "controle" a la parte monoestble (B)

![Foto esquemático dibujo parte A](tme-p1-esquemaFusionA.jpeg)

![Foto esquemático dibujo parte B](tme-p1-esquemaFusionB.jpeg)

![Foto esquemático dibujo fusión](tme-p1-esquemaFusion.jpeg)

## Redefinición

Tras múltiples intentos no logramos

![Foto esquemático intento fallido tinker](tme-p1-tinkerTry1.png)

![Foto esquemático otro intento fallido tinker](tme-p1-tinkerTry2.png)

Tras no lograr llevar a cabo la idea original, decidimos optar por quedarnos con la parte que teníamos funcionando.

![Foto esquemático del circuito que tenemos realmente](tme-p1-esquemaLdaReal.png)

![Foto del flujo real](tme-p1-flujoReal.png)

![Foto esquemático del circuito que queríamos tener](tme-p1-esquemaLdaIdeal.png)

![Foto del flujo que queriamos que fuera](tme-p1-flujoIdeal.png)

# FABRICACIÓN: 

## Cables:

En esta etapa tomamos medidas de los componentes, y los tuvimos en cuenta para el diseño de la carcasa

## Carcasa: 

Hicimos un modelo 3D mediante Rhinoceros 3D

![Foto donde aparezcan varias fotos de proceso del modelado 3d](tme-p1-modeladoProceso.png)

![Foto del modelado 1](tme-p1-modelado.png)

![Foto del render](tme-p1-render.png)

Impresión 3D

![Foto de la impresión comenzando](tme-p1-imp1.png)


![foto de la impresión al 40%](tme-p1-imp2.png)

![foto de la impresión fallando](tme-p1-imp3.png)

![Foto de la impresión lista](tme-p1-imp4.png)

![Foto de la los soportes sacados](tme-p1-imp5.png)
