# sesion-12a

#  Proyecto de Semáforo Electrónico con Detector de Sombra

Este proyecto consiste en la construcción de un semáforo electrónico dividido en tres etapas, utilizando componentes como el LM324, el temporizador 555 y el contador CD4017. Además, se incorpora un detector de sombra que permite la activación del sistema mediante la detección de cambios en la iluminación ambiental.

---

##  Etapa 1: Detector de Sombra

**Objetivo:** Activar un LED en función de la cantidad de luz recibida por un LDR (Light Dependent Resistor).

**Componentes:**

- Amplificador operacional LM324
- LDR
- Potenciómetro
- Resistencias de 1kΩ y 10kΩ
- LED
- Cables de conexión

**Descripción:**

Se construyó un circuito que utiliza un LDR para detectar la presencia o ausencia de luz. La señal del LDR es amplificada por el LM324, y mediante el ajuste del potenciómetro, se establece el umbral de activación del LED. Cuando la luz sobre el LDR disminuye (por ejemplo, al pasar una sombra), el LED se enciende, indicando la detección de oscuridad.


