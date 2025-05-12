# sesion-08a

## 29 de abril de 2025

### _Github_

* "Create pull request".
* Pull request: proponer una contribución.
* Fork: _behind_.
* Issue: problema.

### _KiCad_

* ¿Cómo hacer agujeros en la placa PCB?

_"Mouting hole"_ > Mounting Hole Pad. Símbolo, hay que asignarle una huella por ejemplo Mountinghole pernos m3.

Revisar tablas de pernos, tuercas (sensible a vibración), golilla de presión, tiene un sacado porque hace presión al sentido opuesto por lo que realiza agarre.

MountingHole:MountingHole_3.2mm_M3

Separador de PCB, entregan distancia en cada esquina, espaciadores. Hay de metal y de plástico, este último se usa con pegamento. En _Aliexpress_.

* Ej: Oficina de sonido subactuática.
Exportar 7 capas y el corte, todo en la misma carpeta.
* "Trazar", genera vectores.
* Ejecutar DRC para encontrar errores.
Archivos en .gbr
Importante que para enviarlo hay que comprimirlo.
* Enviar a JLCPCB.
* Gerber Viewer. Te permite ver las capas separadas.
* Cobre> Barniz> Placas de componentes con materiales blandos, existen opciones que expresa la página.

_Google Summer of Code_ ha apoyado OpenSCAD.

Development Snapbook, Nightly.

* Bambu Lab X1 Series.
* (página)  Thingiverse.
* UltiMaker.
* Josef Prusa. Checo. > (página) Printables.
* MakerWorld> MakerLab.
* Parametric Model Maker> Permite subir códigos de OpenSCAD.
  Permite utilizar modelos paramétricos y que uno puede editar sus variables.

Siempre hay que subir un archivo a una plataforma con una Licencia.

Lenguaje OpenSCAD es similar a Pyhton.
Modulo (module).
difference(){
tube(); ...
"true", "false".
Visualizador de openscad.

* Cantanta Santa María de Iquique (Quilapayún).
* OSKITONE (APC). Es opensource, está en github y fue diseñada en opeSCAD.

<> Code > HTTPS / Github CLI

* CLI: command line interface. API en la web, se puede usar en la terminal.

UNIX es antecesor de MAC y Linux.

Windows es distinto.

"sudo rm rf" > Elimina el usuario y el disco duro, peligroso nunca usar.

## Sobre terminales

* Homebrew (página). Manera de instalar en terminal administrador de bibliotecas. Permite instalar miniherramientas para optimizar cosas.

* terminal, cmd, powershell.
* Python es muy cercano a administrar el temrinal.
* chocolatey, winget (windows 10,11), donwloadable MSI. (Opción para Windows).
* "Brew install" MAC.
* _Automate the Boring Stuff with Python_ (libro).
* Donna Haraway.

### Github Desktop. _"Github without the struggle"._ Es mucho más ameno. "Clonar repositorio". Indicar carpeta dónde lo voy a clonar

No es recomendable utilizar Onedrive, Dropbox, Google Drive.

Bajar archivos "en este momento". En caso de cambios la carpeta (del PC) se conecta a la carpeta (en la nube) y uno debe elegir el 'commit'.

Git, herramienta. Para editar github en VSCode se tiene que instalar 'git'. Desde Github Desktop es más rápido editar directorios.

Extensión. TextEdit (Bloc de notas). "push", "commit" en Github Desktop.

1. Clonar nuestro 'fork' (1 vez)
2. 'sync' (sync fork) > Sincronizar ¡Sólo si estás 'behind'!.
3. 'fetch origin', Ver si ha pasado algo, 'pull origin' traer hacia mí lo de la nube.
4. 'pull'.
5. Editar carpetas
6. 'commit' + mensaje.
7. 'push'.

* Atom (github) Hasta 2023.
* Pulsar-edit.
* Visual Studio (sólo en Windows)
* Visual Studio Code o VS Code (para todos).
* "Word" no es un editor de texto porque le coloca cursiva a los textos.

Github desktop > preferencias (o File > Options en Windows)> Seleccionar "External Editor", sirve para editar nuestros archivos de código.

Visual Studio Code tiene un previsualizador de la página. Tiene que vivir la imagen en el repositorio para que se lea en caso de no tener internet. ¿Cómo tener un previsualizador en .md para VSCode? Añadir plugIn.

* PlugIns.
* markdownpdf.
* markdownlint.
* openSCAD.
* p5.js.
* better C++ Syntax.

Para adjuntar un archivo de imagen al repositorio y así citarlo en markdown: (./archivos/imagen.formato). para videos: embed, en html video en "<>" "</>" , con miniatura de youtube. Máximo 50MB, más de 100MB no deja. El texto en html para el video en el .md previsualizado de github quizás no aparezca, pero en el github.io/ sí aparecen como html. Github pages. html + CSS. "Transpilar".

Por lo general la web de github es para cosas macro.

.svg, huellas,---> footprints, clon.

¡Recordar siempre apretar CTRL+S para guardar!
