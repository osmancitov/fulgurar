# Protocolo de Respaldo — Fulgurar
*v1.3 · 2026-03-16 · Protocolo de generación de respaldos del sistema*

---

Cuando el usuario solicite un juego completo de archivos para respaldo, ejecutar en este orden:

**1. Revisar y actualizar archivos operativos**
- `fulgurar.md` — verificar vocabulario, identidad visual, ficha del corpus, flujos. Actualizar versión.
- `protocolo-bodega.md` — verificar criterios, taxonomía, SVG, prompts. Actualizar versión si hubo cambios.
- `protocolo-astillero.md` — verificar arquetipos, estratos, SVG, prompts. Actualizar versión si hubo cambios.
- `protocolo-escuadra.md` — verificar instrumentos, gráficos, SVG, prompts. Actualizar versión si hubo cambios.
- `protocolo-jardin.md` — verificar estratos, perfil, SVG, prompts. Actualizar versión si hubo cambios.
- `protocolo-taller.md` — verificar que el protocolo sigue siendo correcto. Actualizar versión si hubo cambios.
- `protocolo-respaldo.md` — verificar que el protocolo sigue siendo correcto. Actualizar versión si hubo cambios.
- Encabezados HTML — actualizar solo si hubo cambios de paleta o identidad visual.

**2. Revisar y actualizar el system prompt**
Evaluar si los cambios acumulados en la sesión permiten simplificarlo, mejorarlo o corregirlo. Actualizar versión.

**3. Revisar y actualizar archivos de documentación**
- `README.md` — revisar sección por sección: descripción del proyecto, cómo funciona, árbol de archivos con descripciones, instrucciones de instalación, instrucciones de actualización, tabla de versiones. Reescribir donde sea necesario.
- `CHANGELOG.md` — determinar el número de este respaldo contando las entradas con encabezado `## RESPALDO #N` en el historial existente y sumando uno. Agregar entrada completa con ese número y la fecha actual, archivo por archivo, con todos los cambios de la sesión. Orden inverso — lo más reciente arriba. Formato del encabezado: `## RESPALDO #[N] — [FECHA]`

**4. Generar README.html**
Generar desde el contenido actualizado de `README.md` usando la paleta Fulgurar definida en `fulgurar.md`. El README.html se regenera siempre — nunca es estático.

**5. Entregar el paquete completo**
El paquete incluye **todos** los archivos del sistema sin excepción — los modificados en esta sesión y los que no tuvieron cambios. El usuario no debe completar el paquete con archivos de otras fuentes.

Lista completa de archivos del paquete:
- `fulgurar.md`
- `protocolo-bodega.md`
- `protocolo-astillero.md`
- `protocolo-escuadra.md`
- `protocolo-jardin.md`
- `protocolo-taller.md`
- `protocolo-respaldo.md`
- `bodega-header.html`
- `astillero-header-nave.html`
- `astillero-header-flota.html`
- `escuadra-header.html`
- `jardin-header.html`
- `system-prompt.md`
- `README.md`
- `README.html`
- `CHANGELOG.md`
