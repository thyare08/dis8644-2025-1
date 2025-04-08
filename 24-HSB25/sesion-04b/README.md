# sesion-04b

# PROJ1: Bajando Opacidad a la Caja Negra - MI OBJETO: Control Luces LED RGB

![control](https://mercotecnia.cl/wp-content/uploads/2021/06/Controlador-Cinta-Led-con-Control-Remoto-44-botones.jpeg)

![control01](https://github.com/HSB25/dis8644-2025-1/blob/main/24-HSB25/sesion-04b/control01.png?raw=true)
![control02](https://github.com/HSB25/dis8644-2025-1/blob/main/24-HSB25/sesion-04b/control02.png?raw=true)
![control03](https://github.com/HSB25/dis8644-2025-1/blob/main/24-HSB25/sesion-04b/control03.jpeg?raw=true)
![control04](https://github.com/HSB25/dis8644-2025-1/blob/main/24-HSB25/sesion-04b/control04.jpeg?raw=true)
![control05](https://github.com/HSB25/dis8644-2025-1/blob/main/24-HSB25/sesion-04b/control05.jpeg?raw=true)
![control06](https://github.com/HSB25/dis8644-2025-1/blob/main/24-HSB25/sesion-04b/control06.jpeg?raw=true)
![control07](https://github.com/HSB25/dis8644-2025-1/blob/main/24-HSB25/sesion-04b/control07.jpeg?raw=true)








# **1.¿Cómo se utiliza el aparato?**

*Función indicativa y simbólica (gestos, contexto)*

- Uso: El usuario apunta el control hacia el receptor IR de las luces LED y presiona botones con funciones específicas.

- Indicadores: Botones con íconos y colores (por ejemplo, rojo, verde, azul, blanco) indican qué color se seleccionará.

- Botones como "ON", "OFF", "FLASH", "FADE" tienen texto impreso que cumple una función simbólica (indican la acción directamente).

- El gesto principal es presionar un botón.

# **2. ¿Quién es el usuario esperado?**

*Condiciones de accesibilidad*

- Usuarios generales: Personas de todas las edades (niños, adultos mayores) pueden usarlo si tienen visión funcional.

- Accesibilidad limitada para personas con:

- Problemas de visión (los botones suelen ser pequeños y diferenciados por color, pero sin relieve ni braille).

- Dificultades motrices finas (por el tamaño pequeño de los botones).

- No tiene retroalimentación táctil ni sonora, lo que lo limita para usuarios con discapacidades.

# **3. ¿Qué interacción ofrece desde fuera?**

- Botones físicos: entre 20 y 44, dependiendo del modelo.

*Tipos de botones:*

- Encendido/Apagado ("ON/OFF").

- Selección de color: RGB + tonos derivados.

- Brillo: "+" y "−".

- Modos: FLASH, STROBE, FADE, SMOOTH.

- Grado de control: Medio. No permite personalización avanzada ni programación, pero permite seleccionar colores, intensidades y efectos.

# **4. ¿De dónde obtiene energía este aparato?**

*De una pila tipo botón (CR2025 o CR2032)*

- Tensión típica: 3V.

- Se inserta en una bandeja extraíble (tipo reloj o similar a controles pequeños).

# **5. ¿Hay una PCB principal? ¿Cómo se interconecta?**

Sí, hay una sola PCB principal.

En ella se encuentran:

- El microcontrolador (IC básico).

- El emisor IR.

- El conjunto de botones de membrana (en la parte frontal).

Interconexiones:

- Pistas de cobre en la PCB.

- Teclado de membrana impreso conectado directamente al circuito.

Identificadores:

- Algunas PCBs tienen serigrafía con: número de versión, código de fabricación, a veces fecha.

- Letras como “IR-24KEY-V1.0” indican el modelo de control.

# **6. Diagrama de flujo**

![Diagrama del control RGB](https://github.com/HSB25/dis8644-2025-1/blob/main/24-HSB25/sesion-04b/DIAGRAMA%20CONTROL%20RGB.png?raw=true)

**1. PILA 3V**
- Entrada de energía.

- Es una pila de botón (CR2025 o CR2032) que entrega 3 voltios.

- Su energía alimenta toda la electrónica del control.

**2. PCB PRINCIPAL**

- La placa base donde están montados todos los componentes.

- Tiene pistas de cobre que conectan eléctricamente cada parte del sistema.

**3. IC Microcontrolador**

- Es el cerebro del dispositivo.

- Recibe las señales de los botones y las interpreta.

- Por ejemplo, si aprietas el botón azul, este chip genera la señal necesaria para que el LED infrarrojo envíe ese comando.

**4. Botones de Membrana**

- Cada botón está conectado a la PCB y activa una entrada eléctrica en el microcontrolador.

- Cuando presionas uno, cierras un circuito y envías una señal digital.

- No hay retroalimentación electrónica (ni sonido, ni luz).

**5. LED IR EMISOR**

- El diodo emisor infrarrojo se activa cuando el microcontrolador lo indica.

- Emite una señal en el espectro IR (invisible al ojo humano) que lleva la instrucción a las tiras LED.

- Estas señales son codificadas (por ejemplo, usando protocolos como NEC o RC5).

![ILUSTRACION CONTROL RGB](https://github.com/HSB25/dis8644-2025-1/blob/main/24-HSB25/sesion-04b/ILUSTRACION%20CONTROL%20RGB.png?raw=true)

# **7. Bill of Materials (BOM) – Partes generales**

| Ítem | Componente                 | Descripción                                  | Cantidad |
|------|----------------------------|----------------------------------------------|----------|
| 1    | Carcasa plástica frontal  | Plástico inyectado, con orificios para IR y botones | 1        |
| 2    | Carcasa plástica trasera  | Plástico con bandeja deslizante para pila    | 1        |
| 3    | PCB principal              | Placa de circuito impreso, 1 capa            | 1        |
| 4    | Botonera de membrana       | Teclado flexible tipo domo, impreso          | 1        |
| 5    | Emisor infrarrojo (IR LED)| LED que transmite señal infrarroja           | 1        |
| 6    | Microcontrolador (IC)     | IC básico de control IR (p. ej. SC6122)      | 1        |
| 7    | Pila tipo CR2032          | Pila de litio 3V                             | 1        |
| 8    | Portapila                 | Soporte para pila de botón                   | 1        |
| 9    | Resistencias              | Para limitar corriente al IR y otros usos    | 2–4      |
| 10   | Capacitores               | Para estabilización de energía               | 1–2      |
| 11   | Serigrafía frontal        | Lámina plástica con íconos y colores         | 1        |




