# sesion-10b

16-05-2025

## clase

**KiCAD**
para generar una imagen en png, exportar: cuts, f silkscreen, f mask.

para bom directo: data → te texto a columnas → separador ,
para importar: en esta misma hoja.

exportar como csv (valores separados con coma)

convertcsv.com pag web para convertir de csv a md

## encargo-22: documentación textual del proceso de ensamblado de udpudu

proceso:

1. tener bom de materiales y seleccionarlos: identificar la cantidad, valor, posición.
2. al soldar debemos tener precaución con componentes para que no quede espacio entre los componentes y la pcb
3. debemos cortar las patitas bien cerca de la pcb

tips: 

- tener precaución al soldar el componente, asegurándose de colocarlo en la posición correcta y evitando el exceso de estaño para prevenir fallas de conexión.
- limpiar la punta del cautín
- simpre verificar si esta bien el componente, posición y el valor antes de soldar

bom 

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

*sacado de dis8644-2025-1/00-docentes/sesion-10b/*

## encargo-23: documentación visual del proceso de ensamblado de udpudu

faltan (2 unidades) terminal block de 2 pines e (1 unidad) interruptor de 2 posiciones

![bom](https://github.com/Anaisbmg/dis8644-2025-1/blob/main/11-Anaisbmg/sesion-10b/archivos/bom.jpeg)

*foto sacada por santiago*

*video desde galeria*

https://github.com/user-attachments/assets/81be00b6-38f8-4c94-97c1-c6fb91cc8490

*link a youtube video*

[soldadura.anaisbmg](https://youtube.com/shorts/ZTDDUp5fdoA?feature=share)

terminal block van mirando hacia fuera para insertar los cables

![cuidado](https://github.com/Anaisbmg/dis8644-2025-1/blob/main/11-Anaisbmg/sesion-10b/archivos/cuidado.jpeg)

proceso, verificar si esta bien el componente, posición y el valor antes de soldar

![proceso](https://github.com/Anaisbmg/dis8644-2025-1/blob/main/11-Anaisbmg/sesion-10b/archivos/proceso.jpeg)

![pcbfinalizada.anaisbmg](https://github.com/Anaisbmg/dis8644-2025-1/blob/main/11-Anaisbmg/sesion-10b/archivos/apcpudufinalizada.jpeg)
