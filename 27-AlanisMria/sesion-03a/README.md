# sesion-03a
*25 de marzo de 2025*

### Esquemático

- 0, 000000000001 = 1 p (pico)
- 0,000000001 = 1 μ (micro)
- 0,000001 = 1 n (nano)
- 0,001= 1 m
- 1x10 elevado a 0 = 1
- 1x10 elevado a 3 = 1000 K
- 1x10 elevado a 6 = 1.000.000 M
- 1x10 elevado a 9 = 1.000.000.000 G

![Imagen de WhatsApp 2025-03-25 a las 11 22 25_e963d055](https://github.com/user-attachments/assets/f729f5ba-8090-4adf-b151-31c289491d7d)

### Componentes 

. El último digito de un condensador es la cantidad de ceros que tiene 

. El condensador electrolítico negro: tiene polaridad, la cual esta demarcada por un costado blanco y una patita mas corta, indicando su lado negativo. tiene mas faradios.

. Condensador cerámico:parece una lenteja, la nuestra es de 470000.

![Imagen de WhatsApp 2025-03-25 a las 11 22 27_cbbcf66b](https://github.com/user-attachments/assets/fe17c839-1095-4f06-8c38-6dadb02766bf)

. Un condensador: almacena voltaje, hace que la caida del voltaje sea mas lenta.

. Chip 555: Es una caja negra que tiene 8 pins (datasheet manual), es un timer, lo usaremos para prender y apagar.

 Circuito planchado con cable de alambre

 Si al chip pasa mucha corriente se quema, por eso al conectarlo a positivo se debe usar una resistencia de 10k 

 pata 3: output

 Configuracion del 555 astable: no tiene ni un momento de estabilidad, por lo que es intermitente.

![Imagen de WhatsApp 2025-03-25 a las 11 22 31_a8b5c80b](https://github.com/user-attachments/assets/7491d502-fa3a-4db2-9db1-552694c33953)


 Calculadora de modo astable, que nos indica que el tiempo de encendido y apagado depender de el tamaño de las resistencias.

![Imagen de WhatsApp 2025-03-25 a las 15 45 36_6c78399d](https://github.com/user-attachments/assets/dcc6be51-914a-4d16-abe3-dcef4e2d7509)

 que es un potenciometro? una resistencia variable o un sensor de angulo

 usaremos el pin de en medio y uno mas

Esquemático chip 555 + led


![Imagen de WhatsApp 2025-03-25 a las 15 52 55_3075903c](https://github.com/user-attachments/assets/10b28ba2-4a00-4c12-a15e-b192963eefea)
![Imagen de WhatsApp 2025-03-25 a las 15 52 55_4319efa5](https://github.com/user-attachments/assets/d7f66600-db94-48c7-aca9-6b74e001755b)

Durante este ejercicio nos dimos cuenta de que el chip lograba que la energía que fluía a led oscilara, dependiendo de el valor de las resistencias que implementaramos en la conexión.
Circuito original
https://github.com/user-attachments/assets/b318b8ae-6df7-4903-8357-70d5f788e8f8

Circuito con potenciómetro

https://github.com/user-attachments/assets/54020300-a564-453b-88d3-b5d5267f52dc

Al implementar el potenciómetro en reemplazo de la resistencia que conectaba al pin 7 y 2, este nos permitío manipular la cantidad de energía que pasaba al led y de esta forma pudimos controlar la oscilación de energia y con esto dar distintos tiempos al encendido y apagado del led.

*Este chip se usa frecuentemente en la creación de temporizadores, generadores de pulso, alarmas, etc.*

### encargo06: cultura electrónica europea de los 1980s y 1990s

### Stereolab

- Stereolab es una banda anglo-francesa fundada en 1990 por Laetitia Sadier y Tim Gane.
- Mediante melodías y letras, en ingles y frances, mezclan ritmos como el rock, krautrock (corriente músical alemana y una de sus principales influencias), lounge, electronica, etc.
- Entre sus instrumentos se encuentran guitarras, teclados eléctricos, sintetizadores analógicos y cajas de ritmo vintage.

El disco que escuché fue *Refried ectoplasm [Switched On Volume 2]* de 1995, lo elegí porque la primera canción que escuche de la banda fue *French disko*, la cual se fue a mi playlist, este disco es de caracter recopilarorio, lo que explica el sonido y estilo variado.

A mi parecer durante todas sus canciones logran adentrarnos en un ambiente tranquilo, de letras y canciones cortas, bastante repetitivas en contenido vocal, pero no asi en composiciones, ya que estas se mantienen en su loop, pero sorprenden los distintos arreglos electrónicos o climax en instrumentos como la guitarra, lo que destaca la mayoria de las veces al final de la canción, cuando la voz ya se ha desvanecido.

Otra de mis canciones favoritas de este albúm fue *Revox* me encanta la manera en que la voz acompaña a los instrumentos en la primera parte y como la letra son simples palabras sueltas que para mi representan el flujo de una vida.

Me parece interesante como en ocasiones la melodía se superpone a la voz, sobre todo cuando la letra es repetitiva.

De alguna forma este albúm o la banda me recordó a *The breeders*?, no pregunten por qué, no lo se xd.

Parte del final de *Hexploding Head Movie* me recordó al fina de *Space odity* de David Bowie, como si hubieran tomado ese sonido y lo hicieran menos chirreante y mucho más de fondo.

La voz de la vocalista de verdad es muy francesa xd, no me refiero al acento, es su tono.

Muy bueno e inesperado el collage que se mandaron en *"Animal Or Vegetable [A Wonderful Wooden Reason...]" [Crumb Duck]*

Me gustó mucho *Sadistic* sobre todo la letra.

Fuente: <https://rincondesconexion.blogspot.com/2013/07/stereolab.html>

#### ¿Cúal es la diferencia entre un sintetizador analógico y uno digital?

La diferencia se encuentra en que los sintetizadores analógicos producen sonidos provenientes del voltaje circulante en circuitos eléctricos, lo que le daba un sonido inestable, pero con un caracter único, aspero y un tanto psicodelico, mientras que los digitales funcionan a travez de algoritmos que llegan a un procesador digital para lograr emular sonidos. 

Fuente: <https://soundsmarket.com/blog/diferencias-entre-un-sintetizador-digital-y-analogico>

#### Teclados eléctricos

- Tienen 61 teclas
- Son una evolución del piano eléctrico, (mucho mas pesados)

En este caso la banda utilizaba un Fariza compact duo, siendo este un tipo de organo popular en los 60s.
estos trataban de emular los sonidos de los organos Hammond, mediante sonidos generados por transistores que regulan el flujo de energia eléctrica.

También utilizaban el Moog Opus III live

Fuente: <https://nacionprogresiva.wordpress.com/2021/04/19/los-organos-hammond-farfisa-y-de-tubos-de-iglesia-en-la-historia-del-progresivo/>



