# sesion-10a

## Trabajo en clase

### Cosas que hablamos en la mañana

- nos habló Misa de su tesis de Magíster que va a presentar en la Facultad de Arte, Arquitectura y Diseño de la Universidad de Chile, en donde modificó discos duros para que sonaran como parlantes.
- conversamos de cosas buenas que nos hayan pasado en el fin de semana, también hablamos y escuchamos a Trueno.

### Circuito PWM

- la modulación por ancho de pulsos (Pulse width Modulation PWM) de una señal es una técnica en la que se modifica el ciclo de trabajo de una señal periódica, para controlar la cantidad de energía que se envía a una carga.
- fuente <https://www.facilelectro.es/que-es-el-pwm-y-como-funciona/>
- armar un circuito PWM por persona, y juntarse entre tres, utilizando colores diferentes: LED rojo, verde y azul, para luego probar cómo se mezclan los colores bajo un papel.
- el color azul no logra apreciarse tan bien, ya que no alcanza su máxima luz. hay que bajarle la resistencia para que pase más corriente y por tanto, brille más.

![tme-sesion10a-proto](https://github.com/user-attachments/assets/4656d376-2ce7-4d12-bcec-493906d7b1bb)

### Circuitos en Minecraft y Falstad

- si trasladamos los componentes electrónicos y los convertimos en elementos del Minecraft, la batería podría ser un bloque de redstone o una palanca; el LED podría ser una lámpara de redstone; los cables serían polvo de redstone, y el diodo un repetidor de redstone.
- el Redstone compara cuánta redstone hay en una parte con la de al lado, se "pregunta" cuál es la fuerza de la señal de redstone y según eso decide si deja pasar la señal o no.
- realizamos una simulación de circuito en <https://www.falstad.com/circuit/circuitjs.html>
- vimos divisores de voltaje, que son una manera de convertir resistencias en voltaje, dividiendo su valor. si queremos dividir el voltaje a la mitad, ponemos dos resistencias del mismo valor, siempre que el potenciómetro sea lineal.
- el potenciómetro tiene tres terminales: un extremo va a los 9 volts, el otro extremo a los 0 volts, y el terminal del centro entrega un voltaje intermedio.
- con estos umbrales podemos crear proyectos que actúen en función de ellos y que dependan del contexto. también nos ayuda poder manipular esos umbrales. por ejemplo, un circuito que se active cuando el espacio se encuentre en silencio, pero si está en un lugar lleno de gente donde el silencio no llega a ser el mismo, entonces el umbral se modifica.
- el operacional le da impulso a los electrones; funciona como un buffer, un espejo de electrones.

![tme-sesion10a-falstad01](https://github.com/user-attachments/assets/344f322d-4e13-43c4-b820-31ec1fc6c300)

![tme-sesion10a-falstad02](https://github.com/user-attachments/assets/53a3e9ec-0d25-415b-a476-4065cefae7d3)

![tme-sesion10a-falstad03](https://github.com/user-attachments/assets/fa746476-71a3-4898-afc3-a1120c16fc35)

![tme-sesion10a-bitacora](https://github.com/user-attachments/assets/6ae67461-1d70-4faf-8dbd-e621840bb018)

## Encargo

### 20-Pantallas de siete segmentos

- subir fotos de su propia autoría de pantallas de siete segmentos, y otras variantes que encuentren en su vida cotidiana.

### 21-Simulación de circuitos con 555 y/o comparadores hechos con opamps en Falstad

- simular circuitos que hemos visto en clases con chips 555 y/o circuitos comparadores usando el simulador de Falstad.
