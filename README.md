# Fulgurar
*Consume letras. Produce luz.*

> Versión en texto plano. También disponible en [formato visual](index.html) y en la [página del proyecto](https://osmancitov.github.io/fulgurar/).

---

## Qué es

Fulgurar es un sistema de lectura profunda que opera dentro de Claude. Toma cualquier corpus — un libro, un guión, una película, un álbum, una obra completa — y lo somete a fuego hasta que revela lo que no podía decir solo. Toma algo opaco y lo vuelve legible, visible, comprensible.

No es un resumidor ni un buscador. Es un aparato que produce destellos.

---

## Cómo funciona

El sistema opera a través de **talleres** — espacios de trabajo con oficio propio, vocabulario propio y registro de voz propio. Hay cuatro talleres activos:

**La Bodega** destila corpus. Extrae joyas, cartografías, esencias, copa maestra, cata sensorial y sedimento. Describe el corpus como si fuera una bebida y encuentra lo que el texto no pudo decir.

**El Astillero** inspecciona corpus. Somete cada libro a diez estratos de análisis, clasifica la nave según su arquetipo, emite un veredicto de zarpe y produce una cata lírica. También puede inspeccionar autores completos en Modo Flota.

**La Escuadra** mide corpus. Levanta la geometría invisible del texto: proporciones áureas, perfil de densidad léxica, topología de conceptos, curva de Zipf. Produce un plano — la arquitectura real del corpus expuesta.

**El Jardín** cava corpus. Lee en cuatro estratos simultáneos — lo que dice, lo que muestra, lo que exige, lo que guarda — y expone todas las lecturas posibles en cada estrato sin resolver las tensiones entre ellas.

El sistema dispone además de un protocolo para construir talleres nuevos a partir de una semilla del usuario.

Cada corpus que entra a Fulgurar produce un archivo HTML autónomo, legible en cualquier navegador, con encabezado visual animado, navegación interna y SVG embebido.

---

## Archivos del sistema

```
fulgurar/
├── README.md                   ← este archivo
├── README.html                 ← versión visual del README, regenerada
│                                  automáticamente en cada respaldo
├── CHANGELOG.md                ← historial completo de cambios —
│                                  única fuente de verdad del historial
├── system-prompt.md            ← instrucciones de arranque del proyecto
├── fulgurar.md                 ← módulo central: identidad, vocabulario,
│                                  identidad visual, ficha del corpus,
│                                  recepción, operación y producción
├── protocolo-bodega.md         ← vocabulario, criterios y formato
│                                  completo de la Bodega
├── protocolo-astillero.md      ← vocabulario, arquetipos, diez estratos,
│                                  dictamen y formato del Astillero
├── protocolo-escuadra.md       ← vocabulario, seis instrumentos,
│                                  levantamiento y formato de la Escuadra
├── protocolo-jardin.md         ← vocabulario, cuatro estratos,
│                                  perfil y formato del Jardín
├── protocolo-taller.md         ← protocolo para construir talleres nuevos
│                                  a partir de una semilla del usuario
├── protocolo-respaldo.md       ← protocolo de generación de respaldos
│                                  del sistema
├── bodega-header.html          ← encabezado visual animado de la Bodega
│                                  (paleta ámbar — barril + amanita)
├── astillero-header-nave.html  ← encabezado visual animado del Astillero
│                                  modo nave (paleta acero azul — velero + amanita)
├── astillero-header-flota.html ← encabezado visual animado del Astillero
│                                  modo flota (paleta verde marino — brújula + amanita)
├── escuadra-header.html        ← encabezado visual animado de la Escuadra
│                                  (paleta violeta pizarra — escuadra + amanita)
└── jardin-header.html          ← encabezado visual animado del Jardín
                                   (paleta verde musgo — corte de suelo + amanita)
```

---

## Cómo instalar en un proyecto nuevo

**Descargar los archivos:** [fulgurar-main.zip](https://github.com/osmancitov/fulgurar/archive/refs/heads/main.zip)

### 1. Crear el proyecto en Claude

Abre Claude y crea un nuevo proyecto. En el recuadro de **nombre** escribe *Fulgurar*. En el recuadro de **descripción** escribe *Sistema de lectura profunda.*

### 2. Agregar los archivos al proyecto

Sube **todos** los archivos de esta carpeta al contenedor de archivos del proyecto. El sistema los necesita todos — tanto los archivos operativos como los de documentación — para funcionar correctamente y para poder generar respaldos completos en el futuro.

### 3. Configurar el system prompt

En el recuadro de **instrucciones** del proyecto escribe exactamente:

*Lee el archivo system-prompt.md*

### 4. Verificar que funciona

Inicia una conversación nueva en el proyecto y envía un corpus — el título de un libro, un archivo adjunto, o el nombre de un autor. El sistema debe:

1. Acusar recibo del corpus en registro neutro
2. Generar automáticamente la Naturaleza del corpus
3. Ofrecer los cuatro talleres disponibles y esperar tu elección

Si el sistema responde con ese flujo, está correctamente instalado.

---

## Cómo actualizar

El sistema evoluciona con el uso. Cuando hayas acumulado cambios en una sesión de trabajo, pide al sistema:

> *"Genera un juego completo de archivos para respaldo."*

El sistema ejecutará el protocolo de respaldo definido en `protocolo-respaldo.md` — revisará todos los archivos, numerará el respaldo, actualizará el CHANGELOG, regenerará este README.html y entregará el paquete completo listo para reemplazar esta carpeta.

Para instalar la actualización, reemplaza los archivos del proyecto de Claude con las versiones nuevas del paquete.

---

## Versiones actuales

| Archivo | Versión |
|---|---|
| `fulgurar.md` | v2.3 |
| `protocolo-bodega.md` | v1.4 |
| `protocolo-astillero.md` | v1.6 |
| `protocolo-escuadra.md` | v1.0 |
| `protocolo-jardin.md` | v1.0 |
| `protocolo-taller.md` | v1.0 |
| `protocolo-respaldo.md` | v1.4 |
| `bodega-header.html` | v1.1 |
| `astillero-header-nave.html` | v1.1 |
| `astillero-header-flota.html` | v1.2 |
| `escuadra-header.html` | v1.0 |
| `jardin-header.html` | v1.0 |
| `system-prompt.md` | v3.0 |

---

*Fulgurar · Consume letras. Produce luz. · 2026-03-16*
