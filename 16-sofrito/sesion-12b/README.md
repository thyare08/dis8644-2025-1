# sesion-12b
30/05/2025

y2k o problema del año 2000: fue un bug o error de software causado por la costumbre que habían adoptado los programadores de omitir la centuria en el año para el almacenamiento de fechas (generalmente para economizar memoria), asumiendo que el software solo funcionaría durante los años cuyos números comenzaran con 19.

web 2.0: se refiere a una evolución de la web en la que se promueve la interacción y la colaboración entre usuarios.

net art: obras de arte creadas específicamente para internet y que utilizan la red como un medio principal.
https://art.teleportacia.org/olia/summer/ 

posternura records: https://posternurarecords.cl/

sonic pi: página de live coding, gratis y sirve para codificar composiciones musicales. https://sonic-pi.net/

vst (Virtual Studio Technology): software que interpretan midi y lo convierten en sonido.

arturia pigments: software todo en uno para sintetizadores. https://www.arturia.com/es/products/software-instruments/pigments/overview

primavera hacker: es un encuentro gratuito en torno a las relaciones entre tecnología, política y cultura, un festival de dos días para reflexionar, desde distintos ángulos, sobre el rol de la tecnología en la sociedad actual. https://phacker.org/

joshua: teenager vs superpower, es un documental sobre activismo y tensiones políticas en Hong Kong.

## fuentes de poder
Batería 9vl, son caras y contaminantes

Fuente de poder ac/dc: convierte la corriente alterna en corriente continua 

Considerar: 

- Voltajes: Hay de 4,5; 5, 9, 12, 15, 18, 25, VDC, etc. Estas son DC igual que la batería.

- Polaridad: Si el centro es positivo o negativos

- Tamaño del conector

- Corriente: el voltaje se entrega, la corriente se pide, siempre usar una fuente de poder mayor a la que quiero utilizar.

- Pilas: tienen un volataje de 1.5. Las de reloj entregan 3vol.
  
**Gijs Gieskes -  utiliza pantallas solares como baterías**

### Iluminación

- Leds: Son útiles para saber si algo está funcionando (si se usan en paralelo). Se queman. Se pueden encontrar enAmpolletas dispositivos electrónicos.
  
- Ampolletas: Domésticas (220v), son peligrosas, para controlarlas se usa un relé.
  
- Leds de alta potencia (3 o 5w).
  
- Tiras led: llega la corriente desde el enchufe y una salida pwm. Son controlables vía PWM y transistor acorde. Las cintas led se pueden cortar, pero depende de la cinta. Sus características eléctricas, se calculan por metro.

### Motores 
Muy probablemente requerirán transistores.

- Si le llega electricidad gira tan rápido como pueda.
  
- Para que gire más lento, se debe buscar motoreductores, que cambian su velocidad por el principio de conservación del movimiento angular.
  
- Steppermotor:  Es mucho más lento y preciso. Se utilizan en impresoras 3D. Funciona a partir de recibir pequeños impulsos eléctricos  que activan ciertas regiones del motor.
  
- Servomotor o paso a paso: Se suele utilizar con arduino. Sabe donde está, es preciso y puede ser rápido. A veces es inestable.
  
- Puente H: Permite cambiar la dirección de un motor DC. Se genera con 4 switches, 4 transistores, o con un circuito integrado llamado l298n.
  
- Solenoides: Se pueden usar para hacer música. Por principio electromagnético (henry-faraday), genera movimiento lineal. Se usa en percusiones electromecánicas y en  chapas electrónicas. Se usan también para controlar líquidos.
  
- Bomba de agua o de aire

### Transistores
- Se usan como amplificador, como switch,como inversor o como compuerta lógica.
  
- Hay principalmente dos tipos: Bipolares y FET
  
- Ejemplo bipolar: 2n2222
  
- Ejemplo MOSFET: IRFZ44n
  
- Ejemplo transistor: modo inversor

### Sonido
- Parlantes activos y pasivos. Activos se enchufam. Pasivos no, ya que requieren amplificación externa, como el PAM8403. Su intensidad sonora depende de su tamaño (en pulgadas), de su potencia (en watt), de su impedancia (en ohm).
  
- Buzzers: Parlantes muy básicos, principalmente usados como señal de alrma o aviso. Puede sonar muy fuerte.
  
- Reproductores de audio: Convierte datos digitales en electricidad sonora.
  
- Micrófono: Convierte sonido (mecánico) en electricidad. Inverso a un parlante. El más usado es un electret en nuestro contexto.
  
- Piezoeléctrico: Convierte la vibración mecánica en energía electrica.
  
- Sintetizadores: Generan sonido, a partir de señales eléctricas creadas dentro del mismo aparato.
  
- Pedales de guitarra.

### Referentes 
- Kickstarter
  
- Hackaday
  
- Crowsupply
  
- Etsy  

## encargo-24
Describir de forma textual 3 proyectos de máquinas electrónicas que quieran hacer de forma individual, ordenar por preferencia o interés de que sea desarrollado.
## encargo-25
Dibujar diagrama de comportamiento, flujos de interacción. No específicar chips. Considerar procesos de manera especulativa. ¿Cuánto tiempo se usará? ¿Qué encendidos y apagados tiene? ¿Cómo se interactúa?



