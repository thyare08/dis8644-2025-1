# sesion-11a

# ENCARGO 22: Documentación textual del proceso de ensamblado de UDPUDU

![UDPUDUIMG](https://raw.githubusercontent.com/disenoUDP/dis8644-2025-1/main/00-docentes/sesion-10b/archivos/udpudu-pcbRef.png)

![UDPSCH](https://raw.githubusercontent.com/disenoUDP/dis8644-2025-1/refs/heads/main/00-docentes/sesion-10b/archivos/udpudu-sch.png)

# Materiales necesarios
- Placa PCB del circuito UDPUDU (como en la imagen)

- Componentes electrónicos:

- 1x NE555 (U1)

- 1x Portapastillas o zócalo de 8 pines

- 1x Diodo 1N4007 (D1)

- 2x LED 5 mm (D2, D3)

- 3x Resistencias 1 kΩ (R2, R3, R4)

- 2x Capacitores electrolíticos (C4: 1μF, C5: 47μF)

- 1x Capacitor cerámico (C3: 100nF)

- 1x Interruptor (SW1)

- 1x Conector de 9V (J2)

- 2x Pines CAIMÁN para entrada (J1, J3)

- 1x Altavoz pequeño (LS1)

# Herramientas:

- Soldador y estaño

- Pinzas

- Multímetro (opcional pero recomendado)

# Pasos para el ensamblado

# 1. Preparación

- Verifica que tienes todos los componentes.

- Asegúrate de tener la PCB limpia.

- Ubica la imagen de referencia (como la de la serigrafía).

# 2. Montaje de componentes pasivos (resistencias y diodos)

Comienza por los componentes más pequeños:

- R2, R3, R4: coloca las resistencias de 1kΩ. Dobla las patitas, insértalas y suelda.

- D1 (1N4007): coloca respetando la orientación (línea gris hacia el lado del cátodo “K”).

- D3 (LED encendido) y D2 (LED de salida): también con la orientación correcta (lado plano del LED con el símbolo del cátodo).

✅ Acierto: soldar primero componentes pequeños evita obstáculos para los más grandes.
⚠️ Error común: no respetar la polaridad de los LEDs y el diodo. Revisa antes de soldar.

# 3. Montaje de capacitores

- C3: cerámico de 100nF, sin polaridad.

- C4 y C5: electrolíticos, respetar polaridad (el negativo está marcado con una franja).

✅ Consejo: marcar el lado positivo con un plumón para evitar confusiones.

# 4. Montaje del 555 y componentes más grandes

- Coloca el zócalo del 555 (U1) con la muesca mirando hacia el lado correcto (coincidiendo con la serigrafía).

- Inserta y suelda los conectores de entrada (J1 y J3), el conector de alimentación (J2), el interruptor SW1, y el altavoz LS1.

✅ Acierto: usar zócalo facilita reemplazar el IC sin dañar la placa.
⚠️ Error común: soldar el zócalo al revés; eso puede causar confusión al insertar el 555.

# 5. Inserción del IC 555

- Una vez que todo esté soldado, inserta con cuidado el NE555 en el zócalo.

# 6. Pruebas iniciales

- Conecta una batería de 9V.

- Verifica que el LED D3 se encienda al encender el interruptor.

- Conecta brevemente un cable CAIMÁN entre J1 y J3: debería sonar el altavoz y encender D2.

✅ Acierto: probar por secciones permite encontrar errores fácilmente.
⚠️ Error común: si no suena el buzzer, revisar polaridad del capacitor C5 y la conexión del altavoz.

# 7. Aprendizajes y consejos

- Siempre probar componentes antes de soldar, especialmente los polarizados (diodos, LEDs, electrolíticos).

- Revisar bien la serigrafía de la PCB ayuda a evitar errores de montaje.

- No apresurarse al soldar; un buen punto de soldadura es brillante y limpio.

- El diseño incluye un toque lúdico (la silueta de un animal), lo cual hace más atractivo el aprendizaje de la electrónica.

# 8. Resultado final

- Una vez terminado, tendrás un circuito funcional que:

- Se alimenta con 9V

- Emite un sonido breve y una luz cada vez que se activa con un pulso externo

- Este es un gran ejemplo de cómo integrar diseño y electrónica básica en un solo proyecto educativo.

# ENCARGO 23: Documentación visual del proceso de ensamblado de UDPUDU

Las fotos que subire no son de autoria mia ya que, como comente no asisti a la clase pero de igual manera me informe con varios compañeros para poder saber que hicieron en la clase.

![udpudu00](https://media.discordapp.net/attachments/1318882679659171892/1372987354020577431/IMG_7488.jpg?ex=682d62de&is=682c115e&hm=cb81dfef37076724ecd010b6c60a24b332eb3c42e5507f38dc6cb1810f5d4b33&=&format=webp&width=859&height=544)

![udpudu01](https://media.discordapp.net/attachments/1318882679659171892/1372972648065138829/20250516_122212.jpg?ex=682d552b&is=682c03ab&hm=c4f03c4eaf30b9451d9ca0b06a229973758799c347510366e6969bdb918d6ef0&=&format=webp&width=725&height=544)

![udpudu02](https://media.discordapp.net/attachments/1318882679659171892/1372977746744967229/IMG_2286.jpg?ex=682d59eb&is=682c086b&hm=799318e90865326e674e7a46970f855333a467f63a94f1e1c423f6c5819b36fd&=&format=webp&width=736&height=552)

![udpudu03](https://media.discordapp.net/attachments/1318882679659171892/1372978615909879869/IMG_1392.jpg?ex=682d5aba&is=682c093a&hm=94711f9d4bd5cadd8ddd1260b7697d1eb6896727f0c57511f48f795c08324da0&=&format=webp&width=408&height=544)

![udpudu04](https://media.discordapp.net/attachments/1318882679659171892/1372987063162507395/IMG_7516.jpg?ex=682d6298&is=682c1118&hm=1625613a83fe0090a68d67ae1c5dd5c92cdf832035eef4654f5fbd5cc4458c8f&=&format=webp&width=736&height=552)



