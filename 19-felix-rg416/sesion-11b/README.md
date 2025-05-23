# sesion-11b
### 23-05

- circuito integrado 4040 contador binario
- serie 40xx - circuitos integrados

## lógica

 - secuancial - el tiempo es importante
 - conbinacional  - seudo simultáneo

# 555

- pin 3 --> pin clk del 4017
- pin 4 **reset** - espera recibir voltaje positivo - se puedde conectar a un 4017 

# 4017

los circuitos integrados 40xx, son una serie de cirtuitos que hacen funciones distintas

![4017](.\archivos\4017.png)

- pin 14 **clk** - clok
- pin 16 --> VCC ("puede ser muy sano ponerle un condensador de 10uF" conectado al negativo, al pin 16 y al positivo)
- pin 8 --> GND
- pin 10 (Q4) --> pin 15 (reset)
- pin 13 **cken** (clok enable) --> con resistencia de 100k a GND
- pin 12 **Cout** - carry
- pin 2 al 11 (sin el 8)

# secuencia de LED

4017 manejado por un 555 se usa como timer para hacer una secuencia de luces

- la velocidad depende de la resistencia que tenga el 555 (pote, LDR, etc)

> - para que el potenciómetro tenga mayor rango de resistencia, poner una resistencia en un extremo y el centro
![pote+resistencia](.\archivos\pote+resistencia.png)

en el segundo 555 puse un potenciómetro B500K con una resistencia de 10k

![LEDsequence](.\archivos\LEDsequence.jpg)

## USB A 

sí o sí hay un cable positivo y otro negativo [rojo y negro] 
