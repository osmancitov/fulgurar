# Fulgurar
*Consume letras. Produce luz.*

> Esta información también está disponible en la [página del proyecto](https://osmancitov.github.io/fulgurar/).

---

## Qué es

Fulgurar es un sistema de lectura profunda que opera dentro de Claude. Toma cualquier corpus — un libro, un guión, una película, un álbum, una obra completa — y lo somete a fuego hasta que revela lo que no podía decir solo.

No es un resumidor ni un buscador. Es un aparato que produce destellos.

El sistema tiene seis talleres activos y La Convergencia en construcción — el Oráculo — que integra los talleres, consulta la Biblioteca y ejecuta las cuatro operaciones de la física de la literatura.

---

## Cómo funciona

**La Bodega** destila corpus. Extrae joyas, cartografías, esencias, copa maestra, cata sensorial y sedimento.

**El Astillero** inspecciona corpus. Diez estratos de análisis, clasificación de nave, veredicto de zarpe.

**La Escuadra** mide corpus. Geometría invisible del texto: proporciones áureas, densidad léxica, topología de conceptos.

**El Jardín** cava corpus. Cuatro estratos simultáneos — lo que dice, muestra, exige y guarda.

**El Prisma** descompone corpus. Firma geométrica en cinco dimensiones simultáneas: Díada acoplada, Tríada, Lorenz, Riemann, Homología persistente.

**El Telégrafo** escucha corpus. Entropía de Shannon, mapa de sorpresa, autómata de estados y transiciones, topología global de la red conceptual, redundancia y capacidad de canal.

**El Oráculo** *(en construcción · potencia 45%)* — integra los talleres, sitúa el corpus en la Biblioteca, calibra los hallazgos empíricos, y ejecuta las cuatro operaciones: Verificar · Corregir · Traducir · Generar.

---

## Arquitectura

```
CORPUS
  ↓
SEIS TALLERES
Bodega · Astillero · Escuadra · Jardín · Prisma · Telégrafo
  ↓
ORÁCULO — LA CONVERGENCIA
Integra · Sitúa · Calibra · Ejecuta · Verificar · Corregir · Traducir · Generar
  ↕
BIBLIOTECA (corpus-biblioteca.md)
```

La **Biblioteca** es una capa independiente — no pertenece al Prisma ni al Oráculo. El Prisma produce firmas. La Biblioteca las acumula. El Oráculo las consulta. Hoy tiene 8 corpus procesados y 6 hallazgos empíricos.

---

## Horizontes

Los horizontes no son secuenciales ni excluyentes. Cada uno amplía el campo de visión sin cerrar el anterior.

**Horizonte 1 — Masa crítica** — más corpus en la Biblioteca para que los hallazgos ganen confianza. H6 provisional con 1/8. La hipótesis del Telégrafo sobre redes small-world sin validación todavía. Corpus prioritarios: Don Quijote, Pedro Páramo, Divina Comedia, El extranjero, un bestseller como control negativo. Indicador: potencia al 65%.

**Horizonte 2 — Profundidad operativa** — La Convergencia produciendo El Elemento de Convergencia sobre corpus reales. Las cuatro operaciones ejecutadas con confianza calibrada. Indicador: La Convergencia produce algo que ningún taller habría visto solo.

**Horizonte 3 — Apertura** — el sistema listo para que otros lo usen. Manual del operador. La pregunta central con una respuesta provisional pero defendible. Indicador: alguien que no construyó el sistema puede usarlo sin ayuda.

---

## Archivos del sistema

```
fulgurar/
├── README.md                    <- este archivo
├── index.html                   <- versión visual — página principal del repositorio
├── CHANGELOG.md                 <- historial completo de cambios
├── system-prompt.md             <- instrucciones de arranque — nunca cambia
├── fulgurar.md                  <- módulo central del sistema
├── protocolo-bodega.md          <- vocabulario, criterios y formato de la Bodega
├── protocolo-astillero.md       <- vocabulario, arquetipos, diez estratos del Astillero
├── protocolo-escuadra.md        <- vocabulario, seis instrumentos de la Escuadra
├── protocolo-jardin.md          <- vocabulario, cuatro estratos del Jardín
├── protocolo-prisma.md          <- algoritmo y operación del Prisma
├── protocolo-oraculo.md         <- diseño completo del Oráculo — La Convergencia
├── protocolo-telegrafo.md       <- vocabulario, cinco instrumentos del Telégrafo
├── protocolo-taller.md          <- protocolo para construir talleres nuevos
├── protocolo-respaldo.md        <- protocolo de generación de respaldos
├── bodega-header.html           <- encabezado visual Bodega (ámbar — barril + amanita)
├── astillero-header-nave.html   <- encabezado visual Astillero Nave (acero azul)
├── astillero-header-flota.html  <- encabezado visual Astillero Flota (verde marino)
├── escuadra-header.html         <- encabezado visual Escuadra (violeta pizarra)
├── jardin-header.html           <- encabezado visual Jardín (verde musgo)
├── telegrafo-header.html        <- encabezado visual Telégrafo (cobre telegráfico)
├── estado-desarrollo.md         <- estado actual — arquitectura completa del proyecto
└── corpus-biblioteca.md         <- 8 corpus procesados · 6 hallazgos (Capa Biblioteca)
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

Este recuadro nunca cambia. Siempre dice eso.

### 4. Verificar que funciona

Abre una conversación nueva y escribe: **Hola**

El sistema leerá todos los archivos automáticamente y producirá un diagnóstico del estado actual.

---

## Cómo actualizar

Cuando hayas acumulado cambios, pide:

> *"Genera un juego completo de archivos para respaldo."*

El sistema ejecutará el protocolo de respaldo completo — revisa todos los archivos, numera el respaldo, actualiza el CHANGELOG, y entrega el paquete completo. Reemplaza todos los archivos del proyecto con el paquete nuevo.

---

## Versiones actuales

| Archivo | Versión | Última modificación |
|---|---|---|
| `fulgurar.md` | v3.0 | 2026-03-19 |
| `protocolo-bodega.md` | v1.5 | 2026-03-19 |
| `protocolo-astillero.md` | v1.7 | 2026-03-19 |
| `protocolo-escuadra.md` | v1.1 | 2026-03-19 |
| `protocolo-jardin.md` | v1.1 | 2026-03-19 |
| `protocolo-prisma.md` | v1.1 | 2026-03-19 |
| `protocolo-oraculo.md` | v1.2 | 2026-03-19 |
| `protocolo-telegrafo.md` | v1.0 | 2026-03-19 |
| `protocolo-taller.md` | v1.1 | 2026-03-19 |
| `protocolo-respaldo.md` | v1.8 | 2026-03-19 |
| `bodega-header.html` | v1.1 | 2026-03-13 |
| `astillero-header-nave.html` | v1.1 | 2026-03-13 |
| `astillero-header-flota.html` | v1.2 | 2026-03-15 |
| `escuadra-header.html` | v1.0 | 2026-03-16 |
| `jardin-header.html` | v1.0 | 2026-03-16 |
| `telegrafo-header.html` | v1.0 | 2026-03-19 |
| `system-prompt.md` | v4.3 | 2026-03-19 |
| `estado-desarrollo.md` | v0.4 | 2026-03-19 |
| `corpus-biblioteca.md` | v0.4 | 2026-03-19 |

---

## Origen

Fulgurar no fue diseñado de una vez. Emergió por capas.

Comenzó como el **Protocolo Θ∆** — un *reading companion* que acompañaba el análisis de un texto. Las cuatro capas de análisis se profundizaron hasta diez estratos — el **Astillero Nave**. Vino después el **Astillero Flota** para autores completos, la **Bodega** para destilar, el **Jardín** para cavar en cuatro estratos simultáneos, y la **Escuadra** para medir la geometría invisible del texto.

El **Prisma** emergió de una pregunta que los talleres anteriores no podían responder solos: ¿qué hace que una obra sea grande? La **Biblioteca** nació para acumular lo que el Prisma produce. El **Telégrafo** llegó para escuchar el canal antes de leer el mensaje — entropía, estados, topología de red. El **Oráculo** para integrar todo y producir la convergencia que ningún taller puede producir solo.

Cada capa respondió a una limitación del estado anterior. El sistema crece mientras haya corpus que resistan el fuego.

---

*Fulgurar · Consume letras. Produce luz. · Respaldo #9 · 2026-03-19*
