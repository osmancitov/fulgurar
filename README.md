# Fulgurar
*Consume letras. Produce luz.*

- [osmancitov.github.io/fulgurar](https://osmancitov.github.io/fulgurar/) — Página del proyecto
- [github.com/osmancitov/fulgurar](https://github.com/osmancitov/fulgurar) — Repositorio

---

## Qué es

Fulgurar es un sistema de lectura profunda que opera dentro de Claude. Toma cualquier corpus — un libro, un guión, una película, un álbum, una obra completa — y lo somete a fuego hasta que revela lo que no podía decir solo.

No es un resumidor ni un buscador. Es un aparato que produce destellos.

El sistema tiene un protocolo de entrada, seis talleres activos y el Oráculo en construcción — que integra los talleres, escribe en la Biblioteca y ejecuta las cuatro operaciones de la física de la literatura.

---

## Cómo funciona

**El Umbral** recibe el corpus. Produce la carta de presentación — sinopsis, personajes, estructura, contexto, temas centrales — y el prompt de portada del paquete. Es el protocolo de entrada, previo a cualquier taller.

**La Bodega** destila corpus. Copa maestra, barricas (destilados y joyas por capítulo), cartografía, sedimento, cata.

**El Astillero** inspecciona corpus. Diez estratos de análisis, clasificación de nave, veredicto de zarpe.

**La Escuadra** mide corpus. Geometría invisible del texto: proporciones, densidad léxica, topología de conceptos.

**El Jardín** cava corpus. Cuatro estratos simultáneos — lo que dice, muestra, exige y guarda.

**El Prisma** descompone corpus. Firma geométrica en cinco dimensiones simultáneas: Díada acoplada, Tríada, Lorenz, Riemann, Homología persistente.

**El Telégrafo** escucha corpus. Entropía de Shannon, mapa de sorpresa, autómata de estados y transiciones, topología global de la red conceptual, redundancia y capacidad de canal.

**El Oráculo** *(en construcción · potencia 45%)* — integra los talleres, escribe en la Biblioteca, calibra los hallazgos empíricos, y ejecuta las cuatro operaciones: Verificar · Corregir · Traducir · Generar.

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
Integra · Sitúa · Calibra · Ejecuta · Verificar · Corregir · Traducir · Generar
  ↕
BIBLIOTECA — corpus-biblioteca.md
8 corpus · 6 hallazgos · Potencia 45%
```

La **Biblioteca** es una capa independiente. Todos los talleres producen outputs. El Oráculo los integra y escribe en la Biblioteca. La Biblioteca crece con cada corpus procesado.

---

## Horizontes

Los horizontes no son secuenciales ni excluyentes. Cada uno amplía el campo de visión sin cerrar el anterior.

**Horizonte 1 — Masa crítica** — más corpus en la Biblioteca para que los hallazgos ganen confianza. H6 provisional con 1/8. La hipótesis del Telégrafo sobre redes small-world sin validación todavía. Corpus prioritarios: Don Quijote, Pedro Páramo, Divina Comedia, El extranjero, un bestseller como control negativo. Indicador: potencia al 65%.

**Horizonte 2 — Profundidad operativa** — El Oráculo produciendo El Elemento de Convergencia sobre corpus reales. Las cuatro operaciones ejecutadas con confianza calibrada. Indicador: el Oráculo produce algo que ningún taller habría visto solo.

**Horizonte 3 — Apertura** — el sistema listo para que otros lo usen. Manual del operador. La pregunta central con una respuesta provisional pero defendible. Indicador: alguien que no construyó el sistema puede usarlo sin ayuda.

---

## Archivos del sistema

```
fulgurar/
├── README.md                    <- este archivo
├── CHANGELOG.md                 <- historial completo de cambios
├── system-prompt.md             <- instrucciones de arranque del sistema
├── fulgurar.md                  <- módulo central del sistema
├── protocolo-umbral.md          <- protocolo de entrada — carta de presentación y portada
├── protocolo-bodega.md          <- vocabulario, criterios y formato de la Bodega
├── protocolo-astillero.md       <- vocabulario, arquetipos, diez estratos del Astillero
├── protocolo-escuadra.md        <- vocabulario, seis instrumentos de la Escuadra
├── protocolo-jardin.md          <- vocabulario, cuatro estratos del Jardín
├── protocolo-prisma.md          <- algoritmo y operación del Prisma
├── protocolo-oraculo.md         <- diseño completo del Oráculo
├── protocolo-telegrafo.md       <- vocabulario, cinco instrumentos del Telégrafo
├── protocolo-taller.md          <- protocolo para construir talleres nuevos
├── protocolo-respaldo.md        <- protocolo de generación de respaldos
└── corpus-biblioteca.md         <- 8 corpus procesados · 6 hallazgos — Biblioteca
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

## Versiones actuales

| Archivo | Versión | Última modificación |
|---|---|---|
| `fulgurar.md` | v3.3 | 2026-03-20 |
| `protocolo-umbral.md` | v1.3 | 2026-03-20 |
| `protocolo-bodega.md` | v1.7 | 2026-03-20 |
| `protocolo-astillero.md` | v1.8 | 2026-03-20 |
| `protocolo-escuadra.md` | v1.1 | 2026-03-19 |
| `protocolo-jardin.md` | v1.1 | 2026-03-19 |
| `protocolo-prisma.md` | v1.1 | 2026-03-19 |
| `protocolo-oraculo.md` | v1.2 | 2026-03-19 |
| `protocolo-telegrafo.md` | v1.0 | 2026-03-19 |
| `protocolo-taller.md` | v1.2 | 2026-03-20 |
| `protocolo-respaldo.md` | v2.2 | 2026-03-20 |
| `system-prompt.md` | v4.6 | 2026-03-20 |
| `corpus-biblioteca.md` | v0.4 | 2026-03-19 |

---

*Fulgurar · Consume letras. Produce luz. · Respaldo #14 · 2026-03-20*
