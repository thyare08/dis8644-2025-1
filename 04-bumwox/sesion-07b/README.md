# sesion-07b

__kicad__

para tener mejor nocion de los elementos de kicad revisar el repo  de [00-libsKicad-teee](https://github.com/bumwox/dis8644-2025-1/tree/main/00-libsKicad-teee) la cual descargamos papra tener mas facilidad para verla y no sea engorroso usarlo directamente con github

mejoramiento del proceso para usar kicad

- ajustes de plano: cambiar tamaño del plano en el que estamos trabajando (canvas)
- siempre vamos a partir por el esquematico (archivo sch)
- para cargar bibliotecas de simbolos locales: preferencia > gestionar biblioteca de simbolos > nos saldran todos los simbolos del esquematico, dar click al simbolo de la carpeta y en agregar simbolos buscamos 555_ordenado y la seleccionamos

![image](https://github.com/user-attachments/assets/797fa2a9-af0d-4fe2-95ed-0eb01e126942)

- para agregar campo de huellas hay que seleccionar f
- las garrapatas se llaman ___DIP___ y corresponde a dual in-line package
- bloques terminales para la huella del parlante
- socket para colocar caimanes, como resistencia exp
- se pone un LED aparte para poder probar si la placa esta recibiendo energia
- hay dos categorías de switch, directos a la placa y otros que son para montar en carcasa
- una forma de proteger la placa es agregar un diodo, para que no muera tambn el 555, solo hace que no pase nada
- library son los simbolos del esquematico, modules son las huellas de estos simbolos

## 16. - 17. cotizar udpudu

cotice el udpudu hecho en clase y terminado por missa

![image](https://github.com/user-attachments/assets/3a8bb83d-9fe7-4244-8456-8e72bf272d5d)

- cambie las capas que queria que tuviera la placa, 2 > 4
- deje el material base FR-4 ya que queria que la placa fuera azul y las demas opciones de meteriales tenian el azul agotao
- cotice la placa para 30 personas
- los demas parametro que aparecen en la imagen los deje por default 

![image](https://github.com/user-attachments/assets/998249af-35c7-4086-84cc-d9f37b4f1682)

- como mencione anteriormente cambie la placa al color azul
- cambie el tipo de material pasando de FR4-Standard TG 135-140 a FR-4 TG155, ya que lo considero mas resistente
1. FR-4 TG155: es una designación de un tipo de material usado comúnmente en la fabricación de placas de circuito impreso donde FR-4 indica un material laminado de epoxi reforzado con fibra de vidrio que es resistente al fuego y TG155 se refiere a la temperatura de transición vítrea del material, que es de 155°C
- por ultimo cambie el acbado de la superficie a HASL sin plomo, ya que es mas ecologico y cumple con regulaciones ambientales como RoHS
2. HASL sin plomo (Hot Air Solder Leveling): es un acabado superficial para placas de circuito impreso (PCB) que utiliza aleaciones de soldadura sin plomo en lugar de la aleación de estaño-plomo tradicional
3. RoHS (Restriction of Hazardous Substances): es una directiva de la unión europea que regula el uso de determinadas sustancias peligrosas en productos eléctricos y electrónicos
- lo demas lo deje por default

![image](https://github.com/user-attachments/assets/65df260f-6cd8-4f4f-a19f-7527ff298eb0)

- cambie las opciones de envio, de DHL Express a Global standard direct line ya que es mas barato

![image](https://github.com/user-attachments/assets/d34349ae-1d37-4653-8dc1-98bd1aa8498e)

- por ultimo los detalles del pedido y precio final

__pagina para encargar las placas__
- [JLCPCB](https://cart.jlcpcb.com/es/quote?orderType=1&homeUploadNum=c58a645f2e6d4afd9ebf1ed4eaa8ef57&businessType=example&fileName=udpudu_gerber.zip&_t=1748497005294&spm=Jlcpcb.Instantquote.1005&up_spm=Jlcpcb.Loginpage.1003)
