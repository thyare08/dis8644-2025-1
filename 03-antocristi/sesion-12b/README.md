# sesion-12b
## Encargo 24

1-. Indicador de bateria

Para poder monitorear la bateria para los circuitos que desee ocupar, en mi caso, siempre se me olvida cargarla por lo que nunca se si esta bien cargada o no, su rango de monitoreo va desde los 1,2V hasta los 12V.

2-. Ruleta 

3-. Sonidos laser 
### El factor común de estos circuitos son los LED, me llama la atención el jugar con ciertos patrones.

## Encargo 25

### 1-. Indicador de bateria 
El indicador de nivel de batería indica el estado de la batería simplemente mediante el encendido de los LED. Por ejemplo, si seis LED están encendidos, significa que la batería tiene un 60 % de capacidad.

El componente principal de este circuito indicador de nivel de batería es el circuito integrado LM3914. En este circuito, no se necesitan resistencias en serie con los LED, ya que la corriente la regula el circuito integrado.

![Circuito 1](https://github.com/user-attachments/assets/a6f31e60-7c21-43f9-bdf8-53faf8e50aae)

| Componentes    | Nombre                         | Valor       | Cantidad |
|----------------|--------------------------------|-------------|----------|
| Resistencias   | R1                             | 4.7K        | 1        |
| Resistencias   | R2                             | 18K         | 1        |
| Resistencias   | R3                             | 56K         | 1        |
| Potenciometro  | POT                            | 10K         | 1        |
| Chip           | 3914                           | LM3914      | 1        |
| LED            | D1,D2,D3,D4,D5,D6,D7,D8,D9,D10 |             | 10       |
| Switch         | SW1                            | SPST switch | 1        |

![Nivel de bateria](https://github.com/user-attachments/assets/df1ee766-5e0c-46db-853a-ac4a00b3261b)

### 2-. Ruleta 

![Circuito 2](https://github.com/user-attachments/assets/a51d119f-92f1-4ecf-bdde-acf8ab04654e)

| Componentes        | Nombre                         | Valor  | Cantidad |
|--------------------|--------------------------------|--------|----------|
| Resistencias       | R1                             | 3m3    | 1        |
| Resistencias       | R2                             | 10m    | 1        |
| Resistencias       | R3                             | 10k    | 1        |
| Resistencias       | R4                             | 470R   | 1        |
| Resistencias       | R5                             | 4m7    | 1        |
| Tansistor          | 557                            | BC557  | 1        |
| Chip               | 4017                           | CD4017 | 1        |
| Chip               | 555                            | NE555  |          |
| LED                | D1,D2,D3,D4,D5,D6,D7,D8,D9,D10 |        | 10       |
| Interruptor tactil | Touch Wires                    |        | 1        |
| Capacitor          | C1                             | 1uf    | 1        |
| Capacitor          | C2                             | 100nf  | 1        |


### 3-. Sonidos laser 

![Circuito 3](https://github.com/user-attachments/assets/0090c770-6a60-4d6a-9a9b-56409d130733)

| Componentes             | Nombre  | Valor  | Cantidad |
|-------------------------|---------|--------|----------|
| Resistencias            | R1      | 220K   | 1        |
| Resistencias            | R2      | 470R   | 1        |
| Chip                    | 555     | NE555  |          |
| LED                     | D1      |        | 1        |
| Parlante                | SPKR    |        | 1        |
| Condensador             | C1      | 100n   | 1        |
| Condensador polarizado  | C2      | 104    | 1        |
