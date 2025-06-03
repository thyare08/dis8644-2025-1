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

## ⏱️ Etapa 2: Generador de Pulso con Temporizador 555

**Objetivo:** Generar una señal de reloj (clock) para controlar la secuencia del semáforo.

**Componentes:**

- Temporizador 555
- Resistencias de 1kΩ
- Condensador cerámico de 407
- Condensador de 10μF
- LED
- Cables de conexión

**Descripción:**

Se implementó un circuito astable utilizando el temporizador 555 para generar una señal de reloj continua. Esta señal es fundamental para controlar la secuencia de encendido y apagado de los LEDs en la siguiente etapa. El LED conectado al circuito parpadea con una frecuencia determinada por los valores de las resistencias y condensadores utilizados.

 **Video demostrativo:** [Ver en YouTube](https://youtube.com/shorts/mgrAHHeYQ6E?si=prMKpFH1SpHApSDG)

---

##  Etapa 3: Control de Secuencia con CD4017

**Objetivo:** Controlar la secuencia de encendido de los LEDs que simulan las luces de un semáforo.

**Componentes:**

- Contador CD4017
- LEDs
- Resistencias
- Cables de conexión

**Descripción:**

El CD4017 es un contador de décadas que, al recibir pulsos de reloj del temporizador 555, activa sus salidas secuencialmente. Cada salida del CD4017 está conectada a un LED que representa una luz del semáforo (roja, amarilla o verde). De esta manera, se logra una secuencia de luces que simula el funcionamiento de un semáforo real.

 **Video demostrativo:** [Ver en YouTube](https://youtube.com/shorts/evfKeNUtCkc?si=M1l-2M8OVpoLcswX)

---

##  Integración de las Etapas

Al combinar las tres etapas, se obtiene un sistema de semáforo electrónico que se activa mediante la detección de sombra. Cuando el LDR detecta una disminución en la luz, el LED de la primera etapa se enciende, activando el temporizador 555 de la segunda etapa. Este genera pulsos que son enviados al CD4017 en la tercera etapa, el cual controla la secuencia de los LEDs del semáforo.

---

##  Imágenes del Proyecto

![Semáforo Electrónico con 555 y CD4017](https://unicrom.com/wp-content/uploads/2023/04/Semaforo-electronico-con-555-y-4017.png)

*Fuente: [Unicrom](https://unicrom.com/semaforo-electronico-con-555-y-4017/)*

---

##  Componentes Utilizados

- [Amplificador Operacional LM324 / LM324N](https://chatgpt.com/?hints=search&q=Amplificador+Operacional+LM324+%2F+LM324N+%7C+Env%C3%ADo+a+todo+Chile)
- [Circuito Integrado Timer 555](https://chatgpt.com/?hints=search&q=Circuito+Integrado+Timer+555)
- [LDR fotoresistencia resistencia fotosensible sensor de luz](https://chatgpt.com/?hints=search&q=LDR+fotoresistencia+resistencia+fotosensible+sensor+de+luz)
- [Pack 5pcs Ic Decodificador Cd4017be Cd4017 Cmos [ Max ]](https://chatgpt.com/?hints=search&q=Pack+5pcs+Ic+Decodificador+Cd4017be+Cd4017+Cmos+%5B+Max+%5D)
- [Potenciómetro 10k](https://chatgpt.com/?hints=search&q=Potenci%C3%B3metro+10k)

---

##  Referencias

- [Semáforo Electrónico con 555 y CD4017 - Unicrom](https://unicrom.com/semaforo-electronico-con-555-y-4017/)
- [Detector de Sombra con LM324 y LDR (Video)](https://www.youtube.com/watch?v=aLV8XfISqdE)

---

![Semáforo terminado](https://unicrom.com/wp-content/uploads/semaforo-electronico-temp-555-cont-decad-4017.png)

![Semáforo terminado](https://image.easyeda.com/components/3b5d2e3af1b9406093e45f113e7bf828.png)




