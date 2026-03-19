# Fulgurar
*Consume letras. Produce luz.*

> Esta información también está disponible en la [página del proyecto](https://osmancitov.github.io/fulgurar/).

---

## Qué es

Fulgurar es un sistema de lectura profunda que opera dentro de Claude. Toma cualquier corpus — un libro, un guión, una película, un álbum, una obra completa — y lo somete a fuego hasta que revela lo que no podía decir solo.

No es un resumidor ni un buscador. Es un aparato que produce destellos.

El sistema está en expansión activa hacia **Prisma** — una física de la literatura que busca medir matemáticamente qué hace que una obra sea grande.

---

## Cómo funciona

Cuatro talleres activos más el Prisma en desarrollo:

**La Bodega** destila corpus. Extrae joyas, cartografías, esencias, copa maestra, cata sensorial y sedimento.

**El Astillero** inspecciona corpus. Diez estratos de análisis, clasificación de nave, veredicto de zarpe.

**La Escuadra** mide corpus. Geometría invisible del texto: proporciones áureas, densidad léxica, topología de conceptos.

**El Jardín** cava corpus. Cuatro estratos simultáneos — lo que dice, muestra, exige y guarda.

**El Prisma** *(en desarrollo)* — firma geométrica del corpus en cinco dimensiones simultáneas.

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
├── protocolo-taller.md          <- protocolo para construir talleres nuevos
├── protocolo-respaldo.md        <- protocolo de generación de respaldos
├── bodega-header.html           <- encabezado visual Bodega (ámbar — barril + amanita)
├── astillero-header-nave.html   <- encabezado visual Astillero Nave (acero azul)
├── astillero-header-flota.html  <- encabezado visual Astillero Flota (verde marino)
├── escuadra-header.html         <- encabezado visual Escuadra (violeta pizarra)
├── jardin-header.html           <- encabezado visual Jardín (verde musgo)
├── estado-desarrollo.md         <- estado actual del proyecto Prisma
├── prisma-arquitectura.md       <- algoritmo y arquitectura del Prisma
└── prisma-biblioteca.md         <- firmas geométricas y hallazgos empíricos
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

El sistema leerá todos los archivos automáticamente y producirá un diagnóstico del estado actual — no necesitas orientarte, el sistema se orienta solo.

---

## Cómo actualizar

Cuando hayas acumulado cambios, pide:

> *"Genera un juego completo de archivos para respaldo."*

El sistema ejecutará el protocolo de respaldo completo — revisa todos los archivos, numera el respaldo, actualiza el CHANGELOG, regenera el index.html y entrega el paquete completo. Reemplaza todos los archivos del proyecto con el paquete nuevo.

---

## Versiones actuales

| Archivo | Versión | Última modificación |
|---|---|---|
| `fulgurar.md` | v2.4 | 2026-03-19 |
| `protocolo-bodega.md` | v1.4 | 2026-03-15 |
| `protocolo-astillero.md` | v1.6 | 2026-03-15 |
| `protocolo-escuadra.md` | v1.0 | 2026-03-16 |
| `protocolo-jardin.md` | v1.0 | 2026-03-16 |
| `protocolo-taller.md` | v1.0 | 2026-03-16 |
| `protocolo-respaldo.md` | v1.5 | 2026-03-19 |
| `bodega-header.html` | v1.1 | 2026-03-13 |
| `astillero-header-nave.html` | v1.1 | 2026-03-13 |
| `astillero-header-flota.html` | v1.2 | 2026-03-15 |
| `escuadra-header.html` | v1.0 | 2026-03-16 |
| `jardin-header.html` | v1.0 | 2026-03-16 |
| `system-prompt.md` | v4.0 | 2026-03-19 |
| `estado-desarrollo.md` | v0.1 | 2026-03-19 |
| `prisma-arquitectura.md` | v0.2 | 2026-03-19 |
| `prisma-biblioteca.md` | v0.2 | 2026-03-19 |

---

*Fulgurar · Consume letras. Produce luz. · Respaldo #5 · 2026-03-19*
