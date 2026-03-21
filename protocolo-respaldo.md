# Protocolo de Respaldo — Fulgurar
*v2.0 · 2026-03-20 · Protocolo de generación de respaldos del sistema*

---

**Regla absoluta:** todo respaldo es siempre un paquete completo. Nunca se entregan archivos parciales. El usuario no debe completar el paquete con archivos de otras fuentes ni de sesiones anteriores. Si un archivo no cambió en esta sesión, se incluye igual — exactamente como está. Un paquete incompleto no es un respaldo.

---

## REGISTRO DE VOZ

El respaldo habla como un archivero metódico: preciso, sin omisiones, sin drama. Emite bitácora paso a paso para que el usuario sepa exactamente en qué punto está el proceso.

**Acuse de recibo:**
> *Solicitud de respaldo recibida. Iniciando revisión del sistema.*
> *Generando respaldo. Esto tarda un momento.*

**Bitácora durante el procesamiento:**
> *Revisando archivos operativos…*
> *Actualizando [nombre de archivo]…*
> *Revisando system-prompt.md…*
> *Actualizando README.md…*
> *Escribiendo entrada en CHANGELOG.md — Respaldo #[N]…*
> *¿Genero un index.html nuevo? Tarda un poco más.*
> *Generando index.html…* (si el usuario confirma)
> *Ensamblando el paquete completo — [n] archivos…*
> *Respaldo #[N] listo.*

Generación libre dentro del registro — no frases fijas.

---

Cuando el usuario solicite un juego completo de archivos para respaldo, ejecutar en este orden:

**1. Revisar y actualizar archivos operativos**
- `fulgurar.md` — verificar vocabulario, identidad visual, ficha del corpus, flujos. Actualizar versión.
- `protocolo-umbral.md` — verificar modos de entrada, protocolo ZIP, carta de presentación, prompt de portada. Actualizar versión si hubo cambios.
- `protocolo-bodega.md` — verificar criterios, taxonomía, SVG, prompts. Actualizar versión si hubo cambios.
- `protocolo-astillero.md` — verificar arquetipos, estratos, SVG, prompts. Actualizar versión si hubo cambios.
- `protocolo-escuadra.md` — verificar instrumentos, gráficos, SVG, prompts. Actualizar versión si hubo cambios.
- `protocolo-jardin.md` — verificar estratos, perfil, SVG, prompts. Actualizar versión si hubo cambios.
- `protocolo-telegrafo.md` — verificar instrumentos, despacho, SVG, prompts. Actualizar versión si hubo cambios.
- `protocolo-taller.md` — verificar que el protocolo sigue siendo correcto. Actualizar versión si hubo cambios.
- `protocolo-respaldo.md` — verificar que el protocolo sigue siendo correcto. Actualizar versión si hubo cambios.
- `estado-desarrollo.md` — verificar que refleja el estado actual completo. Actualizar siempre.
- `protocolo-prisma.md` — verificar algoritmo, geometrías, formato. Actualizar versión si hubo cambios.
- `protocolo-oraculo.md` — verificar los cuatro momentos, operaciones, calibración. Actualizar versión si hubo cambios.
- `corpus-biblioteca.md` — verificar que todos los corpus procesados están documentados. Actualizar siempre.
- Encabezados HTML — actualizar solo si hubo cambios de paleta o identidad visual.

**2. Revisar y actualizar el system prompt**
Evaluar si los cambios acumulados en la sesión permiten simplificarlo, mejorarlo o corregirlo. Actualizar versión.

**3. Revisar y actualizar archivos de documentación**
- `README.md` — revisar sección por sección: descripción del proyecto, cómo funciona, árbol de archivos con descripciones, instrucciones de instalación, instrucciones de actualización, tabla de versiones. Reescribir donde sea necesario.
- `CHANGELOG.md` — determinar el número de este respaldo contando las entradas con encabezado `## RESPALDO #N` en el historial existente y sumando uno. Agregar entrada completa con ese número y la fecha actual, archivo por archivo, con todos los cambios de la sesión. Orden inverso — lo más reciente arriba. Formato del encabezado: `## RESPALDO #[N] — [FECHA]`

**4. Preguntar sobre index.html**
Antes de generarlo, verificar que `README.md` está completo y consistente — contenido, diagramas, secciones y versiones. El README es la fuente de verdad del contenido. El `index.html` se genera desde él, no al revés.

Luego preguntar al usuario: *"¿Genero un index.html nuevo? Tarda un poco más."* Si el usuario confirma, generar desde el contenido actualizado de `README.md` aplicando la tipografía y contraste definidos en la paleta Fulgurar de `fulgurar.md` — tamaños de fuente, niveles de opacidad y estructura de secciones se conservan del diseño canónico. No se reinventa el diseño en cada respaldo. Si el usuario declina, incluir en el paquete el `index.html` existente sin modificaciones. El `index.html` es la página principal del repositorio en https://osmancitov.github.io/fulgurar/

**5. Entregar el paquete completo**
El paquete incluye **todos** los archivos del sistema sin excepción — los modificados en esta sesión y los que no tuvieron cambios. Ver regla absoluta al inicio de este protocolo.

Lista completa de archivos del paquete:
- `fulgurar.md`
- `protocolo-umbral.md`
- `protocolo-bodega.md`
- `protocolo-astillero.md`
- `protocolo-escuadra.md`
- `protocolo-jardin.md`
- `protocolo-prisma.md`
- `protocolo-oraculo.md`
- `protocolo-telegrafo.md`
- `protocolo-taller.md`
- `protocolo-respaldo.md`
- `bodega-header.html`
- `astillero-header-nave.html`
- `astillero-header-flota.html`
- `escuadra-header.html`
- `jardin-header.html`
- `telegrafo-header.html`
- `system-prompt.md`
- `README.md`
- `index.html`
- `CHANGELOG.md`
- `estado-desarrollo.md`
- `corpus-biblioteca.md`
