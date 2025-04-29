# sesion-07a

(Falté a esta clase)

# Kicad

<https://www.kicad.org/>

* Simuladores de circuitos en línea: _SPICE_ y _Falstad_.
* Opciones para el diseño de PCBs: _Eagle_ de _Autodesk_, _Fritzing_, _Osmond PCB_.

## Conceptos Clave  

### Componentes Electrónicos  

* Resistencias
* Capacitores
* Diodos
* Transistores, entre otros.
* Valor (ej: 10kΩ).  
* Símbolo (representación gráfica en esquema).  
* Rating (límite de tolerancia).  
* Footprint (dimensiones físicas y patas).  

### Capas en KiCad  

| Capa               | Función                              |  
|--------------------|--------------------------------------|  
| F.Cu / B.Cu    | Cobre frontal/trasero.               |  
| Edge.Cuts        | Bordes de la PCB (1mm de grosor).    |  
| F.Silkscreen     | Texto/grabados frontales.            |  
| F.Mask           | Máscara protectora (color verde/rojo). |  

---

## Flujo de Trabajo en KiCad

### 1. Esquemático (SCH)

* Comandos:  
  * "A" > Añadir componente.  
  * "R" > Rotar.  
  * "W" > Cablear conexiones.  
  * "Q" > Marcar patas no usadas.
  * "ERC" > Verificar errores eléctricos (barra superior).  

### 2. Asignar Huellas (_Footprints_)  

* Relacionar símbolos con dimensiones físicas.  
  * Ejemplo: Potenciómetro RK163.  

### 3. Diseño de PCB  

* Ruteo:  
  * Trazar pistas manualmente > "X".  
  * Rellenar áreas de cobre > "B".  
* Visualización:  
  * Visor 3D > "Alt + 3".

## Referentes  

* _Clacktronics_ > PCBs como arte interactivo.

* Kelly Heaton > Circuitos pintados a mano.  
* _OpenFrameworks_ > Programación creativa.
* _Faderbank 16n_.
  
* Envío a China por JLCPCB o PCBWay.  
* Soldadura Manual o con stencil.  

## encargo-14

Diseñar esquemático en Kicad (solamente esquemático, no asignar huellas) de Atari Punk Console con modificaciones que ustedes realizaron en KiCAD, o en su versión base si sus modificaciones no funcionaron al 100%.

![captura_kicad_555](https://github.com/user-attachments/assets/85c5a317-4dde-4c81-86ee-ebef090c40d4)

## encargo-15

Revisar el Manual de supervivencia de KiCADdisponible en <https://misaa.notion.site/Manual-de-supervivencia-para-KiCAD-8cc756e79ced4271ad575874aaa3497e> y plantear 2 dudas y/o aprendizajes importantes, que quieran compartir en la próxima clase.

* Al momento de realizar nuestra PCB cómo terminar por diseñarla en vectores o en modelos 3D.
* ¿Cómo se exportan los diseños? ¿Tiene algo que ver las licencias tipográficas o de programación en esto?
