# sesion-10b

16 de Mayo de 2025.

## Trabajo en clase

 - En clase nos entregaron la placa UDPudu, para soldar sus componentes. Para esto realizamos un BOM de materiales del UDPudu original.

BOM CVS Original.

|Reference|Value                        |Datasheet|Footprint                                    |Qty|DNP|
|---------|-----------------------------|---------|---------------------------------------------|---|---|
|C3       |100n                         |~        |Capacitor_THT:C_Disc_D6.0mm_W2.5mm_P5.00mm   |1  |   |
|C4       |1u                           |~        |Capacitor_THT:CP_Radial_D6.3mm_P2.50mm       |1  |   |
|C5       |47u                          |~        |Capacitor_THT:CP_Radial_D6.3mm_P2.50mm       |1  |   |
|D1       |1n4007                       |~        |Diode_THT:D_DO-41_SOD81_P10.16mm_Horizontal  |1  |   |
|D2,D3    |LED                          |~        |LED_THT:LED_D5.0mm                           |2  |   |
|J1,J3    |CAIMAN                       |~        |modules_teee2025:caiman                      |2  |   |
|J2       |TBLOCK_2                     |~        |TerminalBlock:TerminalBlock_MaiXu_MX126-5.0-02P_1x02_P5.00mm|1  |   |
|LS1      |SPK                          |~        |TerminalBlock:TerminalBlock_MaiXu_MX126-5.0-02P_1x02_P5.00mm|1  |   |
|R2,R3,R4 |1k                           |~        |Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P10.16mm_Horizontal|3  |   |
|SW1      |SW_SPDT                      |~        |modules_teee2025:SPDT_PCB_small_P2.5mm       |1  |   |
|U1       |~                            |         |Package_DIP:DIP-8_W7.62mm_Socket_LongPads    |1  |   |

BOM para armar UDPudu.

|Referencia  |Valor   |Huella                   |Qty|OBS               |
|------------|--------|-------------------------|---|------------------|
|U1          |~       |Socket 8 pines           |1  |                  |
|R2,R3,R4    |1k      |Resistencias             |3  |                  |
|D1          |1n4007  |Diodo                    |1  |                  |
|C3          |100n    |Condensador cerámico     |1  |104               |
|C4          |1u      |Condensador electrolítico|1  |                  |
|C5          |47u     |Condensador electrolítico|1  |                  |
|D2,D3       |LED     |Led 5mm                  |2  |                  |
|J2          |TBLOCK_2|Terminal Block 2         |1  |                  |
|LS1         |SPK     |Terminal Block 2         |1  |                  |
|SW1         |SW_SPDT |Switch spdt              |1  |                  |
|U1          |NE555   |DIP-8                    |1  |Va en el socket U1|
|Clip batería|9v      |                         |1  |                  |
|Parlante    |8ohm    |                         |1  |                  |
|J1,J3       |CAIMAN  |Cables caimán            |2  |                  |

## Encargo 22 y 23: Documentación textual y visual del ensamblado de la PCB UDPudu

1<qQ
