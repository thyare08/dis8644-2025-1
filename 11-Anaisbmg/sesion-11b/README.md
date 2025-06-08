# sesion-11b

23-05-2025

## apuntes

### chip 555 → 8 patitas/pines 

que prende y apaga una onda cuadrada, gracias a su pin numero 3 

### chip 4017 → 16 pines

**clk** es el que recibe la señal de la pin n3 del chip 555 con un **edge rising** (es cuando la onda cuadrara llega a su peak)
VCC 16, GND 8, reset 15, Q0 → 3, Q1 → 2, Q2 → 4, Q3 → 7, Q4 → 10, Q5 → 1, Q6 → 5, Q7 → 6, Q8 → 9, Q9 → 11, cken 13, clk 14

|uso|pin|
|---|---|
|Q5|1|
|Q1|2|
|Q0|3|
|Q2|4|
|Q6|5|
|Q7|6|
|Q3|7|
|GND|8|
|Q8|9|
|Q4|10|
|Q9|11|
|carry out|12|
|enable|13|
|clock|14|
|reset|15|
|VCC|16|

hoy utilizaremos hasta la pata n4, para hacer esto debemos darle esa señal para que vuelva al inicio. 

Utilizaremos Q0 → 3, Q1 → 2, Q2 → 4, Q3 → 7

se le agrego un condensador polarizado de 10uf para que pudiera funcionar el pin 16 del chip 4017

![pizzara](https://github.com/Anaisbmg/dis8644-2025-1/blob/main/11-Anaisbmg/sesion-11b/archivos/esquematicopizarra.png) 

https://github.com/user-attachments/assets/16e3b40f-6fea-43d9-98a4-42224ce2f107

[ejerciciochip4017](https://youtube.com/shorts/g7kyc6f5_JA?feature=share)

se realizó una variación y se agrego un botón a las conexiones del potenciómetro.

https://github.com/user-attachments/assets/4ee91025-e102-495a-ad51-aefce920525b

[ejerciciovariaciónbotónchip4017](https://youtube.com/shorts/jDjRfQpL2YQ?feature=share)

**muchos chips empiezan con 40 (serie 40xx)**

### no hay encargos por ser semana de solemne
