# sesion-12a
    
27-05

- tutoriales que asumen que no sabes nada <https://www.w3schools.com/>
- Juan Downey
- "los transistores tienen muchas mañas"
    transistores: 
            - Bot
            - Fet
                - jeet
                - mosfet

- **nosotros estamos haciendo modularización** pensar en las cajitas negras "no quiero un 555, quiero un semáforo"
- "este proyecto hace estas cosas en esto contexto"
- para cambiarle el nombre dentro de github --> abrir imagen --> editar 
![editar nombre de archivo](.\archivos\editarNombreArchivo.png)

- **para modificar el tamaño de la imagen debe ser en html (en w3schools)** 
    - 3 parámetros:
        - src: donde vive la foto (.\archivos)
        - alt: texto alternativo
        - width: ancho - hay muchas unidades de medida
    - <img src=".\archivos\w3schools.png" alt="w3school" style="width:300px;height:100px;">
> ponte las pilas ordenando los apunteeeess! 😡

- [datasheet 4017](https://www.ti.com/lit/gpn/CD4017B-MIL)
    - 4017 cuenta hasta 10
    - 4022 cuenta hasta 8
    - mínimo 3 volt (2 pilas AA) máximo 18 volts (2 baterias de 9v)
    - diagama de tiempo (el enredado es un diagrama lógico y el otro diagrama de tiempo) 
    ![diagramadetimepo](.\archivos\diagramaTiempo.png)

    - compuerta AND - condicionales
![compuerta AND](.\archivos\compuertasAND.jpg) 

    - Cascading "uno tras otro" como las7 tazas

# detector de sombra "celebrador de sombra. hay una sombra 'me encanta, like'" *aarón*

**con calma, parte por parte**

detector de sombra --> temporizador --> secuencia

### etapa 1: LM324 --> OP-Amp (5 o 9v) **desacopla** "resume y hace que las cosas no se pescan tanto" 
   
    - la patita 3 es señal [LDR]
    - 2 para definir **umbral** [pote]
    - ambass generan una señal enviada hacia el pin 1 [LED]

### etapa 2: 555 --> temporizador

    - capacitor del pin 6 y 7 es el tiempo monostable, se puede cambiar. primero intenté con el 10uF y después el 100uF - la secuencia de luces de la etapa 
        - 10uF se enciende cuando el del LDR se apaga y se apaga cuando el del LDR se enciende 
        - 100uf se demora 2-3 segundos en apagarse (a no ser que haya sombra)
        - capacitor del pin 5 da igual

### etapa 3: 4017 --> seguenciador

    - poner un condensador de 100uF en el 555
    - poner un condensador de 10uF en el pin 16 y el negativo


