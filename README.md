# Fulgurar v2.3
*Consume letras. Produce luz.*

- [osmancitov.github.io/fulgurar](https://osmancitov.github.io/fulgurar/) — Página del proyecto
- [github.com/osmancitov/fulgurar](https://github.com/osmancitov/fulgurar) — Repositorio

---

## Índice

- [Qué es](#qué-es)
- [Cómo funciona](#cómo-funciona)
- [Arquitectura](#arquitectura)
- [Biblioteca](#biblioteca)
- [Horizontes](#horizontes)
- [Archivos del sistema](#archivos-del-sistema)
- [Cómo instalar](#cómo-instalar)

---

## Qué es

Fulgurar es un sistema de lectura profunda que opera dentro de Claude. Toma cualquier corpus — un libro, un guión, una película, un álbum, una obra completa — y lo somete a fuego hasta que revela lo que no podía decir solo.

No es un resumidor ni un buscador. Es un aparato que produce destellos.

El sistema tiene un protocolo de entrada, seis talleres activos y Oráculo acumulando lucidez — que integra los talleres, escribe en la Biblioteca y ejecuta las tres operaciones: Observar · Transformar · Producir. La Cascada encadena todos los talleres en secuencia completa sin intervención del usuario.

---

## Cómo funciona

**Umbral** recibe el corpus. Produce la carta de presentación — sinopsis, personajes, estructura, contexto, temas centrales — y el prompt de portada del paquete. Es el protocolo de entrada, previo a cualquier taller.

**Bodega** destila corpus. Copa maestra, barricas (destilados y joyas por capítulo), cartografía, sedimento, cata.

**Astillero** inspecciona corpus. Diez estratos de análisis, clasificación de nave, veredicto de zarpe.

**Escuadra** mide corpus. Geometría invisible del texto: proporciones, densidad léxica, topología de conceptos.

**Jardín** cava corpus. Cuatro estratos simultáneos — lo que dice, muestra, exige y guarda.

**Prisma** descompone corpus. Firma geométrica en cinco dimensiones simultáneas: Díada acoplada, Tríada, Lorenz, Riemann, Homología persistente.

**Telégrafo** escucha corpus. Entropía de Shannon, mapa de sorpresa, autómata de estados y transiciones, topología global de la red conceptual, redundancia y capacidad de canal.

**Oráculo** *(Lucidez: 92.9%)* — integra los talleres, escribe en la Biblioteca, calibra los hallazgos empíricos, y ejecuta las tres operaciones: Observar · Transformar · Producir.

**Cascada** — encadena todos los talleres en secuencia fija sin intervención del usuario, y al completarse ejecuta automáticamente un respaldo del sistema. El corpus entra. Ocho productos y un respaldo salen. Actívala con: *Cascada*, *procesamiento completo*, *todos los talleres* o equivalente.

---

## Arquitectura

```
CORPUS
  ↓
UMBRAL — Carta de presentación + Prompt de portada
  ↓
SEIS TALLERES
Bodega · Astillero · Escuadra · Jardín · Prisma · Telégrafo
  ↓
ORÁCULO
Integrar · Observar · Transformar · Producir
  ↕
BIBLIOTECA — corpus-biblioteca.md
14 corpus · 7 hallazgos · Lucidez: 92.9%

── MODO CASCADA ──────────────────────────────────
Umbral → Bodega → Astillero → Escuadra → Jardín
→ Prisma → Telégrafo → Oráculo → Respaldo
Sin intervención · 8 archivos · Respaldo automático
```

La **Biblioteca** es una capa independiente. Todos los talleres producen outputs. Oráculo los integra y escribe en la Biblioteca. La Biblioteca crece con cada corpus procesado.

---

## Biblioteca

| # | Corpus | Género | Época | Palabras | Rol |
|---|---|---|---|---|---|
| 1 | Caperucita Roja — Grimm | Cuento oral | s. XIX (recopilación) | ~1.500 | Canónico |
| 2 | El coronel no tiene quien le escriba — García Márquez | Novela corta | 1961 | ~28.000 | Canónico |
| 3 | Hamlet — Shakespeare | Drama en verso | c. 1600 | ~30.000 | Canónico |
| 4 | La vida es sueño — Calderón | Drama en verso | 1635 | ~22.000 | Control de Hamlet |
| 5 | La Odisea — Homero | Épica | c. s. VIII a.C. | ~120.000 | Canónico |
| 6 | Argonáuticas — Apolonio de Rodas | Épica | c. s. III a.C. | ~70.000 | Control de La Odisea |
| 7 | Cien años de soledad — García Márquez | Novela | 1967 | ~140.000 | Canónico |
| 8 | El proceso — Franz Kafka | Novela | 1925 (póstuma) | ~60.000 | Caso especial |
| 9 | El mito de Sísifo — Albert Camus | Ensayo filosófico | 1942 | ~34.000 | Convergencia completa |
| 10 | El extranjero — Albert Camus | Novela breve | 1942 | ~29.000 | Par de El mito de Sísifo |
| 11 | Don Quijote de la Mancha — Cervantes | Novela (dos partes) | 1605 / 1615 | 384.656 | Convergencia completa · Corpus fundacional |
| 12 | La Divina Commedia — Dante Alighieri | Poema visionario | c. 1306–1321 | 101.601 | Convergencia completa · Corpus fundacional |
| 13 | Du côté de chez Swann — Marcel Proust | Novela autobiográfica | 1913 | 166.247 | Convergencia completa · Corpus fundacional |
| 14 | Pedro Páramo — Juan Rulfo | Novela breve fragmentada | 1955 | 33.374 | Convergencia completa · Canónico mayor |

**Próximos corpus**

| Prioridad | Corpus | Razón |
|---|---|---|
| Alta | Le Temps retrouvé — Proust | Cierre del ciclo — ¿resuelve o declara irresoluble el agujero raíz del Swann? |
| Alta | Ilíada — Homero | Control de La Odisea — ¿misma firma o distinta? |
| Media | El llano en llamas — Rulfo | Par de Pedro Páramo — ¿misma estrategia de compresión en cuentos? |
| Control | Cualquier bestseller contemporáneo | Verificar que apertura topológica baja correlaciona con obras no canónicas |

→ [Biblioteca completa](corpus-biblioteca.md) — fichas individuales, hallazgos empíricos, patrones emergentes.

---

## Horizontes

Los horizontes no son secuenciales ni excluyentes. Cada uno amplía el campo de visión sin cerrar el anterior.

**Horizonte 1 — Masa crítica** — más corpus en la Biblioteca para que los hallazgos ganen confianza. H4 tiene cuatro validaciones directas en cuatro escalas distintas y dos confirmaciones parciales — la hipótesis más robustamente medida. La Biblioteca tiene ahora cinco corpus con apertura 5/5, los cinco canónicos máximos o fundacionales. El 71.4% constante en los últimos cinco corpus canónicos confirma que H2 y H3 son catálogos estructuralmente expansivos. Corpus prioritarios: Le Temps retrouvé, Ilíada, El llano en llamas, un bestseller como control negativo. Indicador: lucidez acumulada sostenida por encima de 90%.

**Horizonte 2 — Profundidad operativa** — Oráculo produciendo convergencia completa sobre corpus reales. Sexta convergencia completa ejecutada: Pedro Páramo. La Convergencia produjo el hallazgo central: la geometría del texto es la geometría del mundo narrado — los meridianos señalan las tres capas de Comala, la red bifurcada replica la estructura del pueblo, el autómata excluye lo que los muertos no pueden alcanzar. Indicador: Oráculo produce algo que ningún taller habría visto solo — cumplido seis veces consecutivas.

**Horizonte 3 — Apertura** — el sistema listo para que otros lo usen. Manual del operador. La pregunta central con una respuesta provisional pero defendible. Indicador: alguien que no construyó el sistema puede usarlo sin ayuda.

---

## Archivos del sistema

```
fulgurar/
├── README.md                              <- este archivo
├── CHANGELOG.md                           <- historial completo de cambios
├── system-prompt.md                       <- instrucciones de arranque del sistema
├── parametros-globales.md                 <- fuente de verdad — valores actuales del sistema
├── matriz.md                              <- módulo central del sistema
├── protocolo-umbral.md                    <- protocolo de entrada — carta de presentación y portada
├── protocolo-bodega.md                    <- vocabulario, criterios y formato de Bodega
├── protocolo-astillero.md                 <- vocabulario, arquetipos, diez estratos de Astillero
├── protocolo-escuadra.md                  <- vocabulario, seis instrumentos de Escuadra
├── protocolo-jardin.md                    <- vocabulario, cuatro estratos de Jardín
├── protocolo-prisma.md                    <- algoritmo y operación de Prisma
├── protocolo-oraculo.md                   <- diseño completo de Oráculo
├── protocolo-telegrafo.md                 <- vocabulario, cinco instrumentos de Telégrafo
├── protocolo-cascada.md                   <- ejecución total sin intervención — 8 talleres en secuencia
├── protocolo-taller.md                    <- protocolo para construir talleres nuevos
├── protocolo-respaldo.md                  <- protocolo de generación de respaldos
└── corpus-biblioteca.md                   <- 12 corpus procesados · 7 hallazgos · Lucidez 92.9% — Biblioteca
```

---

## Cómo instalar

### 1. Crear el proyecto en Claude

Nombre: *Fulgurar* · Descripción: *Sistema de lectura profunda*

### 2. Subir todos los archivos

Sube **todos** los archivos de esta carpeta. Sin excepción.

### 3. Configurar las instrucciones

En el recuadro de instrucciones del proyecto escribe exactamente:

*Lee el archivo system-prompt.md*

Esta instrucción en el recuadro nunca cambia — siempre dice eso. Es `system-prompt.md` el que evoluciona con el sistema.

### 4. Verificar que funciona

Abre una conversación nueva y escribe: **Hola**

---

*Fulgurar v2.3 · Respaldo #23 · 2026-03-27*
