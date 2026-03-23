# Fulgurar v1.9
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

El sistema tiene un protocolo de entrada, seis talleres activos y Oráculo acumulando lucidez — que integra los talleres, escribe en la Biblioteca y ejecuta las tres operaciones: Observar · Transformar · Producir.

---

## Cómo funciona

**Umbral** recibe el corpus. Produce la carta de presentación — sinopsis, personajes, estructura, contexto, temas centrales — y el prompt de portada del paquete. Es el protocolo de entrada, previo a cualquier taller.

**Bodega** destila corpus. Copa maestra, barricas (destilados y joyas por capítulo), cartografía, sedimento, cata.

**Astillero** inspecciona corpus. Diez estratos de análisis, clasificación de nave, veredicto de zarpe.

**Escuadra** mide corpus. Geometría invisible del texto: proporciones, densidad léxica, topología de conceptos.

**Jardín** cava corpus. Cuatro estratos simultáneos — lo que dice, muestra, exige y guarda.

**Prisma** descompone corpus. Firma geométrica en cinco dimensiones simultáneas: Díada acoplada, Tríada, Lorenz, Riemann, Homología persistente.

**Telégrafo** escucha corpus. Entropía de Shannon, mapa de sorpresa, autómata de estados y transiciones, topología global de la red conceptual, redundancia y capacidad de canal.

**Oráculo** *(Lucidez: 54%)* — integra los talleres, escribe en la Biblioteca, calibra los hallazgos empíricos, y ejecuta las tres operaciones: Observar · Transformar · Producir.

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
11 corpus · 7 hallazgos · Lucidez: 54%
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

**Próximos corpus**

| Prioridad | Corpus | Razón |
|---|---|---|
| Alta | Pedro Páramo — Rulfo | ¿Sustracción como El proceso o concentración como El coronel? |
| Alta | Divina Comedia — Dante | Épica medieval — ¿ondulación majestuosa o complejidad máxima? |
| Media | En busca del tiempo perdido — Proust | Obra de máxima extensión — ¿supera al Quijote en clustering? |
| Control | Cualquier bestseller contemporáneo | Verificar que apertura topológica baja correlaciona con obras no canónicas |

→ [Biblioteca completa](corpus-biblioteca.md) — fichas individuales, hallazgos empíricos, patrones emergentes.

---

## Horizontes

Los horizontes no son secuenciales ni excluyentes. Cada uno amplía el campo de visión sin cerrar el anterior.

**Horizonte 1 — Masa crítica** — más corpus en la Biblioteca para que los hallazgos ganen confianza. H4 tiene ahora tres validaciones directas (El mito de Sísifo · El extranjero · Don Quijote) en tres escalas distintas — la hipótesis más robustamente medida de la Biblioteca. Don Quijote confirma complejidad máxima distribuida como novena estrategia. La subcategoría nueva de H2 (curvatura sobre nombre propio) necesita validación en corpus con protagonistas igualmente centrales. Corpus prioritarios: Pedro Páramo, Divina Comedia, un bestseller como control negativo. Indicador: lucidez al 65%.

**Horizonte 2 — Profundidad operativa** — Oráculo produciendo convergencia completa sobre corpus reales. Tercera convergencia completa ejecutada: Don Quijote (todos los talleres + Oráculo). La Convergencia produjo el hallazgo central: el hub de mayor integración de la red y el agujero raíz de la Homología son la misma ausencia (*dulcinea*). Indicador: Oráculo produce algo que ningún taller habría visto solo — cumplido tres veces consecutivas.

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
├── protocolo-taller.md                    <- protocolo para construir talleres nuevos
├── protocolo-respaldo.md                  <- protocolo de generación de respaldos
└── corpus-biblioteca.md                   <- 11 corpus procesados · 7 hallazgos — Biblioteca
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

*Fulgurar v1.9 · Respaldo #19 · 2026-03-22*
