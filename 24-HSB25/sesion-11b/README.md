# sesion-11b

# Secuenciador LED con CD4017 y Timer 555

Este proyecto utiliza el integrado **CD4017** junto con un **Timer 555** para crear un **secuenciador LED de 10 pasos**, también conocido como un **Ten-segment LED bargraph**.

Inspirado en los conceptos binarios de **encendidos y apagados** (0s y 1s), y haciendo una referencia musical a *Hail to the Thief* de **Radiohead**, este circuito explora la lógica digital secuencial.

---

## Conceptos Básicos

### Tipos de Lógica Digital

- **Lógica Combinacional:** Las salidas dependen directamente de las entradas actuales.
- **Lógica Secuencial:** Las salidas dependen de entradas **y** del **estado anterior**; es decir, ocurren eventos **en el tiempo**.

---

##  ¿Qué es un secuenciador?

Un **secuenciador** es un sistema que avanza por una serie de pasos. En este caso, los pasos están representados por LEDs que se encienden uno tras otro, en secuencia, al ritmo de una señal de reloj (clock).

---

##  Componentes Principales

### CD4017 – Decodificador Johnson de 10 salidas

- **VCC (16):** Alimentación positiva (+5V)
- **GND (8):** Tierra
- **CLK (14):** Entrada de reloj. Avanza el estado del contador en cada pulso.
- **CKEN (13):** Clock enable. Debe estar en GND (por ejemplo,

## 🧩 Chips 40XX

El CD4017 forma parte de la familia **40XX**, una serie de circuitos integrados CMOS muy utilizados en lógica digital.

---

## 🔌 Conectores USB (Referencia rápida)

| Tipo     | Pines                     |
|----------|---------------------------|
| USB-A    | Tierra, Data+, Data−, VCC |
| USB-B    | Variante para periféricos |
| MicroUSB | Variante del tipo B       |
| MiniUSB  | Variante del tipo B       |
| USB-C    | Reversible, multifuncional |

