# sesion-12b

Viernes 30 de Mayo del 2025.

Me encontraba con licencia pero de igual forma me consegui la materia

## Apuntes

## Fuentes de Poder Alternativas a Baterías de 9V

Además de las baterías tradicionales, existen diversas fuentes de alimentación:

### Alternativas comunes

* **Eliminadores de voltaje (fuentes AC/DC)**: Transforman corriente alterna en continua.
* **Powerbank**: Fuente portátil de energía, útil para dispositivos de bajo consumo.
* **Conectores USB**:

  * **USB-A / USB-B**: Pueden alimentar pequeños proyectos.
  * **USB-C**: Precaución, ya que puede manejar voltajes variables; no todos los dispositivos son compatibles.
* **Paneles solares**: Ideal para proyectos autónomos o al aire libre.
* **Pilas**:

  * **AA y AAA**: Fáciles de conseguir, buena autonomía.
  * **CR2032**: Utilizadas comúnmente en dispositivos compactos o de bajo consumo.

## Parámetros importantes al elegir una fuente de poder

### 1. **Voltaje (VDC)**

* Las fuentes comunes van desde **4.5V hasta 25V**, por ejemplo: 5V, 7V, 9V, 12V, 15V, 18V, 25V.

### 2. **Polaridad**

* Verificar si el **centro del conector** es positivo o negativo.

### 3. **Tamaño del conector**

* Conectores típicos: **2 mm o 2.5 mm** de diámetro central.

### 4. **Corriente (A)**

* **La corriente la demanda el dispositivo**, pero la fuente debe ser capaz de **proveer más de la necesaria**, no menos.

## Iluminación

### - **Ampolletas domésticas**

* Funcionan a **220V AC**, pero pueden ser controladas con **relés**.

### - **LEDs de alta potencia (3W–5W)**

* Requieren **resistencias adecuadas** y buena disipación de calor.

### - **Tiras LED**

* Consumen bastante, es recomendable controlarlas mediante **transistores** y modulación PWM.
* Algunas pueden cortarse; se deben calcular sus necesidades por metro (tensión y corriente).

## Motores

### - **Motores DC (6V)**

* Giran a máxima velocidad al recibir energía.
* Común en juguetes, ventiladores, vibradores, etc.

### - **Motorreductores**

* Reducción de velocidad mediante engranajes. Ideal para aplicaciones que requieren más torque y menos velocidad.

### - **Stepper Motors (Motores paso a paso)**

* Muy precisos y controlados por pulsos.
* Tipos:

  * **Unipolares**
  * **Bipolares**

### - **Servomotores**

* Motores con control de posición.
* Precisos, pero pueden ser inestables en ciertas condiciones.

### - **Puente H**

* Circuito que permite invertir la dirección de un motor DC.
* Se puede armar con:

  * **4 transistores** o interruptores
  * O usar un **CI como el L298N**

### - **Solenoides**

* Generan movimiento lineal mediante magnetismo.
* Se usan en cerraduras electrónicas, percusiones, etc.

## Transistores

* Se usan como:

  * **Amplificadores**
  * **Interruptores (switch)**
  * **Inversores**
  * **Compuertas lógicas**

### Tipos principales

* **BJT (Bipolares)**: Ejemplo clásico: *2N2222*
* **MOSFET**: Ejemplo típico: *IRFZ44N*

## Sonido

### - **Parlantes**

* **Activos**: Tienen su propia alimentación.
* **Pasivos**: Necesitan amplificación externa (ej: módulo **PAM8403**).
* Factores a considerar:

  * **Tamaño** (pulgadas)
  * **Potencia (Watt)**
  * **Impedancia (Ohmios)**

### - **Buzzers**

* Emiten tonos básicos para alertas. Muy sonoros.

### - **Reproductores de audio**

* Transforman datos digitales en señales audibles.

### - **Micrófonos**

* Transforman sonido en electricidad.
* El más común: **Electret**.

### - **Piezoeléctricos**

* Generan electricidad por deformación mecánica.

### - **Sintetizadores**

* Generan sonidos a partir de señales eléctricas internas.

## Pedales de guitarra

* Modifican el sonido eléctrico de la guitarra.
* Requieren componentes electrónicos específicos.
* Puedes revisar proyectos en **Tonepad** para ejemplos y circuitos.
