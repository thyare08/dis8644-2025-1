# Proyecto 01 

### Grupo 6 

Antonia Fuentealba

Sofía Pérez

Félix Rodríguez

Izhak Villegas


### PREMISA/PLANTEAMIENTO

¿Cómo podríamos modificar un APC para que sea lo más parecido posible a un instrumento musical tradicional?

En este proyecto nos planteamos la idea y la duda de cómo las frecuencias de las notas musicales podrían ser replicadas, a través de un circuito electrónico a partir de un _Atari Punk Console_.

¿Cómo se genera una nota musical?

Una nota musical es una vibración del aire a una cierta frecuencia (medida en Hertz). Por ejemplo, la nota La (A4) vibra a 440 Hz.

La APC genera ondas cuadradas con frecuencias variables. Esas ondas sonoras entran en un altavoz, el cual vibra a esa frecuencia, y nuestro oído lo percibe como una nota. 

Es por esto que nuestra decisión fue modificar el APC  para generar notas musicales a través de cables que conectan ondas eléctricas de distintos objetos, ya sean orgánicos o metálicos, simulando de esta forma una especie de teclado, que gracias a la suma de resistencias genera una frecuencia más grave o más aguda dependiendo del objeto que transmite la onda. Esto a través de un circuito que sería astable, debido a sus estados de on/off, al momento de presionar botones y accionar los clables en contacto con objetos. Además es un circuito robusto, que no es frágil en su fisicalidad, ya que cuenta con una carcasa exterior impresa ne 3d que protege el circuito solsdado en la pcb.


“Cada nota musical tiene una frecuencia principal, que indica cuántas veces por segundo vibra el elemento que la produce. La frecuencia producida por un temporizador 555 en modo astable depende de los valores del condensador (C) y dos resistencias (R A  y R B )”
Instructables. (2024, 6 marzo). 
Simple Electronic piano. Instructables. https://www.instructables.com/Simple-Electronic-Piano/ 


Esta relación es:

![formula frecuencia](https://github.com/user-attachments/assets/a927dec7-da5b-4a46-ba7b-c661a13953b0)


### ANATOMÍA FÍSICA, DIAGRAMAS, ILUSTRACIONES, TEXTO.

### CAJA NEGRA (ANATOMÍA FÍSICA)

## Teclado musical APC

Cuenta con una carcasa, con 5 orificios (sin contar el parlante ni el conector a la batería), por donde salen cables que se conectan a caimanes y a su vez, a objetos metálicos y orgánicos, también un botón, cables y un potenciómetro que, al accionar cada uno de estos, genera una frecuencia distinta, la cuales son capaces de oírse a través de una bocina o parlante.
La carcasa contiene el circuito soldado a la placa perfboard con todos los componentes utilizados (BOM) 

[Imágenes del teclado musical y sus partes]

![objeto_impreso](https://github.com/user-attachments/assets/6cefe40c-f04d-4942-ad06-59c471b750db)

![objeto_impreso(2)](https://github.com/user-attachments/assets/a9d3763a-ff72-4b65-8ec3-7df49ac4e816)

![objeto_interior](https://github.com/user-attachments/assets/03c8000e-0451-456f-9254-ddd9455dddd3)


### DIAGRAMA

A continuación se presenta el esquemático realizado para la construción del circuito e ilustraciones del planteamiento de cómo sería esta esquematización.

![proceso esquematico](https://github.com/user-attachments/assets/efa2b254-972b-4659-a288-a0179d86cc8a)

![proceso esquemático 2](https://github.com/user-attachments/assets/0f6e6ea2-a143-4246-bc55-a771e96a44b0)

![esquema PCB v01](https://github.com/user-attachments/assets/7bd40cd4-ea5f-4d39-ab66-42cd65187ce7)

![atariPunk_tinkercad](https://github.com/user-attachments/assets/b9c7a5fb-ebcf-4578-bf73-661e21ace227)


### BITÁCORAS


**Bitácora Anto**

![proceso esquematico](http://github.com/felix-rg416/dis8644-2025-1/blob/main/19-felix-rg416/sesion-06a/archivos/bit%C3%A1coras/anto.feuntealba/bitacora.anto.01.jpeg)

![ilustraciones+pauta](https://github.com/user-attachments/assets/d9cf7cdb-72ed-40ac-83de-da013afd2faf)

![experimentaciones](https://github.com/user-attachments/assets/a57aadb4-f099-4764-8776-6155a9fbd3c1)

![esquemático+resistencias](https://github.com/user-attachments/assets/8d21b44e-217e-4f1e-8ace-e8740c008f11)

![diagrama_de_flujo](https://github.com/user-attachments/assets/0a261737-c85c-4d27-971f-a1185fb84180)


**Bitácora Sofía**

![bitácora( 1)](https://github.com/user-attachments/assets/308d73b3-f04f-4ee4-b46c-71aef1f205b1)

![bitácora (2)](https://github.com/user-attachments/assets/a54c759f-bac9-443e-8253-7e9f78df3693)

![bitácora (3)](https://github.com/user-attachments/assets/b6a5a372-3fe6-46d3-9e5a-aba47dcb8586)

![bitácora (4)](https://github.com/user-attachments/assets/5beb6233-d07a-400c-8922-deabe9f41276)


**Bitácora Izhak**

![bitacoraa(1)](https://github.com/user-attachments/assets/06cbf094-a9fa-44b5-87fa-650e759eabd5)

![bitacoraa(2)](https://github.com/user-attachments/assets/815f0466-ced7-4b66-97cc-6851563e4a50)

![bitacoraa(3)](https://github.com/user-attachments/assets/47a7b342-b060-4438-a8bc-2e5703b43a73)

![bitacoraa(4)](https://github.com/user-attachments/assets/f74de39b-bef5-4579-8424-3f14ba285eb7)

![bitacoraa(5)](https://github.com/user-attachments/assets/c6b54ba0-879a-471b-b8ae-ae4732195bc2)

![bitacoraa(6)](https://github.com/user-attachments/assets/b74d0fad-4f96-480a-8419-d0bd0416c4f9)

![bitacoraa(7)](https://github.com/user-attachments/assets/b7f42ee8-18b5-47a8-b49b-ed2d7ca859a8)

![bitacoraa(8)](https://github.com/user-attachments/assets/eca564ee-980d-4eb8-9bf2-099fae8443c9)

[Bitácora y proceso Félix]

![pcb-b 01](https://github.com/user-attachments/assets/9e0722f8-1cba-4608-b3e8-b46a80050a03)

![pcb-b 02](https://github.com/user-attachments/assets/08aa160f-f32e-4c70-8910-ef2a5756bd00)

![pcb-b 03](https://github.com/user-attachments/assets/3692d526-e061-493c-bda7-4fcf1c285bd3)

![pcb-b 04](https://github.com/user-attachments/assets/2d4d658b-507f-4b8d-8191-4c719357a0cf)

![pcb-f 01](https://github.com/user-attachments/assets/a9feff96-f1c3-4061-96da-79095294b415)

![pcb-f 03](https://github.com/user-attachments/assets/0c6f8559-4a3a-4312-9c8b-f48caa01b51e)

![pcb-f 04](https://github.com/user-attachments/assets/be324029-0bbd-4957-a359-221dfb8833fd)

### PROCESOS

![collage](https://github.com/user-attachments/assets/fdcaa42d-2d9e-4889-bf8a-62206cc4c7d6)

[Videos de muestra del proceso en _Proto_]

https://github.com/user-attachments/assets/790efdef-d78c-4d19-b25d-af472468af7d

https://github.com/user-attachments/assets/fc261a51-aa6d-4029-83d4-fa57e76a6de4


### ESQUEMÁTICO ELÉCTRICO, BILL OF MATERIALS, CITAS Y REFERENCIAS

![esquemático final](https://github.com/user-attachments/assets/2b33f657-323f-4d00-a9f6-1db51bee0faa)

### BILL OF MATERIALS (B.O.M)

| Tipo                  | Cantidad | Nombre                  | Valor      |
|-----------------------|----------|-------------------------|------------|
| Perforated board      | 1        | PB                      |            |
| Batería               | 1        | BAT.                    | 9 V        |
| Resistencias          | 8        | R1, R2, R3, R5, R6, R7, R8 | 1k      |
|                       |          | R4                      | 10k        |
| Condensador cerámico  | 3        | C1, C2, C4              | 100nF      |
| Condensador 
  electrolítico         | 1        | C5                      | 100uF      |
| Condensador           | 1        | C3                      | 470nF (474)|
| Jumpers               | 12-17    |                         |            |
| Bocina                | 1        | Speaker                 | 0.5W/8Ω    |
| Caimanes              | 5        |                         |            |
| Circuito integrado    | 2        | Chip 1, Chip 2          | 555        |

Para nuestro proceso nos referenciamos en el piano electrónico creado por Joshua Brooks.

"La electrónica puede producir sonidos muy fácilmente con solo unas pocas piezas".

https://www.instructables.com/Simple-Electronic-Piano/ 

### CONCLUSIÓN 

Finalmente a la hora de probar por primera vez nuestro circuito nos dimos cuenta que no funciona
¿qué errores hay?, ¿son solucionables?, ¿se puede llegar al resultado deseado?
Pedir retroalimentación.
