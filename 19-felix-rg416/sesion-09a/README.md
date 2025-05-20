# sesion-09a

- Para postular hay que ser lo más específicos posibles [palacio pereira]
    - emergencias tecnológicas
- <https://patshiu.com/> <https://officialfan.club/>
- [new york](https://www.diaart.org/visit/visit-our-locations-sites/walter-de-maria-the-new-york-earth-room-new-york-united-states)
- [ranking de universidades](https://www.topuniversities.com/world-university-rankings)
- "todo chile es charcha" "asume que nada en tu vida va a funcionar" - papá de Aarón

hay que postular para no quedar

descripción del proyecto, no genérico, no tímido, específico,

- turco mecánico (primer robot -anécdota de misa-)
- hidrófono: micrófono de submarino
- envelope follower
- laurie anderson concert for dogs
- lou reed velvet underground
- <https://www.wolframalpha.com/> cálculos ridículos

## PAM 8403 <>

mini amplificador 5V con control de volumen

módulos: un chip con las conexiones ya hechas, conexiones SMT

## [relé de canal 01](https://afel.cl/products/rele-de-01-canal)

* imagen *

controla el encendido y apagado de cualquier aparato que se conecte a una fuente de alimentación eléctrica externa.

# 555

- astable - no estable--> oscilación cíclica - control/aviso - va y viene _-_-_-_-_ (los transistores son el turco mecánico)
    - input: resistencia [R] y condensador [C] 
    - output: led - sonido - movimiento - AVISO

- monostable - timer - está en un estado de estabilidad hasta que es perturbado 

> "está durmiendo y dice 'ah, me despertaron' y se mantiene así" - misa

    - input: resistencia [R] y condensador [C]
    - output: led - movimiento - sonido - AVISO


## módulo - siguiente grado de expansión en la electrónica

- lo más importante de la electrónica: electrones - conjunto de electrónes: materia -> componentes "no importa qué es, importa para qué sirve"
    - resistencias
    - condensadores
    - diodos
    - LED
    - power suplly (batería)
    - potenciómetro (resistencia variables)
-> circuitos - Ateri Punk Console - astable - monostable -> CAJA NEGRA

## diagrama de flujo

separar el problema que queremos resolver en cajas más chicas para simplificarlo

# control de brillo LED - circuito PWM

Pulse Width Modulation - Modulación por Ancho de Pulso

- diodo 1n4148 - tienen que estar en antiparalelo, uno hacia un lado y otro en hacia el contrario
- potenciómetro de 100k (potenciometros más grandes no sirven para notar el cambio)

tioene una gradiante - comportamiento gris, no es blanco y negro

- en la pata 3 siempre sale una onda rectangular
- no se controla la amplitud de la onda ni la frecuencia, estamos cambiando cuanto tiempo está prendido. la suma del tiempo que está prendido más cuando está apagado, es constante sin importar la posición del potenciómetro, lo que cambia es la diferencia entre cada momento
- porcentaje que para prendido: DUTY "si el duty es de 90% significa que el 90% del timpo está prendido y el 10% apagado"


> - siempre va a parpadear por la persistencia visual -> cuando ves una luz por mucho tiempo, cierras los ojos y se sigue viendo la luz

qué pasa si cambia el valor del potenciómetro

- digital -> discreto - tiempo
- analógico -> continua - hora

## relé

- IN: aviso - 555
- GND: negativo
- VCC: positivo