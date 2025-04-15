# sesion-05b

viernes 11 de abril 2025

## Dos tipos de componentes: para PCB y para Panel

Los componentes para pcb están pensados para conectarse directamente en las placas (pcb o perfboard)

Potenciómetro para PCB

![pot pcb](./archivos/pot_pcb.jpg)

Potenciómetro para Panel (incluye un hilo para colocar una tuerca, y debe llevarse con cables)

![pot panel](./archivos/pot_panel.jpg)

### Placa perforada

Placa que viene perforada de fábrica para fijar componentes de forma más permanente. Hay de distintos tamaños y colores.

Algunos traen los hoyitos aislados.

![perfboard con hoyitos aislados](./archivos/perfboard_isolated.jpg)

Otras los traen pre-conectados

![perfboard con hoyitos interconectados](./archivos/perfboard_line.jpg)

Así se ve una perfboard terminada por encima (top)

![perfboard top](./archivos/perfboard_top.jpg)

Así se vería por debajo (bottom)

![perfboard bottom](./archivos/perfboard_bottom.jpg)

En una perfboard deben ser conectados los componentes a través de cables. Se puede hacer poco a poco, o también planear con antelación

![perfboard dibujo](./archivos/perfboard_draw.jpg)

Es MUY importante no soldar los IC (como el 555) de forma directa a la perfboard, sino que instalar una base DIP como intermediaria. Éstas permiten reemplazar el componente con facilidad sin necesidad de desoldar en caso de falla. ¡Es más fácil soldar que desoldar!

En la imagen hay una base DIP de 20 pines (DIP-20). DIP significa Double In-Line Package

![perfboard dibujo](./archivos/basedip.jpg)

Conocer y escoger los conectores correctos y precisos se aprende con la práctica. Inicialmente utilizaremos cable directo soldado a a la PCB.

![perfboard cableado](./archivos/perf_wiring.jpg)

Con el tiempo lograrán planificar y elegir conectores apropiados para cada tipo de señal.

![perfboard final](./archivos/perfboard_label.jpg)

### Soldar

Para soldar hay que seguir 4 pasos:

1. Pasar alambre o cable a través de PAD
2. Calentar alambre Y pad al mismo tiempo con el cautín (3 seg)
3. Sin retirar el cautín, insertar soldadura
4. Sin sacar cautín, sacar soldadura
5. Esperar 3 segundos, luego retirar el cautín

![como soldar](./archivos/comosoldar.jpg)

Puedes visitar el [manual para soldar](./archivos/nasa_soldar.pdf) con recomendacioens de la NASA

## Video tutoral para soldar placa perforada (en inglés)

[<img src="./archivos/soldar_yt.png">](https://youtu.be/3N3ApzmyjzE?t=228)
