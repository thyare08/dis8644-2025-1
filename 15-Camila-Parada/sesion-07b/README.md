# ⋆₊˚⊹♡ Clase 07b - Kicad 2 y Atari punk console ♡⊹˚₊⋆

Viernes 25/04/2025

***

## Observaciones

La clase resolvimos dudase de Kicad, por lo que fue primordial el tener un portátil con el cual trabajar.

El primer módulo se centró en aprender a cómo construir el esquemático y colocar las "huellas" (asociar piezas reales al listado de materiales).

La segunda parte de la clase se centró en orientar los materiales dentro de una placa PCB ficticia y a poder revisarlos en 3D.

Además, el profesor trajo un libro que se centra en la construcción de un módulo.

![byom foto 01 de 05](./archivos/byom-01.jpg)

![byom foto 02 de 05](./archivos/byom-02.jpg)

![byom foto 03 de 05](./archivos/byom-03.jpg)

![byom foto 04 de 05](./archivos/byom-04.jpg)

![byom foto 05 de 05](./archivos/byom-05.jpg)

Encontré un link que me lleva al producto: <https://www.thonk.co.uk/shop/byom/>

Y esta es la web de los desarrolladores: <https://clacktronics.co.uk/>

- Garrapatas = DIP (Dual in-line package o empaquetado/paquete de doble hilera).

***

## Bitácora digital

Al comienzo de la clase se nos presentaron algunos programas y bibliotecas que ayudan a poder facilitar los procesos de KiCad.

- **KiCad StepUp WB** (library) <https://github.com/easyw/kicadStepUpMod/>
  Permite importar diseños de PCB de KiCad a FreeCAD, creando un modelo 3D que puede ser utilizado para el diseño mecánico de la caja o envolvente.

  VRML -> El lenguaje de modelado de realidad virtual o VRML es un formato de archivo normalizado que tiene como objetivo la representación de escenas u objetos interactivos
  tridimensionales. Web a consultar: <https://www.geeksforgeeks.org/introduction-to-vrml/>

- **CAD assistant** (Herramienta) <https://www.opencascade.com/products/cad-assistant/>
  ¿Cómo poder exportar un archivo en 3D para poder revisarlo y fabricar una cobertura? Esta es una aplicación y software libre de Open CASCADE Technology que permite visualizar y convertir modelos 3D de CAD y malla.

Tras eso hubo que descargar un documento directo del Discord del curso y comenzamos con un proyecto nuevo.

Este documento posee un archivo (un chip 555). Este se agrega a a kicad mediante la gestión de biblioteca de simbolos (en herramientas).

![image](https://github.com/user-attachments/assets/b5435d1f-9f13-4f5a-8bd0-7724270df5d7)

![image](https://github.com/user-attachments/assets/962b7d96-d13a-42ea-b770-69999d8025b6)

![image](https://github.com/user-attachments/assets/9f42649b-61d1-4087-8e6a-16aabcd49752)

![image](https://github.com/user-attachments/assets/abe322ae-9790-4660-a85e-9b54c115971a)

Después, apretando la tecla "f" se pueden asignar "huellas", es decir, una forma física.

![image](https://github.com/user-attachments/assets/fa09ddcd-242b-4127-b051-24776f62eba0)

Dado que era un poco dificil encontrar la versión que se necesitaba, los profesores subieron mediante _discord_ la línea de palabras específica para encontrar el componente.

- Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P10.16mm_Horizontal (resistencia)
![image](https://github.com/user-attachments/assets/66c57f9d-0ac8-4d0b-9e3e-06da6362240e)

- Capacitor_THT:C_Disc_D6.0mm_W2.5mm_P5.00mm (condensador cerámico)
![image](https://github.com/user-attachments/assets/c85fb458-30b3-4547-a69b-0a66e14422f9)

- Capacitor_THT:CP_Radial_D6.3mm_P2.50mm (Condensador polarizado)
![image](https://github.com/user-attachments/assets/7f6d93cb-79ea-4425-b750-0e63ae80bd86)

- LED_THT:LED_D5.0mm (diodo led)
![image](https://github.com/user-attachments/assets/fe908223-349d-4b34-b04d-e2efbf321062)

- Package_DIP:DIP-8_W7.62mm_Socket_LongPads (Chip 555 entregado por los profes)
![image](https://github.com/user-attachments/assets/a33e1523-9322-4a17-8395-566f163c5748)

- TerminalBlock:TerminalBlock_MaiXu_MX126-5.0-02P_1x02_P5.00mm (Parlante)
![image](https://github.com/user-attachments/assets/37ced238-da5e-469d-90a1-dd74a4c5b036)

Después de hacer todas las huellas de los componentes, pues comenzamos a reordenar estos mismos para poder realizar el circuito de Atari Punk Console.

![image](https://github.com/user-attachments/assets/04971cbf-3230-4629-a50d-eb849a8428df)

A su vez se habló ded la violencia que presente el lenguaje de los elementos (master.slave, trigger, etc). Se hizo referencia al blog "CMD", quienes crean una alternativa a los nombres de estas terminologías. (<https://cdm.link/so-yeah-lets-just-use-plug-and-socket-industry-group-recommends-obvious-change-in-terminology/>).

Se agregaron unas terminales para los cables tipo Caimán "Conn_01x01_Socket". Y después un interruptor "SW_SPDT", una batería "+9v" y un Screw Terminal (Terminal de tornillo) "Screw_Terminal_01x02"

![image](https://github.com/user-attachments/assets/d2095a18-48f9-4394-9e4d-9223c8fba5a0)

Después se comenzó a nombrar y escribir los valores de los componentes, además de cambiarles el nombre.

![image](https://github.com/user-attachments/assets/6b1b1042-9870-4f36-b1d3-ab4c6138513c)

Después del momento del break, hubo que volver a reinstalar una carpeta que mandaron por discord, por lo que se reemplazaron los documentos del anterior.
Tras eso hubo que gestionar la biblioteca de huellas para agregar unas las carpetas que se encuentran en "modules".

![image](https://github.com/user-attachments/assets/43ce1cbb-e2dc-4397-960f-06eaad50e812)

Una vez listo, volvemos al archivo del diagrama y comenzamos a revisar las huellas faltantes con la opción "Asignar huellas"

![image](https://github.com/user-attachments/assets/eff1281c-17ca-4dd5-88c3-5cf6600e1687)

![image](https://github.com/user-attachments/assets/c5a8263f-bf4c-4934-ab37-f13ae0e0758a)

Ya teniendo el listado de huellas completo, toca trabajar en el documento pcb. Para ello es necesario reorganizar las piezas, crear las conexiones de cobre, las serigrafías, entre otros.

![image](https://github.com/user-attachments/assets/23a3f5d0-9870-466d-ba1d-3c5ca4da0bf9)

![image](https://github.com/user-attachments/assets/37a0054b-a266-4820-aad4-0a772f38fe0c)

![image](https://github.com/user-attachments/assets/b17174e6-9ad2-4576-8f0e-3817e0564ef4)

Al final no pude seguir el ritmo de la edición de la placa, por lo que tendré que estudiar la parte de edición y diseño gráfico de la placa, además de la importación.

Para ello he estado revisando una serie de videos de youtube: <https://youtube.com/playlist?list=PL-Hb9zZP9qC7-j4MKZNYg5i8rwu_ejkwW&si=FGzFyaG3pf5dPkZW>

Para finalizar la clase, nos enseñaron a como poder subir el documento a una página que se especializa en la fabricación de placas PCB.

<https://cart.jlcpcb.com/quote?orderType=1&stencilLayer=2&stencilWidth=100&stencilLength=100>

***

### Posdata

Me quedé colgada a la mitad de la clase, así que toca estudiar y practicar ૮◞ ﻌ ◟ა

***

°˖✧◝(⁰▿⁰)◜✧˖°
