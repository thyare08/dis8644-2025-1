# sesion-04b

## circuito monoestable

- [calculadora de circuito 555](https://ohmslawcalculator.com/555-monostable-calculator)
- 



### encargo
 
Hi, How Are You -  Daniel Johnston

Botón experimental

# encargo: mouse rosado

![mouse rosado](https://github.com/felix-rg416/dis8644-2025-1/blob/main/19-felix-rg416/sesion-04b/archivos/mouse.01.jpg) ![mouse.02](https://github.com/felix-rg416/dis8644-2025-1/blob/main/19-felix-rg416/sesion-04b/archivos/mouse.02.jpg)

### uso y usuario

el mouse inalámbrico es un objeto común para las personas que usan computador o laptop. aunque muchas laptops incluyen un trackpad, muchos usuarios prefieren un mouse externo gracias a su comodidad y precisión.

está dirigido a cualquier persona que utilice un computador, sin necesitar conocimientos técnicos para su uso. es intuitivo y ergonómico: la mano hábil (generalmente la derecha) se posa sobre él, dejando el dedo índice y medio sobre los botones principales, ubicados a ambos lados del scroll central.

### interacción e indicaciones de uso

generalmente, la forma del mouse sugiere su modo de uso de manera ergonómica e indicativa: la curva superior invita a apoyar la mano, los botones y la rueda central indican las zonas de interacción (en este caso no tiene una forma curva, pero, al conocer otros modelos, es posible intuirlo). no se necesitan mayores señalizaciones para su uso

funciones externas y control:
- botón izquierdo: selección, apertura y ejecución de elementos en pantalla.
- botón derecho: despliega menús contextuales o funciones adicionales.
- scroll (o rueda) central: permite desplazarse verticalmente en documentos o páginas web; también puede presionarse como botón adicional para ejecutar atajos o funciones específicas.

todos los elementos son de fácil acceso con una sola mano, ofreciendo un grado de control simple, pero eficiente.
_______________________
## componentes internos

**placa PCB principal:** tiene una única placa PCB, donde se encuentran todos los componentes electrónicos. la placa une la alimentación, el procesamiento de datos y la interfaz física con el usuario.

**interruptores:**
- 2 con botones rojos para el clic izquierdo y derecho.
- 1 negro bajo el scroll para el clic central.

**scroll:** tiene un codificador que lee el movimiento de la rueda

**sensor óptico:** está ubicado hacia la parte de abajo del mouse, funciona junto a un LED rojo para detectar el movimiento en la superficie

**LED:** emite una luz que es reflejada por la superficie y captada por el sensor. es lo principal para el funcionamiento del rastreo óptico.

**inductor de 100 µH:** filtrar o estabilizar la corriente eléctrica en el circuito

**oscilador de cristal:** mantiene la frecuencia estable para las comunicaciones y procesamiento del microcontrolador.

**microcontrolador:** procesa todas las señales: clics, scroll, movimiento, y las convierte en datos que el computador interpreta para mostrar en la pantalla.

**conector de alimentación:** es el conector para el compartimento de la pila AA

### alimentación
necesita sólo una pila AA. en la placa está dibujado el positivo y el negativo para el conector. le da energía a toda la PCB. todo está integrado en una sola PCB, sin placas secundarias ni cables internos complejos. las señales viajan mediante pistas conductoras dentro de la placa, que conectan los interruptores, el sensor y el microcontrolador.

## señales, códigos y textos
la placa tiene serigrafiados varios elementos:

- **texto:**
  	- modelo de placa: "HXSC - WK8 - TLW - DT"
  	- fecha de fabricación: "2021 - 08 - 02"
  	- versión de placa: "VER - 01"
 
- **marcas y símbolos:**
  	- "LED" muestra la ubicación del LED
  	- "LB", "RB" y "MB" left, right, middle button (respectivamente). indica la ubicación de los botones
  	- "ENC" (encoder) ubicación del **codificador**
  	- "L1" ubicación del **inductor** .
  	- "U1" y "U2" son los circuitos integrados. el U1 está en la parte superior y es el sensor optico junto a un chip. el U2 es otro chip que controla las entradas, comunicación y lógica del mouse.

| **componente*         | **Qty** | **nombre** | **valor/tipo** |
|-----------------------|---------|------------|----------------|
| botones               | 3       | LB, RB, MB | 6mm            |
| encoder               | 1       | ENC        |                |
| sensor óptico         | 1       | U1         |                |
| chip                  | 1       | U2         |                |
| LED                   | 1       | LED        | 1.2 - 1.8 V    |
| inductor              | 1       | L1         | 100 µH         |
| oscilador de  cristal | 1       | Y1         | 16MHZ          |
| PCB                   | 1       | -          |                |
| conector de pila      | 1       | -          |                |
|                       |         |            |                |
