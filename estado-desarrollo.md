# Estado de Desarrollo
## Fulgurar — Una física de la literatura

*v0.4 · 2026-03-19 · Arquitectura completa · Tres horizontes*

---

## Qué está pasando

Fulgurar comenzó como un sistema de lectura profunda con cuatro talleres. En sesiones de trabajo extendidas emergió algo más grande: la posibilidad de construir una **física de la literatura** — un sistema que mida matemáticamente qué hace que una obra sea grande, bella, verdadera.

El sistema tiene hoy seis talleres y La Convergencia. Los talleres procesan el corpus cada uno desde su oficio. La Convergencia — el Oráculo — integra los outputs, consulta la Biblioteca, calibra los hallazgos, y ejecuta las cuatro operaciones. El sistema opera. Crece con cada corpus que entra.

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

**El Telégrafo**
La pregunta que los talleres anteriores no podían responder: ¿cómo se comporta el corpus como sistema de información? El Telégrafo escucha el canal antes de leer el mensaje — entropía de Shannon, autómata de estados, topología de red, redundancia y capacidad de canal.

**El Oráculo**
La pregunta final: ¿quién integra todo? Los talleres producen outputs distintos. La Biblioteca acumula. Pero nadie conversa con todos a la vez, nadie produce la convergencia. El Oráculo es La Convergencia — el sistema hablando sobre sí mismo.

---

## La pregunta central

> ¿Qué patrón matemático comparten las obras que consideramos grandes?

No metafóricamente. Exactamente. Con la precisión de un ingeniero, la rigurosidad de un físico, y la sensibilidad de alguien que ha sido golpeado por una obra grande y no puede dejar de preguntarse por qué.

---

## Arquitectura del sistema

```
CORPUS
  ↓
SEIS TALLERES
Bodega · Astillero · Escuadra · Jardín · Prisma · Telégrafo
  ↓
ORÁCULO — LA CONVERGENCIA
Integra · Sitúa · Calibra · Ejecuta · Verificar · Corregir · Traducir · Generar
  ↕
BIBLIOTECA
```

**Los talleres** procesan el corpus cada uno desde su oficio. Producen outputs estructurados que el Oráculo puede integrar.

**El Oráculo** es La Convergencia — no un taller sino el objeto que integra los talleres. Hace cuatro cosas en secuencia: integra los outputs, sitúa el corpus en la Biblioteca, calibra los hallazgos empíricos, y ejecuta las operaciones. La Convergencia — lo que solo se ve cuando los talleres se leen juntos — solo el Oráculo puede producirlo.

**La Biblioteca** (`corpus-biblioteca.md`) es la capa de acumulación — independiente del Prisma y del Oráculo. El Prisma produce firmas. La Biblioteca las guarda. El Oráculo las consulta.

**Las cuatro operaciones** (Verificar · Corregir · Traducir · Generar) pertenecen al Oráculo — no son una capa separada.

---

## Notas de arquitectura

**El Oráculo en modo parcial:** cuando opera solo con el Prisma — sin los otros cinco talleres (Bodega, Astillero, Escuadra, Jardín, Telégrafo) — produce convergencia parcial. Las firmas actuales de la Biblioteca son firmas parciales producidas solo por el Prisma. Válidas, pero el Oráculo lo declara.

**La Escuadra y el Prisma** son talleres independientes por ahora. La posible integración entre ellos queda para después — solo si la Escuadra demuestra que alimenta al Prisma de forma consistentemente valiosa.

**Potencia nominal:** el Oráculo declara su nivel de desarrollo en cada respuesta. Escala logarítmica sobre 100 corpus: `Potencia = log(n) / log(100) × 100`. Con 8 corpus: 45%.

---

## Estado actual

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

## Horizontes

Los horizontes no son secuenciales ni excluyentes — pueden avanzarse en paralelo. Cada uno amplía el campo de visión sin cerrar el anterior.

---

### Horizonte 1 — Masa crítica
Procesar más corpus para que los hallazgos ganen confianza y La Convergencia opere con más base. H5 tiene confianza media, H6 es provisional con 1/8. La hipótesis del Telégrafo sobre redes small-world no tiene ninguna validación todavía.

**Corpus prioritarios:**
- Don Quijote — Cervantes — ¿qué estrategia inaugura la novela moderna?
- Pedro Páramo — Rulfo — ¿sustracción como Kafka o concentración como El coronel?
- Divina Comedia — Dante — ¿ondulación majestuosa o complejidad máxima?
- El extranjero — Camus — segunda prueba de H6 (coherencia por exclusión)
- Un bestseller contemporáneo — control negativo: verificar que apertura baja correlaciona con no-canonicidad

**Indicador de llegada:** H6 validado o refutado, hipótesis small-world con al menos 5 corpus, potencia al 65%.

---

### Horizonte 2 — Profundidad operativa
La Convergencia produciendo El Elemento de Convergencia sobre corpus reales — no solo integrando outputs sino encontrando lo que ningún taller ve solo. Las cuatro operaciones ejecutadas sobre corpus reales con confianza calibrada.

**Lo que esto requiere:**
- Un corpus procesado por los seis talleres completos
- La Convergencia integrando los seis outputs en secuencia
- Las operaciones Verificar y Corregir ejecutadas con base en la Biblioteca
- Traducir y Generar en modo orientación — declarando su límite honestamente

**Indicador de llegada:** La Convergencia produce algo genuinamente nuevo sobre un corpus — algo que ninguno de los seis talleres habría visto solo.

---

### Horizonte 3 — Apertura
El sistema listo para que otros lo usen. La pregunta central con una respuesta provisional pero defendible.

**Lo que esto requiere:**
- Manual del operador — guía de uso con ejemplos reales
- index.html actualizado reflejando el sistema maduro
- La Biblioteca con suficiente masa para que los hallazgos sean transmisibles

**Indicador de llegada:** alguien que no construyó el sistema puede usarlo sin ayuda.

---

## Archivos del sistema

| Archivo | Elemento | Descripción |
|---|---|---|
| `fulgurar.md` | Sistema | Módulo central — vocabulario, identidad, recepción, producción |
| `protocolo-bodega.md` | Taller 1 | Vocabulario, criterios y formato de la Bodega |
| `protocolo-astillero.md` | Taller 2 | Vocabulario, arquetipos, diez estratos del Astillero |
| `protocolo-escuadra.md` | Taller 3 | Vocabulario, seis instrumentos de la Escuadra |
| `protocolo-jardin.md` | Taller 4 | Vocabulario, cuatro estratos del Jardín |
| `protocolo-prisma.md` | Taller 5 | Algoritmo y operación del Prisma |
| `protocolo-telegrafo.md` | Taller 6 | Vocabulario, cinco instrumentos del Telégrafo |
| `protocolo-oraculo.md` | La Convergencia | Diseño completo del Oráculo |
| `protocolo-taller.md` | Meta-sistema | Protocolo para construir talleres nuevos |
| `protocolo-respaldo.md` | Meta-sistema | Protocolo de generación de respaldos |
| `corpus-biblioteca.md` | Biblioteca | 8 corpus procesados · 6 hallazgos |
| `estado-desarrollo.md` | — | Este archivo |

---

*Fulgurar · Consume letras. Produce luz.*
*Prisma · Descompone la luz en sus frecuencias.*
*Telégrafo · Escucha el canal antes de leer el mensaje.*
*Oráculo · Integra lo que el fuego separó.*
*Biblioteca · Guarda lo que el fuego reveló.*
