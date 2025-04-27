# sesion-06b

No hay clase por feriado.

## encargo-12: instalar kicad

Instalar software _Kicad_ en su computador personal, incluir información sobre la instalación, la versión que están usando, el sistema operativo que usan, los idiomas que están usando, las carpetas en donde instalas la app y cualquier otra biblioteca o archivos relacionados, además de cualquier otro dato relevante.

APUNTES VIDEO: <https://www.youtube.com/watch?v=hn_pk0nWDns>

* Anoté apuntes relacionados al video proporcionado por los docentes.

Programa _open source_ gratuito especial para el diseño de PCBs, opciones a esto es _Eagle_ y _Altium_

_Workflow_: flujo de trabajo.

* "Crear proyecto" > nombrar
Se crea una carpeta .sch (esquemático) y .pcb (forma física).

Primero se abre el .sch, tiene el nombre del archivo y el nombre de _Kicad_.

* Hay que variar el zoom regularmente, hay un _hotkey_ para esto, en preferencias y atajos o _hotkeys_ aparece la configuración de este comando.

_Protools_ (para audio)

* Configurar _touch pad_ se configura en: "Utilizar _touch pad_ para panorámica".

### Parámetros del bloque del título

- Tamaño (carta, a4, tabloide, etc).
* Orientación (vertical, horizontal).
* Título.
* Compañía.
* Comentario 1, 2, 3, 4.
* Archivo de descripción del diseño de hoja.

Esto queda declarado en la parte inferior derecha del documento.

Diseño de _Atari Punk Console_, 555 circuito _timer_ se configura para que sea astable o una configuración monostable.
Revisar 555 _timer circuits_
<https://www.555-timer-circuits.com/>

* Añadir componente: objeto físico representado en dibujo (puede tener formas distintas en físico, pero lo que importan son sus propiedades).

Se selecciona y se cargan "librerías".

En las librerías están todos los componentes, por ejemplo _resistor_. A la derecha se previsualiza la forma que tiene el dibujo, de manera que nosotros podamos leerlo.

Resistencia tiene 2 R, la primera R es un nombre por ejemplo, R1 R2 R3, se hace automáticamente, no es necesario alterarlo. Se pueden cambiar los nombres de los componentes.

Cuando uno busca un chip 555 salen diferentes esquemáticos en diferente orden, buscar el más pertinente para nuestro circuito. Visualizar el orden de los pines.

Escribiendo C, aparecen condensadores polarizados o condensadores no polarizados.

* Crear esquema > abrir esquema > añadir componente/símbolo > ¿Existe el componente? Sí/No > Si existe lo ubicamos, si no existe lo modificamos.

Conectar alimentación: "jack.DC" _barrel jack switch_, diferentes formas, tiene 3 ranuras, fijarse en el nombre del componente, el diámetro.

Buscar _switch_ para botones pulsadores switch spst "_single pole single throw_" cuando se suelta no cae en ninguna parte, spdt "_single pole double throw" cae en dos puntos distintos, estos se usan para el ON/OF también está sp3t y dpdt "double pole double throw".

* ¿Cuántos componentes de cada uno necesito?

Colocando el mouse arriba y presionandoc "C" se copia, se arrastra y se pega. Si tengo un componente encima de otro se tiene que clarificar la selección entre múltiples opciones.

"_Potentiometer_" o POT Potenciómetro, reostatos. Símbolo américano "R_POT US" línea en zig-zag y europeo "R_POT" bloque.

Para mover un componente "M", se arrastra y se clickea, también se puede rotar en medio de la selección con "R", se puede realizar con todos los componentes.

Para borrar se coloca el mouse encima y se unsa "Supr" (suprimir), en Mac es "Fn" + retroceso "<-".

Parlante de 8Ω, los parlantes suelen poseer cable rojo y negro, se les busca por "_speaker_".

"_Connector_" conn_01x01 (siendo el primer número el n° de filas y el segundo el n° de pines que posee) 01x02 01x03, 04, 05, 06, 07 suele demonminarse "_male_" o "_female_". Ejemplo sería "Conn_01x01_Male".

Voltaje: VCC genérico de 5 o 9V, dos pilas de 1.5V quedan en 3V. 0V o GND, GND significa _GROUND_ o TIERRA. Tierra analógica, digital, de power, de referencia, de señal, tierra real, de chasis ¿En qué se diferencian?

Se ven dos líneas, una verde y una azul. La azul sirve para separar cosas por dibujo, la verde sirve para hacer conexiones eléctricas. Cada click es una curva, ¡No se arrastra!.

La función de un esquemático es que sea legible y claro. Que se vea ordenado.
Con doble click se cierra la conexión, si sale un cuadrado significa que está mal hecha, no se puede sobrar la conexión, suele salir un cuadrado encima de la ranura, hay que ser preciso.

Punto verde: hay conexión de entre distintos puntos que se entrelazan, si no lo hay, no hay conexión. El punto verde va en el entramado del cobre, deben compartir línea de cobre. En un esquemático las líneas no son líneas sino puntos, para los electrones es una distancia ínfima.

¿Cómo se mueven varios componentes al mismo tiempo? Si seleccionamos un bloque se mueven todos los componentes seleccionados. "G" de _grab_ se puede mover un componente y se mantiene conectado el cable. Si ponemos G sobre una malla hay que presionar click derecho y "agarrar".

Orientación, se pueden reflejar los componentes según eje x y eje y presionando "X" e "Y" respectivamente.

Entramado de puntos que son el mismo punto cuando coloco un GND (_ground_), solo funciona con los componentes que son de "_power_", "_power flag_".

Se puede puentear 2 y 3 o se puede colocar X "símbolo de no conexión", ese pin no hay que conectarlo, estamos seguros de que aquella ranura no conecta con ninguna parte. Es una decisión de que algo no esté conectado, no igual a cuando es un error, una línea que no está conectada a ninguna parte, los circuitos deben ser para _Kicad_ lazos cerrados.

"LED". Ahora se nombran valores y cantidades.

Valor de componente se pone encima con la letra "V" de _value_ o valor, así se puede establecer si coloco 1k a una resistencia. Pueden ser valores referenciales, no necesariamente reales. No es necesario ponerle Ohm a una resistencia porque se asume que está medido en Ohms.

Debe colocarse los mismos tipos de valores para los componentes, no se puede colocar una k minúscula con una K mayúscula porque al final el programa nos entrega una lista en donde se diferencian ese tipo de detalles.

En _Getting started_ de _Kicad_ aparece el _Workflow_

* Anotar Esquemas

_E-eschema_: Anotar esquema, si está todo en verde está todo bien. El programa enumera los componentes del diagrama. Así podemos utilizar una lista de materiales para poder comprarlas en una tienda de electrónica.

* Realizar control de reglas

El botón de bicho "_bug_" nos muestra cada error que podamos tener en nuestro circuito en relación a nuestros componentes. En realidad no son errores sino avisos.

Por ejemplo: "el pin 1 de tal componente no está conectado a GND".

"Los pines de alimentación no están alimentados".

Uno puede ver la información de cada componente con la letra "E". Orientación, tamaño, nombre.

Resistencias medidas en watts además de ohms.

* Asignar huellas a símbolos de esquema.

Huellas y símbolos no son lo mismo. Símbolo no es algo real, son denominaciones semánticas, son íconos.

Cargar librería de huellas. Asignarle una huella en la placa, quiere decir, el espacio que utiliza en dicha placa.

Aparecen muchas librerías a la izquierda, al centro los componentes de nuestro diseño y a la derecha las huellas filtradas. Además una ventana negra que muestra los componentes que seleccionamos en el filtro. Hay que medirlos en mm. "C_Rect_L7.0mm_W4.5mm_P5.00mm"
Con W de ancho, P de _pitch_ es la distancia que hay entre las patas.
10U electrólitico, radiales "CP_Radial_D6.3mm_P2.50mm", "LED_D5.0mm",
"Barrel Jack", _Speaker_ buscar capacitor, por ejemplo el _connector_ _pinheader_ de 1.5 Pinheader Horizontal, Vertical, Vertical en SMD, Ejemplo: PinHeader_1x02_P2.54mm_Vertical. Se puede referenciar símbolo, pines, entre otros datos.

Resistencias: Shift + click seleccionamos varias, se puede buscar en librerías en _resistor_, componente en _true hold_. Resistencia de 1/4 watt, medición en mm. SMD, THT. Ejemplo: R_Axial_DING207_L6.3mm_D2.5mm_P10.16mm_Horizontal. Si hago doble click con todas las seleccionadas se aplica la misma huella a todos los componentes.

Potenciómetro, el que comunmente se vende es Potentiometer_Alps_RK163_Single_Horizontal.

_Botton switch_, Botón pulsador SW_PUSH_6mm_H5mm se diferencian en la altura del botón.

_Switch_ ON/OFF o _push_ DIP switch SW_DIP_SPSTx01_Slide_6.7x4.1mm_W7.62mm_P2.54mm_LowProfile.

555, buscador de librería "_package_" o "_houssings_" entre versión 4 o 5 les cambiaron el nombre "_resistor_" y "_resistors_". _Package_ DIP de 8 pines _width_ de 7.62mm los LongPads son más fáciles de soldar que los comunes: DIP-8_W7.62mm_Socket_LongPads.

* Aplicar > Guardar Esquema > Continuar.

Esquemático y medir el objeto en persona y aplicar la huella, también se pueden descargar huellas o se pueden crear.

¿Existe la huella? No> se puede crear, se puede buscar en internet.

Click derecho en componente> editar huella> y se aplica.

Generar _Netlist_. Genera una lista de redes, le coloca un nombre a cada uno de nuestros cables.}

Ejecutar _PCBnew_ > "_Update PCB from schematic_".
Si quiero volver a modificar la esquemática, hay que volver a llamarlo y ajustar la actualización de huellas.

Definir el tamaño que tendrá nuestra placa desde ya, aparece una cuadrícula, puede ser por ejemplo de 5mm que es la cuadrícula más ancha, es parte de la interfaz de navegación. Se puede asignar el _hotkey_ de + y - (zoom).

Administrador de capas, una placa PCB está compuesta por capas. Baquelita o Fibra de vidrio.
Capas: lineas de cobre _front_ y _back_. Líneas blancas de componentes, nombres y texto.

Lámina verde encima del componente, es una máscara de protección de soldadura, soporta más calor del que suele generar un cautín.

Necesitamos una capa de corte que es el tamaño físico, la capa arriba y abajo. Figura de línea.

_Edge Cuts_
Parto del 50 (por ejemplo de 50 a 150). Placa física sería de 5 x 10 cm. Arrastro los componentes, se puede cambiar visualemente en el adminsitrador de capas, se desactivan las líneas aéreas.

Generalmente se coloca el integrado en el medio porque es el corazón del circuito.
En Mac Command + "F" de _find_ se puede hallar por ejemplo el switch n1, n2. Así se ajusta físicamente.

Hay que verificar que las distancias sean ergonómicas y aptas para la utilización del chip, existe una regla, herramienta regla. por ejemplo "<------> 14mm". También se puede ocupar como guía la capa _margin_ sirve para dibujar líneas de referencia. Sirve para ubicar, por ejemplo, el centro de la capa.

* Modificar> actualización> "Mantener los símbolos existentes".

Click derecho> cambiar huella, sin embargo borra cambios (no recomendado) mejor editar huellas atrás y luego actualizar.

Una placa de 10x10cm es más barata enviarla a hacer a China.

Criterio de distribución, si voy a colocar componentes directos a placa es importante que queden en la posición que quiero que queden finalmente, ubicar inicialmente los componentes que quiero sí o sí que tengan una ubicación específica. Hay que revisar el esquemático para entender una composición coherente de la placa. Denominación de pistas  a los cables.

* Dibujar pistas.

Enrutar pistas, que la pista por defecto sea roja y de 0.25mm, una placa a mano que sea de ancho 0.7 u 0.8mm. Pista > _pre-defined size_, y editar tamaño, así entonces se dibuja, línea roja, dibujo de cobre. Placa de un solo lado.

VCC, el programa y el encargo a China aguanta colocar varias conexiones, sin embargo, cuando uno taladra manual puede romper la pista, lo que es recomendable es dibujar un canal.

Vía, pequeño pedacito de alambre que conecta la placa de arriba con la placa de abajo. En vez de ir horizontalmente va d euna placa a otra placa. Los "agujeros" son vías que van de una placa a otra placa, tienen tamaños predefinidos, por ejemplo 2mm y el taladro 1,2mm con la "V" agrego una vía, se tiene que seleccionar arriba que vía estamos usando una customizada o una predeterminada.

Ejemplo alimentación gruesa y resto de componentes conectados con líneas más delgadas, seguir líneas blancas recomendadas por el programa.

Autoruter o _autorouter_, puede determinar las rutas de la placa, sin embargo puede generar problemas, no es recomendable, además que enlazar y dibujar la placa no es un tema tan engorroso.

* ¿Cómo resolvemos que algo esté atravesado?

Retroceso, _backspace_ y cambiar la ruta, el dibujo lo aguanta pero puede ser arriesgado cuando hacemos una placa a mano. Con una cuadrícula más pequeña podemos tener mejor criterio para tomar estas decisiones.

Salvo que se usen señales de muy alta frecuencia, no hay problemas con circuitos que sean en línea recta, a los de alta frecuencia les cuesta doblar en aquellos circuitos.

Diseño de PCB paciente y de optimización.
La "V" de vía hace que se puedan atravesar las otras rutas.

Conectar GND: zona de relleno, ¿rellenar la capa de frente o de abajo? ¿Qué red se marca? con "B" se rellena.

* Formas de visualización, contornos de áreas rellenas

Ver, Visualizador 3D. Se puede mandar a hacer a China, se puede hacer a mano o se puede hacer en CNC, pero a considerar que a mano y en CNC las diferencias quizás no las aguante, es difícil hacer placas de 2 caras a mano, hay que considerar todo eso en el primer momento en el que diseñamos la placa.

Para previsualizar un objeto que no está en nuestro modelo 3D: "E" encima de un componente en la placa impresa hay que añadir un modelo 3D importado. Se descarga y se agrega.

Se puede hacer la placa impresa con el botón imprimir placa. ¿Qué capas voy a imprimir? ¿Me interesa la de cobre de adelante? ¿Me interesa la de abajo (verde)? ¿Me interesa la capa de texto?

* Escala 1:1 muy importante
* OUTPUT? ej: Monocromo?, marca pequeña?, sin marca de taladro?, real?.

Acetona, quitaesmalte, limón (suave). ¿Cómo funcionan las capas de las placas?

* Guardar como PDF (plugIn). ¿Cuándo va la cara invertida o cuando no?

Problema: me puede quedar invertido, vista inferior del circuito.
Ver> Voltear visualización de placa.

* Imprimir> imprimir invertido. Es fundamental y depende mucho de la técnica de nuestro diseño de placa, por ejemplo si va a ser por luz, o ser blanco sea negro o el negro sea blanco. Impresión en plancha.

* Guardar.

Para no perderse en la orientación podemos colocar una capa de texto, lo importante es en qué capa quiero que quede. Tamaño. Con la "B" se ajusta a la capa de la placa para transferirlo.

Importante agregar: un botón para añadir huellas. _Mounting hole_ M3 MountingHole_3.2mm_M3 agujero para enganchar, con tornillos, se puede descargar y añadir un modelo 3D con un tornillo. Se puede renderizar el modelo 3D, pero exige más. Perspectivas isométricas. Añadir el _mounting hole_ al esquemático.

* El programa genera una lista de materiales BOM. Y se puede abrir en formato excel .csv.

* JLCPCB se pueden mandar a hacer los PCB. LCSC Electronics Components. Se puede ajustar el envío.

Capas extras se pueden añadir más informaciones por ejemplo añadir una serigrafía.

Criterio de ancho de 0.6mm para hacerlos a mano para que no sea tan estrecho. Ancho de la pista.

## Terminología de PCBs

Se pueden importar dibujos externos, importarlas como borde a la placa PCB.

* _InkScape_.

### Glosario Terminología de diseño en PCB
<https://docs.google.com/document/d/1uwGN5jmR22pYjSk9IIKY-icggmpqQSC4HyakQe322rQ/edit?tab=t.0>

## encargo-13 Ver el documental _Sisters with transistors_

### Escoger artista favorita del documental y escuchar algún concierto o disco de ella

Tras visualizar _Sisters with transistors_ (2020) pude apreciar la calidad musical a la que se puede llegar mediante máquinas electrónicas pues las mujeres que aparecían documentadas fueron pioneras en este medio y dejaron un legado importante el cual podemos seguir a través del aprendizaje de dichas autoras. Como algunos comentarios y entrevistas decían la música electrónica con transistores es sino, un sonido no físico pero sí «del alma», es una «extensión» de la persona que puede modificar a detalle, un proceso que en su época fue visto con paternalismo por las figuras masculinas, pero que han trascendido en el tiempo por su extensa complejidad en el cómo nosotros podemos interpretarlos artísticamente. Sin duda cada una de estas músicas fueron capaces de expresar el arte de una forma sin precedentes y que se refleja en cada época de la historia reciente, ellas también fueron perspicaces pues al ser un sistema complejo que requería entendimiento muchos hombres obviaron este mundo y las mujeres supieron reinvindicarse por este mismo medio.

Considero personalmente que el aspecto más relevante en el ámbito músical es que cada una de estas pioneras lograron nuevas sensaciones a través de la música y que también fueron parte del cómo podemos graficar el sonido electrónco en medios artísticos de todo tipo, inclusive en los comerciales de televisión o en las películas.

Escuché _The Expanding Universe_(1980) de Laurie Spiegel y me gusta poder escuchar el ambiente que genera, reminiscencias de la electrónica y la naturaleza, precursora del _ambient_. La sensibilidad musical que genera es impresionante y me hace percibir el universo de manera sonora, es decir, la amplitud y la infinidad que puede llegar a tener está siendo interpretado de manera musical. Lo que más aprecio de estos temas es que a pesar de ser largos te enganchan en todo momento porque te inducen a sentir lo que en realidad se pretendía realizar cuando, en aquellos días en el que fueron creadas estas piezas musicales, se consideraba a aquellas mujeres autora como "locas" o como algo "sin ninguna relevancia" lo que resulta ser todo lo contrario y por eso se mantienen influyentes.
