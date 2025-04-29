# sesion-07b

continuamos con kicad

Me mande una embarrada y instale el kicad 7 en vez de la version mas reciente kicad 9

Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P10.16mm_Horizontal

Capacitor_THT:C_Disc_D6.0mm_W2.5mm_P5.00mm

Capacitor_THT:CP_Radial_D6.3mm_P2.50mm

LED_THT:LED_D5.0mm

TerminalBlock:TerminalBlock_MaiXu_MX126-5.0-02P_1x02_P5.00mm

Diode_THT:D_DO-41_SOD81_P10.16mm_Horizontal

modules_teee2025:SPDT_PCB_small_P2.5mm

modules_teee2025:caiman

Capacitor_THT:C_Disc_D6.0mm_W2.5mm_P5.00mm

Al PCB se le puede dar diversas formas exportandolas desde otros programas (fushion - rhino)

ARC: permite redondar bordes placa
VIA: es un pequeño orificio perforado en la PCB que permite la conexión eléctrica entre diferentes capas del PCB
HUELLAS 

completar apuntes!!!!

## Encargo-16: cotizar udpudu en JLCPCB de forma productiva
hacerse una cuenta en JLCPCB y cotizar udpudu, para 30 personas, documentar cada parámetro y elección.

JLCPCB es una empresa china que fabrica placas de circuito impreso (PCBs). Es una opción económica y rápida. También ofrecen el servicio de montaje de componentes si se les envía el diseño correspondiente. Me sorprende que vayamos a mandar a fabricar las PCBs, ya que en otros cursos muchos profesores nos decían que encargar cualquier cosa a China era complicado y costoso. Sin embargo, ahora veo una perspectiva completamente diferente. En tan solo unas semanas, podremos tener en nuestras manos una PCB fabricada afuera.

## Cotización en JLCPCB

![Cotización JLCPCB](./cotizacion%20udpudu%20en%20JLCPCB%201.png)

## Costos de envío

![Costos envío](./costos%20envios.png)

| Parámetros              | Valor elegido              | ¿Por qué?                                                    |
|------------------------|----------------------------|--------------------------------------------------------------|
| **Material base**      | FR-4                       | Es el más común y barato, sirve bien para casi todo.         |
| **Capas**              | 2                          | El diseño solo necesita dos capas, más sería exagerado.      |
| **Tamaño**             | 85 mm x 55 mm              | Lo detectó JLCPCB automáticamente desde el archivo.          |
| **Cantidad**           | 30 piezas                  | Con esto alcanza para todo el curso, quedando algunas extras. |
| **Tipo de producto**   | Electrónica de consumo     | Es lo más general y aplica para nuestro proyecto.            |
| **Diseños distintos**  | 1                          | Solo estamos haciendo una versión.                           |
| **Formato de entrega** | PCB suelta                 | No necesitamos que las panelicen.                            |
| **Espesor**            | 1.0 mm                     | Buen grosor, ni muy frágil ni muy caro. con valores más caros, el precio aumenta)|
| **Color de la PCB**    | Azul                       | Me gusta el color azul.                                      |
| **Color de serigrafía**| Blanco                     | Hace buen contraste con el fondo azul.                       |
| **Acabado superficial**| HASL con plomo             | Es barato y fácil para soldar a mano.                        |

---

###  Precio total

| Conceptos              | Costos       |
|------------------------|-------------|
| Fabricación PCB        | $10.70 USD  |
| Tarifa de ingeniería   | $4.00 USD   |
| **Subtotal**           | **$14.70 USD** |
| Envío por DHL (3-7 días) | $32.37 USD |
| **Total con envío**    | **$47.07 USD** |

Envío por DHL: Aunque es caro, los tiempos de entrega son más rápidos. Lo ideal sería usar este método para el examen; tendríamos que tener los proyectos casi listos al menos un mes antes para poder mandar a fabricar las placas a tiempo.

---

### Tiempo de fabricación
- Seleccioné la opción de 3 días (sin pagar extra), ya que de momento no hay apuro. Aunque también está disponible una opción de fabricación en 24 horas, esta tiene un costo adicional de $7.20 USD.

---



## encargo-17: cotizar udpudu en JLCPCB de forma experimental
probar opciones que no entiendan, documentar otros parámetros que no conozcan aún.
