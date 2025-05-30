# sesion-12b

viernes 30 mayo 2025

### Fuentes de poder

Usamos baterías de 9v, lamentablemente son caras y contaminantes

Alternativa: Eliminador de voltaje o fuente de poder AC/DC

Powerbank, o más bien todo lo que usb-A o usb-B. Ojo con USB-C porque trabaja con otro estándar

También pueden usar pantallas solares como [éstas](https://listado.mercadolibre.cl/mini-panel-solar#D[A:mini%20panel%20solar]). Para cargar baterías de litio se requiere un aparato intermediario llamado [BMS](https://afel.cl/collections/cargador-balanceador) 

PILAS: AA, AAA, CR2032, etc

Considerar: 

- Voltaje: hay de 4,5; 5, 7, 9, 12, 15, 18, 25 VDC, etc... ESTAS SON DC, como una batería. Debe ser IGUAL al que espero que se utilice

- Polaridad: Si el centro es positivo o negativo

![dcsymbol](./archivos/dcsymbol.png)

- Tamaño del conector: centro de 2.1mm o 2.5mm

- Corriente: Recordar esta analogía: el voltaje se entrega, la corriente se pide. Siempre usar una fuente de poder de corriente MAYOR a la que quiero utilizar

### Iluminación

- Sabemos usar LEDS. Se queman. Son útiles para saber si algo está funcionando (si se usa en paralelo). Los encontramos en dispositivos electrónicos

- Ampolletas domésticas (220V), son peligrosas, hay que tener cuidado. Para controlarlas, usamos RELÉS

- LEDS de alta potencia. Requieren resistencias también de alta potencia. [Ejemplo](https://articulo.mercadolibre.cl/MLC-563818414-pack-10-led-high-power-3w-blanco-frio-sin-base-max--_JM)

- Cintas LEDS son controlables vía PWM y transitor acorde. Las cintas leds se pueden recortar, pero dependen de la cinta. Generalmente sus características eléctricas se calculan por metro. Tiras LED disponibles en [DEMASLED](https://www.demasled.cl/cintas-led)

- Muy probablemente requerirán transistores

- Muy interesante considerar aspectos aditivos de la luz [EJEMPLO](https://lorre-mill.com/spectrabloom)

### Motores

- Requerirán transistores

- Ya aprendimos a usar motores DC de 6v. Si le llega electricidad, gira. Tan rápido como pueda. Se aplica en juguetes, ruedas, ventiladores, vibradores.

- Si quiero motores DC que giren mas lento, debo buscar [motorreductores](https://afel.cl/collections/motorreductores), que cambian su velocidad por de giro por el principio de conservación del movimiento angular. Ejemplos: Arthur Ganson

- Steppermotor o Paso a Paso. Es mucho mas lento y preciso. Se utilizan en impresoras 3D. Funciona a partir de recibir pequeños pulsos eléctricos que activan ciertas regiones del motor. Analizar este [video](https://www.youtube.com/watch?v=Vc2XRVJ9n1o). OJO hay dos tipos de motores stepper, los unipolares y bipolares. Venden uno un unipoler en [AFEL](https://afel.cl/products/mini-motor-paso-a-paso-driver-board-uln2003?_pos=2&_psq=motor&_ss=e&_v=1.0)

- SERVOMOTOR: Se suele utilizar con Arduino. Sabe donde está, es preciso, y puede ser rápido. Es a veces inestable

- Puente H. Permite cambiar la dirección de un motor DC. Se genera con 4 switches, 4 transistores, o con un circuito integrado llamado L298n [ejemploe](https://mcielectronics.cl/shop/product/controlador-de-motores-puente-h-l298n-25508/)

- Solenoides. Por principio electromagnético (Henry-Faraday, principio de inducción), genera movimiento lineal. Se usa en percusiones electromecánicas y en chapas electrónicas. Se usan para controlar también [líquidos](https://afel.cl/products/valvula-solenoide-12v-1-2-n-c).

- Bomba de agua o de aire https://afel.cl/products/mini-bomba-de-agua-sumergible-120l-h?_pos=1&_sid=1ab36901a&_ss=r

### Transistores

- Se usan como amplificador, como switch, como inversor, o como compuerta lógica

- Hay principalmente dos tipos: BIPOLARES y FET

- Ejemplo bipolar: 2n2222

- Ejemplo MOSFET: IRFZ44n

- Ejemplo transistor modo inversor: https://es.wikipedia.org/wiki/Puerta_NOT

### Sonido

- Parlantes activos y pasivos. Activos se enchufan. Pasivos no, ya que requieren amplificación externa, como el PAM8403. Su intensidad sonora depende de su tamaño (en pulgadas), de su potencia (en watt), de su impedancia (en ohm)

- Buzzers. Son parlantes muy básicos, principalmente usados como señal de alarma o aviso. Pueden sonar MUY fuerte

- Reproductor de audio. Convierte datos digitales en electricidad sonora [ejemplo](https://afel.cl/products/modulo-reproductor-mp3-con-lector-micro-sd-y-usb?_pos=4&_sid=7d96bb1d9&_ss=r)

- Micrófonos. Convierte sonido (mecánica) en electricidad. Inverso a un parlante. El más usado es el Electret en nuestro contexto. [ejemplo](https://altronics.cl/microfono-electret-max4466)

- Micrófono piezoeléctrico. Convierte vibración mecánica (sobre materiales) en electricidad. Investigar [Fenómeno piezoeléctrico](https://es.wikipedia.org/wiki/Piezoelectricidad)

- Sintetizadores. Generan sonido a partir de señales eléctricas creadas dentro del mismo aparato. Curso básico [Logic Noise](https://hackaday.com/2015/02/04/logic-noise-sweet-sweet-oscillator-sounds/), intermedio [Moritz Klein](https://www.youtube.com/watch?v=Xbl1xwFR3eg)

- Pedales de guitarra [Muchos kits en Tonepad](http://www.tonepad.com/projects.asp?projectType=fx)

### Referentes

- [Kickstarter](https://www.kickstarter.com/)

- [Hackaday](https://hackaday.com/)

- [Adafruit](https://www.adafruit.com/)

- [Crowd Supplt](https://www.crowdsupply.com/)

- [Etsy](https://www.etsy.com/search?q=synth&ref=search_bar)

- [Tindie](https://www.tindie.com/)

## encargo-30

- Describir 3 proyectos de máquinas electrónicas que quieran hacer de forma individual, ordenar por preferencia o interés. 


## encargo-31

- Dibujar diagrama de comportamiento, flujos de interacción. No específicar chips. Considerar procesos de manera especulativa. ¿Cuánto tiempo se usará? ¿Qué encendidos y apagados tiene? ¿Cómo se interactúa?