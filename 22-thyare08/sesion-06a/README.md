# sesion-06a

15 de Abril de 2025.

 # Project-01 

  - Grupo 02:

    - Emilia Contreras
    - Katalina Riquelme
    - Thyare Santander.

 1. **Idea del proyecto:** Como grupo queremos crear un modificador de frecuencia capaz de cambiar el sonido original de nuestra Atari Punk Console con 3 pulsadores distintos que generan una frecuencia más aguda, una intermedia y una más grave. También logramos agregar un interruptor de dos tiempos que nos permite frenar la energía que alimenta el circuito de forma gradual apagándolo momentáneamente.

 2. **Propósito:** Objeto interactivo sonoro que permite la exploración auditiva de distintos tonos/frecuencias que varían en tanto graves como agudos.

 3. **Modificaciones:** Las modificaciones realizadas fueron 3 en total:

   - Entre el C1 y R_experimental_1 pusimos 3 pulsadores cuya frecuancia varía según el condensador cerámico conectado a tierra.
     
      1. **P1:** Está conectado a un condensador de 163n (C5). En este caso el cambio es más notorio cuando el LDR es estimulado con una fuente de luz constante. Frecuencia aguda.
      2. **P2:** Está conectado a dos condensadores de 474n (C6 y C7) en serie. Frecuencia intermedia.
      3. **P3:** Está conectado a un condensador de 474n (C8). Frecuencia grave.
    
   - También agregamos un interruptor (Int1) de dos tiempos; en el tiempo 1, aunque el circuito esté conectado a la batería, logramos que se detuviera el paso de energía apagando el el circuito de manera gradual.

   - En la R_experimental_2 pusimos una resistencia de 330 Ω que según notamos genera una frecuencia más aguda que nos llamó más la atención que con otros resistores.

   4. **Circuito esquemático original y modificado:**

APC original.

![APC (1)](https://github.com/user-attachments/assets/f159e8e6-ec75-41dd-90de-6b3f900927b8)

APC modificado.

![APC_modificado](https://github.com/user-attachments/assets/245399b7-14c2-4169-bdf0-22ac388f3cbf)

 5. **Fotografías de protoboard con APC modificado:**

Foto 1.

![1](https://github.com/user-attachments/assets/427899fe-6775-4b6d-a840-1eca45d55b9b)

Foto 2.

![Foto_1](https://github.com/user-attachments/assets/27a43fc3-e569-41dc-8a6c-d6ad02228f10)

  6. **Videos de potoboard con APC modificado:** 

  Video Atari Punk Console modificada 1.

https://github.com/user-attachments/assets/2bb049fe-d00a-4fb9-8db2-486fe020fc69

Video Atari Punk Console modificada 2.

https://github.com/user-attachments/assets/1dfc053f-26e3-40d8-8d1e-b993af6207fa

   7. **Bill of Materials:**

| Componentes               | Nombre                     | Valor | Cantidad |
|---------------------------|----------------------------|-------|----------|
| Resistencias              | R2, R3                     | 1kΩ   | 2        |
| Resistencia               | R4                         | 33OΩ  |          |
| Condensador Cerámico      | C1, C2, C3, C4, C6, C7, C8 | 474n  | 7        |
| Condensador Cerámico      | C5                         | 163n  | 1        |
| Condensador Electrolítico | C9                         | 100uf |          |
| LDR                       | R1                         |       | 1        |
| Chip 555                  | Chip1, Chip2               |       | 2        |
| Jumpers                   |                            |       | 25       |
| Pulsadores                | P1, P2, P3                 |       | 3        |
| Caimanes                  |                            |       | 2        |
| Interuptor                | Int1                       | 250V  | 1        |
| Batería                   | Batería                    | 9V    | 1        |
| Altavoz                   | LS1 Speaker                | 8Ω    | 1        |
| Protoboard                |                            |       | 2        |

# Encargo 12: Instalar Kicad
  - Versión: 9.0.1
  - Sistema operativo: Sistema operativo de 64 bits, procesador basado en x64
  - Windows: 11
  - Ubicación de la aplicación: Este equipo > Archivos de programación > Kicad

![Captura de pantalla 2025-04-28 135858](https://github.com/user-attachments/assets/2fbc7bbc-632c-4d6d-9034-9beff0f7d770)

# Encargo 13: Ver documental Sisters with transistors
  - Mis artitas favoritas fueron Delia Derbyshire y Bebe Barron
  - Disco escuchado: Standard Music Library: Electronic Music de Delia Derbyshire, me parece relajante, divertido y tormentoso, con toques misteriosos en algunas partes, es increíble los sonidos y las emociones que puede generar. Además siento que son sonidos suaves y a veces fuertes, puede deberse a que ella era violinista
