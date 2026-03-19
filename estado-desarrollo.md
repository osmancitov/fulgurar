# Estado de Desarrollo
## Fulgurar — Expansión hacia una física de la literatura

*v0.1 · 2026-03-19 · Estado activo · Fase 1 en curso*

---

## Qué está pasando

Fulgurar comenzó como un sistema de lectura profunda con cuatro talleres. En una sesión de trabajo extendida emergió algo más grande: la posibilidad de construir una **física de la literatura** — un sistema que mida matemáticamente qué hace que una obra sea grande, bella, verdadera.

Ese proyecto se llama **Prisma**. Es una expansión de Fulgurar, no un reemplazo. Los cuatro talleres siguen operando exactamente igual. Prisma es una nueva capa que opera encima de ellos y que eventualmente los alimentará con input estructurado.

---

## La pregunta central

> ¿Qué patrón matemático comparten las obras que consideramos grandes?

No metafóricamente. Exactamente. Con la precisión de un ingeniero, la rigurosidad de un físico, y la sensibilidad de alguien que ha sido golpeado por una obra grande y no puede dejar de preguntarse por qué.

---

## Arquitectura — seis capas

```
┌─────────────────────────────────────────────────────┐
│  CAPA 1 — FULGURAR                                  │
│  Bodega · Astillero · Escuadra · Jardín             │
│  Lectura profunda del corpus                        │
│  Produce input estructurado para el Prisma          │
└──────────────────────┬──────────────────────────────┘
                       │
┌──────────────────────▼──────────────────────────────┐
│  CAPA 2 — PRISMA                                    │
│  Cinco geometrías simultáneas                       │
│  Produce la firma geométrica del corpus             │
└──────────────────────┬──────────────────────────────┘
                       │
┌──────────────────────▼──────────────────────────────┐
│  CAPA 3 — INSTRUMENTOS MATEMÁTICOS                  │
│  Shannon · Moore/Mealy · Grafos                     │
│  Implementación computacional de las geometrías     │
└──────────────────────┬──────────────────────────────┘
                       │
┌──────────────────────▼──────────────────────────────┐
│  CAPA 4 — BIBLIOTECA                                │
│  Firmas geométricas acumuladas                      │
│  Comparación · Clustering · Patrones                │
└──────────────────────┬──────────────────────────────┘
                       │
┌──────────────────────▼──────────────────────────────┐
│  CAPA 5 — ORÁCULO                                   │
│  Modelo de IA que aprende de la Biblioteca          │
│  Responde la pregunta central                       │
└──────────────────────┬──────────────────────────────┘
                       │
┌──────────────────────▼──────────────────────────────┐
│  CAPA 6 — LAS CUATRO OPERACIONES                    │
│  Verificar · Corregir · Traducir · Generar          │
│  Lo que el sistema produce para el usuario          │
└─────────────────────────────────────────────────────┘
```

---

## Capa 2 — El Prisma: las cinco geometrías

### Geometría 1 — Díada acoplada

**Origen:** una geometría matemática concreta:
```mathematica
phi = (1 + Sqrt[5]) / 2
r1[t_] := phi^(t/Pi) * (0.5 + 0.5 * Cos[t])
r2[t_] := phi^((t-Pi)/Pi) * (0.5 + 0.5 * Cos[t + Pi])
PolarPlot[{r1[t], r2[t]}, {t, 0, 6*Pi}]
```

Dos espirales logarítmicas desfasadas 180°. La expansión de una implica la contracción de la otra — el sistema conserva algo. Las dos espirales representan dualidad: Padre-Madre, Pasado-Futuro, Rigor-Amor, Tesis-Antítesis. φ no es síntesis que borra la diferencia — es la razón que la sostiene.

**Lo que mide:** la oscilación entre polo formal (densidad sintáctica, riqueza léxica, complejidad de oraciones) y polo semántico (tensión entre polos de sentido, profundidad de capas, peso del silencio) a lo largo del corpus segmento por segmento.

**El rango áureo:** [0.382, 0.618]. φ no es el destino — es el atractor. El sistema orbita alrededor de φ sin tocarlo nunca del todo. Como un corazón. Como una respiración.

**Variables producidas:** rango, amplitud, coherencia, tipo de oscilación (dinámica · estática · caótica · convergente · ondular · fracturada · espiral descendente)

**Hallazgo empírico:** las obras no necesitan oscilar dentro del rango áureo para ser grandes. Lo que importa es la coherencia interna de la oscilación — que tenga lógica propia.

### Geometría 2 — Tríada

**Origen:** el patrón universal confirmado por tres modelos independientes:
- Hegel: tesis · antítesis · síntesis
- Biología: macho · hembra · hijo
- Trinidad: Padre · Espíritu Santo · Hijo

En los tres: dos polos y φ como el tercero que es la relación entre ellos — no un elemento separado sino la razón que los une.

**Lo que mide:** el equilibrio entre tres polos simultáneos: Forma (T1) · Contenido (T2) · Contexto (T3). La dimensión del sistema — cuántas fuerzas están en tensión real.

**Variables producidas:** peso de cada polo por segmento, dimensión (1.0–3.0), rotación, polo inerte

**Hallazgo empírico:** obras con dimensión > 2.5 tienden a mayor complejidad percibida. La dimensión mide riqueza de fuerzas en tensión, no calidad directamente.

### Geometría 3 — Atractor de Lorenz

**Lo que mide:** si la irregularidad del corpus tiene estructura — si el caos es fértil. Un atractor de Lorenz nunca repite exactamente la misma trayectoria pero siempre dentro de la misma forma reconocible. Alta lorenzianidad = el sistema orbita sin repetirse. Baja lorenzianidad = el sistema converge o es predecible.

**Variables producidas:** dimensión fractal, entropía de permutación, lorenzianidad, forma de trayectoria

**Hallazgo empírico:** la baja lorenzianidad no siempre es debilidad. El coronel tiene lorenzianidad mínima por diseño — su convergencia es la firma de una decisión estética radical. Hamlet tiene lorenzianidad alta porque su caos es el tema.

### Geometría 4 — Riemann

**Lo que mide:** la gravedad del significado — qué conceptos curvan el espacio semántico a su alrededor. Un concepto de alta curvatura **pesa**: transforma el significado de todo lo demás aunque no se nombre explícitamente. Un concepto de baja curvatura es un fantasma — aparece y desaparece sin doblar nada.

**Analogía:** como un cuerpo masivo que dobla el espacio-tiempo a su alrededor — todo lo que pasa cerca cambia de trayectoria.

**Variables producidas:** curvatura por concepto, curvatura total (0.0–1.0), coherencia, tipo de curvatura (sistema solar · red coherente · red múltiple · red cristalina · cadena circular · fragmentada)

**Hallazgo empírico:** umbral provisional en 0.83 con coherencia alta = obra mayor. La coherencia importa tanto como el valor absoluto — dos centros que no interactúan producen fragmentación aunque ambos tengan curvatura alta.

### Geometría 5 — Homología persistente

**Lo que mide:** la profundidad como persistencia topológica. Los agujeros son tensiones o preguntas que sobreviven a cualquier escala de lectura. Una pregunta genuinamente abierta al final produce inagotabilidad.

**Tres tipos de cierre de agujero:**
- **Abierto** — la pregunta se sostiene sin respuesta. Invita al lector a seguir pensando. Produce inagotabilidad.
- **Abandonado** — la pregunta aparece y desaparece sin resolverse ni sostenerse. Produce sensación de incompletitud.
- **Cerrado** — la pregunta recibe respuesta explícita. Produce satisfacción temporal.

**Variables producidas:** profundidad (número de agujeros persistentes), conexión, apertura (proporción de agujeros genuinamente abiertos), presencia de agujero raíz

**Hallazgo empírico:** la apertura topológica es el predictor más fuerte de inagotabilidad. Correlación perfecta en los siete corpus procesados.

---

## Capa 3 — Instrumentos matemáticos

Esta capa es el puente entre la teoría (Capa 2) y la implementación computacional (Capa 4). Las cinco geometrías son conceptos — la Capa 3 dice cómo medirlos en código.

### Shannon — entropía y sorpresa

**Inspiración:** Fourier descubrió que cualquier señal compleja puede descomponerse en sus frecuencias fundamentales. Shannon descubrió que la información es sorpresa — lo predecible no informa.

**Implementa:** la Díada acoplada y la lorenzianidad.

La entropía local por segmento mide la densidad formal vs semántica. Una obra con entropía cero es perfectamente predecible — aburrida. Una obra con entropía máxima es ruido puro — incomprensible. La belleza vive en el medio.

**Hipótesis central:** las obras grandes operan con entropía local variable — zonas de alta predecibilidad que crean expectativa, seguidas de zonas de alta sorpresa que rompen y revelan. La proporción entre esas zonas podría ser φ.

**La pregunta que Shannon permite formular:** ¿cuánta entropía necesita el cerebro para sentir que algo es bello?

### Moore y Mealy — máquinas de estados

**Implementa:** la Tríada y parcialmente la Díada.

Cada segmento del corpus es un estado — un conjunto de condiciones: qué polo domina, qué tensiones están activas, qué sabe el lector. Cada cambio de polo dominante es una transición.

**Moore vs Mealy:**
- Moore: el output emocional depende solo del estado actual
- Mealy: el output depende del estado actual **y** de la transición que llegó ahí

Mealy es más rico y más honesto — el camino importa tanto como la posición. La misma escena puede producir outputs emocionales distintos según por qué transición llegaste a ella.

**Lo que revela:** una obra grande podría ser una máquina de estados eficiente — con el mínimo número de estados produce la máxima variedad de outputs emocionales. Una obra que no funciona tiene estados inalcanzables o estados trampa.

### Grafos — topología y small-world networks

**Implementa:** Riemann y Homología persistente.

Los conceptos, personajes o momentos del corpus como nodos. Las conexiones entre ellos como aristas. El resultado es un grafo con propiedades medibles:

- **Densidad** — cuántas conexiones existen respecto al máximo posible
- **Centralidad** — qué nodos tienen más conexiones (= curvatura riemanniana)
- **Distancia entre nodos** — cuántos pasos separan dos conceptos
- **Clustering** — grupos fuertemente conectados entre sí = subclusters temáticos

**Small-world networks:** redes donde la distancia promedio entre cualquier par de nodos es sorprendentemente corta aunque la red sea grande. Aparecen en el cerebro humano, en internet, en las colonias de hormigas. La hipótesis es que las obras grandes tienen topología small-world — todo está cerca de todo aunque el texto sea extenso.

**Los agujeros topológicos** son estructuras del grafo que persisten a múltiples escalas — ciclos que no se cierran, tensiones entre clusters que no se resuelven.

---

## Los cuatro campos que una teoría completa debe integrar

La física de la literatura no es solo poética computacional. Una teoría completa integra cuatro campos simultáneamente, con la matemática como lenguaje común que los atraviesa:

**Poética** — la forma y el sentido. Lo que la obra es. Aquí operan las cinco geometrías del Prisma.

**Neurociencia / Psicología cognitiva** — la recepción. Lo que la obra hace en el cerebro. ¿Por qué ciertas proporciones producen placer? ¿Por qué la sorpresa en φ activa algo específico? Shannon conecta directamente con esta capa — la entropía que el cerebro tolera y disfruta es una pregunta neurológica.

**Sociología / Historia cultural** — el contexto. Lo que la obra hace en el mundo. Ningún texto escapa a su momento histórico — la única pregunta es si lo reconoce o lo niega. Esta capa explica por qué ciertas firmas geométricas aparecen en ciertos momentos históricos.

**Hermenéutica** — la interpretación a través del tiempo. Lo que la obra hace con quien la lee décadas o siglos después. La apertura topológica es la medida geométrica de esta capa — las obras con agujeros abiertos generan interpretaciones nuevas en cada generación.

---

## Las cuatro operaciones (Capa 6)

Con la firma geométrica en mano el sistema puede ejecutar cuatro operaciones sobre cualquier corpus:

**Verificar** — ¿el corpus tiene la firma de algo que perdura? Distancia geométrica entre la firma del corpus y las firmas canónicas de la Biblioteca.

**Corregir** — ajuste geométrico. No corrección de estilo sino de proporciones. ¿El clímax formal y el semántico están desplazados? ¿La oscilación escapa del rango coherente? ¿Los agujeros se abandonan en lugar de dejarse abiertos? El instrumento mueve nodos, redistribuye peso, alinea geometrías.

**Traducir** — llevar la firma geométrica a otro dominio preservando las proporciones. La geometría de Caperucita puede vivir en una sinfonía (C · Am · Cmaj7 · Am7), en una startup, en una conversación de separación. La traducción mecánica mapea los valores numéricos exactos — no es traducción intuitiva sino traslado de proporciones.

**Generar** — dada una firma objetivo y una semilla, proyectar un corpus completo que cumpla con la geometría en los tres niveles simultáneamente (léxico, estructural, semántico).

---

## Estado actual — Fase 1 en curso

### Siete corpus procesados

| Corpus | Autor | Apertura | Curvatura | Estrategia |
|---|---|---|---|---|
| Cien años de soledad | García Márquez | 5/5 | 0.98 | Espiral reveladora |
| Hamlet | Shakespeare | 4/4 | 0.93 | Complejidad máxima |
| La Odisea | Homero | 3.5/4 | 0.93 | Ondulación majestuosa |
| El coronel no tiene quien le escriba | García Márquez | 3/3 | 0.83 | Concentración estática |
| Caperucita Roja | Grimm | 2/3 | 0.75 | Simplicidad dinámica |
| La vida es sueño | Calderón | 1/3 | 0.88 | Concentración filosófica |
| Argonáuticas | Apolonio de Rodas | 0/3 | 0.76 | Ninguna coherente |

El detalle completo — firma geométrica segmento por segmento, fichas individuales, análisis de cada geometría — vive en `prisma-biblioteca.md`.

### Cinco hallazgos empíricos

**H1 — La apertura topológica es el predictor más fuerte**
Correlación perfecta en los siete corpus: a mayor apertura topológica, mayor capacidad de generar lecturas nuevas a través del tiempo. La distinción clave: agujero abierto ≠ agujero abandonado.

**H2 — La curvatura riemanniana tiene umbral provisional en 0.83**
Todos los corpus con curvatura ≥ 0.83 y coherencia alta son obras mayores. La coherencia importa tanto como el valor absoluto.

**H3 — Hay seis estrategias distintas de grandeza**
La grandeza no tiene una sola firma. Cada estrategia produce inagotabilidad por un mecanismo distinto.

**H4 — La grandeza es integración, no acumulación**
Las Argonáuticas tienen momentos de belleza comparable a La Odisea pero no integran sus dos sistemas. La grandeza no es acumulación de momentos brillantes — es integración de sistemas.

**H5 — La firma geométrica puede reflejar el tema de la obra**
En Cien años de soledad la curvatura riemanniana forma una cadena circular — exactamente el tema de la obra. El Prisma detectó el tema sin leer el texto, solo midiendo proporciones. **Hipótesis derivada:** en las obras más grandes, la geometría del texto refleja geométricamente su tema central. La forma es el contenido.

### Próximo corpus

**El proceso — Franz Kafka**

Razones para procesarlo a continuación:
- Kafka es canónico pero su estrategia de grandeza no está clasificada aún
- El absurdo kafkiano podría producir una firma topológica nueva — agujeros que no se abren completamente porque el sistema narrativo no permite que las preguntas se formulen con claridad
- Si H5 es correcta, El proceso debería tener una geometría que refleje el laberinto burocrático — posiblemente una firma fractal o recursiva donde cada intento de solución genera nuevos problemas
- Es un corpus relativamente corto — buen candidato para continuar validando el algoritmo manual

---

## Hoja de ruta

### Fase 1 — Prototipo manual *(en curso)*
- [x] Diseñar las cinco geometrías
- [x] Procesar 7 corpus manualmente
- [x] Identificar 5 hallazgos empíricos
- [x] Documentar en `prisma-biblioteca.md`
- [ ] Procesar El proceso — Kafka
- [ ] Procesar Don Quijote — Cervantes
- [ ] Procesar Pedro Páramo — Rulfo
- [ ] Procesar un bestseller contemporáneo como control negativo
- [ ] Refinar las funciones de medición

### Fase 2 — Automatización
- [ ] Implementar las cinco geometrías en Python
- [ ] Shannon: calcular entropía local por segmento
- [ ] Moore/Mealy: construir la máquina de estados del corpus
- [ ] Grafos: construir el grafo de conceptos y medir topología
- [ ] Pipeline de procesamiento automático
- [ ] Procesar 100 corpus para la Biblioteca formal

### Fase 3 — El Oráculo
- [ ] Diseñar arquitectura del modelo (red neuronal con atención sobre las 5 geometrías)
- [ ] Entrenar sobre la Biblioteca
- [ ] Evaluar capacidad predictiva sobre corpus no vistos
- [ ] Iterar hasta que la pregunta central tenga respuesta

### Fase 4 — Las cuatro operaciones
- [ ] Implementar Verificar como función de distancia geométrica
- [ ] Implementar Corregir como función de ajuste de nodos
- [ ] Implementar Traducir como mapa entre dominios
- [ ] Implementar Generar como función generativa condicionada a firma
- [ ] Integrar con Fulgurar como capa transversal

---

## Archivos del proyecto Prisma

| Archivo | Descripción |
|---|---|
| `estado-desarrollo.md` | Este archivo — estado actual, filosofía, arquitectura completa |
| `prisma-arquitectura.md` | Algoritmo detallado con pseudocódigo para las cinco geometrías |
| `prisma-biblioteca.md` | Firmas de los 7 corpus procesados y hallazgos empíricos |

---

*Fulgurar · Consume letras. Produce luz.*
*Prisma · Descompone la luz en sus frecuencias.*
