# sesión-12a

*27 de mayo de 2025*

Estamos modularizado.

Buscar en manual de data sheet info sobre el chip 4017

Link: https://n9.cl/q3ln8g

![dataSheet4017](https://github.com/AlanisMria/dis8644-2025-1/blob/main/27-AlanisMria/sesion-12a/archivos/dataSheet4017.png)

En este manual aparecen los límites de alimentación, los cuales son 3v mínimo y 18v máximo.

Compuerta and pregunta qué es la a y que es la b y si ambas se cumplen pasa el mensaje

Contiene el aspecto físico del chip.

Tenemos hasta el 10 de junio para hacer correcciones de nuestras bitácoras y publicar un issue.

A los archivos subidos en la carpeta de github se les puede cambiar el nombre desde la carpeta.

Cuando las fotos se suben en html se puede modificar el tamaño.

Vamos a conectar 3 módulos , avanzaremos por parte y haremos un detector de sombra.

1. el circuito detectara la sombra
2.  la detección de sombra pasará por un temporizador, para que la señal dure
3.  pasara por un secuenciador SEQ que sería el 4017

aplicaremos un amplificador operacional cuadruple lm324 opam
en la pata 3 se conecta un ldr una resistencia de 10k

![circuitoDetectorDeSombra](https://github.com/AlanisMria/dis8644-2025-1/blob/main/27-AlanisMria/sesion-12a/archivos/circuitoDetectorDeSombra.png)

## Proceso 

En este circuito es importante conectar las 3 terminales del potenciómetro.

![detalleLm324](https://github.com/AlanisMria/dis8644-2025-1/blob/main/27-AlanisMria/sesion-12a/archivos/detalleLm324.jpg)
![detalle555](https://github.com/AlanisMria/dis8644-2025-1/blob/main/27-AlanisMria/sesion-12a/archivos/detalle555.jpg)
![detalle4017](https://github.com/AlanisMria/dis8644-2025-1/blob/main/27-AlanisMria/sesion-12a/archivos/detalle4017.jpg)

Afinar el sensor exponiendolo a un umbral de luz más grande 

Al probar si funcionaba la parte 3 del circuito con el chip 4017 notamos que nos faltaba conectar los pines superiores, específicamente el 10 con el 15 y el 13 con una resistencia de 100k a GN

En nuestra última versión especulamos que el led que se encienda depende de la cantidad de veces que se detecte una sombra en una frecuencia determinada.

![probandoSensor](https://github.com/AlanisMria/dis8644-2025-1/blob/main/27-AlanisMria/sesion-12a/archivos/probandoSensor.mp4)

![resultadoFinal](https://github.com/AlanisMria/dis8644-2025-1/blob/main/27-AlanisMria/sesion-12a/archivos/resultadoFinal.mp4)
