# sesion-12b

30-05-2025

## resumen de componentes

### fuentes de poder

- batería 9v
- power bank
- pilas 1,5
- pilas reloj (2032 3v) *estas van en un socket*
- fuente de poder: esta debe ser mayor a lo que quiero utilizar *cuidado ya que existen jack de 2.1 y 2.1*

### luces

- puede variar la intensidad y la potencia, son programables.
- leds, siempre con una resistencia *poner en paralelo para ver si funcionan*
- leds de alta potencia
- tiras led/cintas led *existen varios tipos*

### motores

- algo que regula las revoluciones
- necesitaran transistores
- Dc 6v, gira tan rápido como pueda, si necesito cambiar la dirección, cambio las entradas *motoreductores se utilizan para bajar la velocidad de giro*
- steppermotor o paso a paso genera un movimiento mucho más lento y controlado, reciben pulsos eléctricos y esto genera el movimiento *existen unipolares y bipolares*
- solenoides genera movimiento lineal *se puede controlar líquidos*
- bombas de agua o aire
- puente h: si enciendo s1 y s4 se mueve hacia la derecha, si prendo s3 y s2 se mueve hacia la izquierda *también existe uno que viene listo*
  
![puenteh](https://lh4.googleusercontent.com/m0OLxiwguWzEd33R-OGEHfscX-0e3Wt27qG8bt0kE5mICrIEh3LOHTCvfAH9okuCQfiPnl1Dq4NYgxSLwYPa_B0PHkzTSeMHQWW5n3U3nx_k958ozikYdW90RbX1V4PMGxVdMCB9yaPRRYx5Kui-_w)

[mcielectronics.cl-puenteh](https://cursos.mcielectronics.cl/2022/08/05/que-es-un-puente-h/)


### transistores

- se usa como amplificador o switch
- bipolares *2n2222*
- fet *IRFZ44N*

### sonido

- parlante activos *se enchufan*
- parlante pasivos *requiere amplificación*
- buzzers *zumbador*
- reproductor de audio *datos a electricidad*
- micrófonos *sonido en electricidad*
- sintetizadores 

### referentes

- gijsgieskes
- tristian perich
- arthur ganson
- javier bustos
- audiomaquinas
- polyend
- gabriel holzapfel
- monica bate
- logic noise
- tonepad
- kickstarter
- hackday
- tindle
- etsy

## encargo-24

- Describir de forma textual 3 proyectos de máquinas electrónicas que quieran hacer de forma individual, ordenar por preferencia o interés de que sea desarrollado.

1. __máquina interactiva con parlantes, buzzer y vibrador ocultos__. objeto del tamaño de una mano que emite sonidos y vibraciones diversas según el punto de contacto y su conexión interna.
2. __máquina de dibujo aleatorio__. un motor mueve un lápiz sobre papel, generando trazos variados según diferentes opciones de velocidad y periodos de movimiento.
3. __conductividad del agua__. según sonidos generados electrónicamente, estos se transmitirán a través del agua, permitiendo visualizar y experimentar la electrónica.

## encargo-25

- Dibujar diagrama de comportamiento, flujos de interacción. No específicar chips. Considerar procesos de manera especulativa. ¿Cuánto tiempo se usará? ¿Qué encendidos y apagados tiene? ¿Cómo se interactúa?

### 1. máquina interactiva con parlantes, buzzer y vibrador ocultos

el objeto está en reposo → tocar y presionar → vibración, sonido → cada zona tiene una respuesta.

ejemplo de respuesta: tonos graves, agudos, mayor y menor periodo, entre otros.

- exploración: el usuario empieza a probar combinaciones e identificar qué sonidos provienen de cada interacción
- reposo: depende de la interacción. si el objeto deja de recibir señales, entra nuevamente en reposo.
- tiempo estimado de uso: ya que el uso es espontáneo , su duración varía según la curiosidad del usuario, en promedio 5 minutos.

### 2. máquina de dibujo aleatorio

- estado inicial: la máquina está en reposo al igual que el lápiz, esperando a recibir una señal.
- inicio de uso: el usuario coloca una hoja en la base y presiona un botón para activarla. el motor comienza a mover el lápiz, así el trazo aparece en el papel.
- interacción: durante el dibujo, el usuario puede intervenir modificando parámetros como velocidad, intensidad, o duración mediante botones, potenciómetros o LDR. cada intervención cambia el trazo.
- finalización: la máquina se detiene y el usuario retira la hoja, observa el resultado que se creó gracias a la electrónica.
- tiempo estimado de uso: en promedio 2 minutos, aunque invita a seguir experimentando con otros parámetros.

### 3. conductividad del agua

- estado inicial: el agua se encuentra en estado de reposo y el circuito está listo para la interacción.
- inicio de uso: el usuario comienza a interactuar con el circuito, las luces led se encienden y el agua comienza a vibrar según los tonos producidos por la interacción.
- exploración: el usuario experimenta con distintas cantidades de agua, también experimenta con la diversidad de sonidos que se pueden generar gracias al circuito, cada cambio modifica la respuesta.
- reposo: cuando el usuario deja de presionar el circuito, el agua vuelve a un estado de reposo.
- tiempo estimado de uso: en promedio, 5 minutos. pensado como una exploración.
