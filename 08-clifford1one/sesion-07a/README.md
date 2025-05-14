# sesion-07a

### encargo 14

![esquemático kicad del APC](tme-07a-schApc.png)
este es el esquemático del circuito base Atari Punk Console.

![error que me tira](tme-07a-schError.png)
al ejecutar el EDR, me tira esos errores.

busqué en internet, y según [este foro](https://forum.kicad.info/t/erc-falsely-reporting-pin-not-connected/32455/2) es posible que se deba a que algunos elementos no están alineados con la grilla.

Intenté alinear los elementos a la grilla pero sigue saliendo el mismo error.

![error que me tira](tme-07a-sch-lda.png)
este es el esquemátio hecho en kicad del circuito LDA. Basado en el circuito encontrado en la página <555-timer-circuits.com>

![error que me tira el esquemático del LDA](tme-07a-ldaError.png)
mi tira el mismo error, lo atribuyo a la misma causa que en el caso anterior, ya que pareciera no coincidir aquellos componentes que causan errores.

basado en el circuito [DARK DETECTOR](https://www.555-timer-circuits.com/dark-detector.html)
