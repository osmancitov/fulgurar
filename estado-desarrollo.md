# Estado de Desarrollo
## Fulgurar — Una física de la literatura

*v0.2 · 2026-03-19 · Fase 1 completa · Fase 2 en diseño*

---

## Qué está pasando

Fulgurar comenzó como un sistema de lectura profunda con cuatro talleres. En sesiones de trabajo extendidas emergió algo más grande: la posibilidad de construir una **física de la literatura** — un sistema que mida matemáticamente qué hace que una obra sea grande, bella, verdadera.

El sistema tiene hoy seis elementos. Cinco son talleres que procesan el corpus desde oficios distintos. El sexto — el Oráculo — integra los outputs de los cinco, consulta la Biblioteca, calibra los hallazgos, y ejecuta las cuatro operaciones. La Fase 1 está completa. El Oráculo está diseñado pero no implementado.

---

## Historia del sistema

Fulgurar no fue diseñado de una vez. Emergió por capas — cada expansión respondiendo a una limitación del estado anterior.

**Protocolo Θ∆ — el origen**
El sistema comenzó como un protocolo de compañero de estudio (*reading companion*): un lector que acompaña el análisis de un texto, hace preguntas, señala conexiones. Sin vocabulario propio, sin estructura fija. La semilla.

**Cuatro capas de análisis**
El protocolo Θ∆ se expandió hacia un análisis estructurado en cuatro capas simultáneas, con analogías biológica, física, matemática y hermenéutica. El corpus empezó a ser tratado como objeto de estudio, no solo de lectura.

**Diez estratos**
Las cuatro capas se profundizaron hasta diez estratos de inspección — lo que eventualmente se convertiría en el núcleo del Astillero Nave. Cada estrato examina el corpus desde un ángulo distinto: estructura, corrientes ocultas, psicología del autor, rutas míticas, nudos de sentido.

**El Astillero Flota**
La lógica de inspección se extendió del libro individual al autor completo. Un modo distinto — no una nave sino una flota. El Astillero tomó su forma definitiva con dos modos de operación.

**La Bodega**
El sistema necesitaba un taller que destilara en lugar de inspeccionar. La Bodega emergió como espacio de extracción pura: joyas, esencias, cartografía, copa maestra, sedimento. El lenguaje de la destilación como metáfora operativa.

**El Jardín**
La lectura en capas simultáneas — no secuencial sino estratigráfica. Inspirado en PaRDeS, la palabra hebrea para jardín y acrónimo de cuatro niveles exegéticos. El Jardín cava en lugar de inspeccionar o destilar.

**La Escuadra**
La geometría invisible del texto. Un taller que mide proporciones, densidad léxica, topología de conceptos, curva de Zipf. La Escuadra levanta planos, no interpreta.

**El Prisma**
La pregunta que los cuatro talleres no podían responder solos: ¿qué hace que una obra sea grande? El Prisma descompone el corpus en cinco geometrías simultáneas y produce su firma matemática. La física de la literatura como proyecto.

**La Biblioteca**
El Prisma por sí solo produce firmas individuales. Para detectar patrones necesita acumulación y comparación. La Biblioteca nació como capa independiente — no un taller sino un archivo vivo que crece con cada corpus procesado.

**El Oráculo**
La pregunta final: ¿quién integra todo? Los cinco talleres producen outputs distintos. La Biblioteca acumula. Pero nadie conversa con los cinco a la vez, nadie produce la convergencia. El Oráculo es el sexto elemento — el sistema hablando sobre sí mismo.

---

## La pregunta central

> ¿Qué patrón matemático comparten las obras que consideramos grandes?

No metafóricamente. Exactamente. Con la precisión de un ingeniero, la rigurosidad de un físico, y la sensibilidad de alguien que ha sido golpeado por una obra grande y no puede dejar de preguntarse por qué.

---

## Arquitectura del sistema

```
CORPUS
  ↓
CINCO TALLERES
Bodega · Astillero · Escuadra · Jardín · Prisma
  ↓
ORÁCULO
Integra · Sitúa · Calibra · Ejecuta
  ↕
BIBLIOTECA

El Oráculo ejecuta:
Verificar · Corregir · Traducir · Generar
```

**Los cinco talleres** procesan el corpus cada uno desde su oficio. Producen outputs estructurados que el Oráculo puede integrar.

**El Oráculo** es el sexto elemento — no un taller sino el objeto que integra los cinco. Hace cuatro cosas en secuencia: integra los outputs, sitúa el corpus en la Biblioteca, calibra los hallazgos empíricos, y ejecuta las operaciones. El Sexto Elemento — lo que solo se ve cuando los cinco talleres se leen juntos — solo el Oráculo puede producirlo.

**La Biblioteca** (`corpus-biblioteca.md`) es la capa de acumulación — independiente del Prisma y del Oráculo. El Prisma produce firmas. La Biblioteca las guarda. El Oráculo las consulta.

**Las cuatro operaciones** (Verificar · Corregir · Traducir · Generar) pertenecen al Oráculo — no son una capa separada.

---

## Notas de arquitectura

**El Oráculo en modo parcial:** cuando opera solo con el Prisma — sin los otros cuatro talleres — produce convergencia parcial. Las firmas actuales de la Biblioteca son firmas parciales producidas solo por el Prisma. Válidas, pero el Oráculo lo declara.

**La Escuadra y el Prisma** son talleres independientes por ahora. La posible integración entre ellos queda para después — solo si la Escuadra demuestra que alimenta al Prisma de forma consistentemente valiosa.

**Potencia nominal:** el Oráculo declara su nivel de desarrollo en cada respuesta. Escala logarítmica sobre 100 corpus: `Potencia = log(n) / log(100) × 100`. Con 8 corpus: 45%.

---

## Estado actual — Fase 1 completa

### Ocho corpus procesados

| # | Corpus | Curvatura | Apertura | Estrategia |
|---|---|---|---|---|
| 1 | Cien años de soledad — García Márquez | 0.98 | 5/5 | Espiral reveladora |
| 2 | Hamlet — Shakespeare | 0.93 | 4/4 | Complejidad máxima |
| 3 | La Odisea — Homero | 0.93 | 3.5/4 | Ondulación majestuosa |
| 4 | El coronel no tiene quien le escriba — García Márquez | 0.83 | 3/3 | Concentración estática |
| 5 | La vida es sueño — Calderón | 0.88 | 1/3 | Concentración filosófica |
| 6 | Caperucita Roja — Grimm | 0.75 | 2/3 | Simplicidad dinámica |
| 7 | Argonáuticas — Apolonio de Rodas | 0.76 | 0/3 | Ninguna coherente |
| 8 | El proceso — Kafka | 0.72 | 3/4 | Sustracción sistemática |

El detalle completo vive en `corpus-biblioteca.md`.

### Seis hallazgos empíricos

**H1 — La apertura topológica es el predictor más fuerte** *(confianza alta — 8/8)*
Correlación sostenida en los ocho corpus. Distinción crítica: agujero abierto ≠ agujero abandonado.

**H2 — La curvatura riemanniana tiene umbral en 0.83** *(confianza media-alta — 7/8, 1 excepción refinada)*
Dos rutas a la grandeza: acumulación (curvatura alta) y sustracción (coherencia por exclusión). El proceso reformuló el umbral.

**H3 — Seis estrategias distintas de grandeza** *(confianza alta — 8/8)*
La grandeza no tiene una sola firma. Cada estrategia produce inagotabilidad por un mecanismo distinto.

**H4 — La grandeza es integración, no acumulación** *(confianza alta — 8/8)*
La grandeza no es acumulación de momentos brillantes — es integración de sistemas.

**H5 — La firma geométrica puede reflejar el tema de la obra** *(confianza media — 2/8 directa, 1/8 estructural)*
En las obras más grandes, la forma es el contenido. La geometría encarna el mecanismo del tema.

**H6 — Coherencia por exclusión como categoría propia** *(provisional — 1/8)*
Cuando el protagonista tiene la curvatura más baja de su propia novela, la coherencia viene de lo que el sistema excluye. Distinto de la fragmentación. Requiere más corpus.

---

## Hoja de ruta

### Fase 1 — Prototipo manual *(completa)*
- [x] Diseñar las cinco geometrías
- [x] Definir la arquitectura completa del sistema
- [x] Procesar 8 corpus manualmente
- [x] Identificar 6 hallazgos empíricos
- [x] Documentar en `corpus-biblioteca.md`
- [x] Diseñar el Oráculo — `protocolo-oraculo.md`

### Fase 2 — Construcción del Oráculo *(siguiente paso)*
- [ ] Implementar los cuatro momentos del Oráculo operativamente
- [ ] Definir cómo el Oráculo accede y consulta la Biblioteca
- [ ] Construir el mecanismo de calibración de confianza por hallazgo
- [ ] Probar las cuatro operaciones sobre los 8 corpus existentes
- [ ] Procesar 12 corpus adicionales para llevar la potencia al 65%
  - Don Quijote — Cervantes
  - Pedro Páramo — Rulfo
  - Divina Comedia — Dante
  - El extranjero — Camus (segunda prueba de H6)
  - Un bestseller contemporáneo (control negativo)

### Fase 3 — Automatización
- [ ] Implementar las cinco geometrías en Python
- [ ] Pipeline de procesamiento automático
- [ ] Procesar 100 corpus para la Biblioteca formal

### Fase 4 — Sistema completo
- [ ] Oráculo con potencia 100%
- [ ] Las cuatro operaciones completamente implementadas
- [ ] Respuesta a la pregunta central

---

## Archivos del sistema

| Archivo | Elemento | Descripción |
|---|---|---|
| `estado-desarrollo.md` | — | Este archivo |
| `protocolo-prisma.md` | Taller 5 | Algoritmo y operación del Prisma |
| `protocolo-oraculo.md` | Sexto elemento | Diseño completo del Oráculo |
| `corpus-biblioteca.md` | Biblioteca | 8 corpus procesados · 6 hallazgos |

---

*Fulgurar · Consume letras. Produce luz.*
*Prisma · Descompone la luz en sus frecuencias.*
*Oráculo · Integra lo que el fuego separó.*
*Biblioteca · Guarda lo que el fuego reveló.*
