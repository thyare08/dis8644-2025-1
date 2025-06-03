# sesion-12b

##  Sitios Recomendados para Comprar Materiales

Aquí tienes algunas páginas útiles para adquirir componentes electrónicos usados en este proyecto:

-  **LEDs y Cinta Píxel LED**  
  [https://www.demasled.cl/](https://www.demasled.cl/)

- ⚙ **Motores y Componentes Electrónicos**  
  [https://afel.cl/](https://afel.cl/)

-  **Controlador de Motores - Puente H L298N**  
  [https://mcielectronics.cl/shop/product/controlador-de-motores-puente-h-l298n-25508/](https://mcielectronics.cl/shop/product/controlador-de-motores-puente-h-l298n-25508/)

## Encargo 3/06

- Traer 3 ideas, ordenadas de mejor a peor, explicadas de forma textual. concentrarse en el lenguaje, los rangos de operación, el uso, no partir desde un chip en particular.
traer diagramas y dibujos por cada una de las 3 Ideas.

# 🧠 Proyectos de Máquinas Electrónicas

---

## 1. Secuenciador de acciones cotidianas

### Descripción especulativa
Una máquina que divide una rutina en **pasos secuenciales** con indicadores visuales o sonoros. Ideal para rutinas de estudio, cocina, ejercicio, autocuidado. Cada fase tiene duración fija y está representada con un LED o señal sonora.

Funciona como una **guía temporal no verbal**, sin distracción ni interrupción fuerte como una alarma.

###  Encendidos y apagados
- **Encendido manual** al iniciar.
- Cada fase se **activa y apaga automáticamente**.
- **Apagado total** tras completar el ciclo.

###  Tiempo de uso
- **20–40 minutos por sesión.**
- Uso **ocasional o diario**, según necesidad.

###  Interacción
- El usuario solo **presiona un botón para iniciar**.
- La máquina **guía el proceso** con luces o sonidos.

###  Diagrama de comportamiento

[Inicio manual] ──> [Fase 1] ──> [Fase 2] ──> [Fase 3] ──> [Fin y apagado]
       ▲                   ▲           ▲           ▲
       │                   │           │           │
  [Usuario inicia]   [Tiempo asignado por fase: 5–10 min]

---

##  2. Lámpara de luz ambiental reactiva al cuerpo

### Descripción especulativa
Una lámpara que reacciona a la **cercanía o permanencia del cuerpo**. Si alguien se aproxima, se enciende suavemente con una temperatura de color cálida. Si permanece más de cierto tiempo (por ejemplo, 15 minutos), comienza a atenuarse lentamente para invitar al usuario a moverse o cambiar de actividad. La lámpara sugiere una relación viva o consciente.

###  Encendidos y apagados
- **Encendido automático** al detectar presencia.  
- **Atenuación progresiva** si el cuerpo permanece.  
- **Apagado total** tras 30 minutos de inactividad.

###  Tiempo de uso
- Uso diario en sesiones de 15–30 minutos.
- Especialmente útil en rutinas nocturnas o espacios de lectura.

###  Interacción
- **Sin botones.** Se activa por proximidad y tiempo de permanencia.
- La máquina **responde de forma sensible**, no se controla de forma directa.

###  Diagrama de comportamiento

[Sin presencia] ──> [Detección de cuerpo] ──> [Encendido suave]
                            │
                            ▼
                    [Presencia continua > 15 min]
                            │
                            ▼
                  [Atenuación progresiva de luz]
                            │
                            ▼
                    [Apagado a los 30 min]

---

##  3. Reloj atmosférico de estado emocional

### Descripción especulativa
Un reloj que no muestra la hora de forma directa, sino que representa el **paso del tiempo según el estado emocional o energético** del espacio. Detecta sonido, movimiento y luz, y los traduce en visualizaciones atmosféricas (colores, formas, movimientos).

Por ejemplo:
- En ambiente **activo** (ruido, movimiento): se acelera visualmente.  
- En ambiente **calmo**: ralentiza animaciones y emite tonos suaves.

###  Encendidos y apagados
- Siempre **encendido** (modo reposo si no hay actividad).
- **Nivel de actividad visual cambia** según el entorno.

###  Tiempo de uso
- Funcionamiento **continuo**, como instalación diaria.
- Sugiere pausas o activaciones, sin sesiones explícitas.

###  Interacción
- Interacción **pasiva y ambiental**.
- El usuario **interpreta estados** mediante colores o sonidos.

###  Diagrama de comportamiento

[Ambiente inactivo] ──> [Visualización mínima]
         ▲                         │
         │                         ▼
[Ambiente activo] <── [Animaciones + sonidos intensos]


