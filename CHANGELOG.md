## RESPALDO #14 — 2026-03-20

### estado-desarrollo.md — eliminado
- Archivo retirado del sistema. Su contenido relevante vive en `README.md` (arquitectura, horizontes) y `corpus-biblioteca.md` (corpus, hallazgos).

### system-prompt.md
**v4.5 → v4.6**
- Instrucción de lectura de `estado-desarrollo.md` eliminada

### fulgurar.md
**v3.2 → v3.3**
- Referencia a `estado-desarrollo.md` en IDENTIDAD DEL SISTEMA eliminada
- `estado-desarrollo.md` eliminado de la lista de archivos en VERSIONADO

### protocolo-respaldo.md
**v2.1 → v2.2**
- `estado-desarrollo.md` eliminado del Paso 1 de revisión
- `estado-desarrollo.md` eliminado de la lista del paquete
- Paquete: 16 → 15 archivos

### README.md
- `estado-desarrollo.md` eliminado del árbol de archivos
- `estado-desarrollo.md` eliminado de la tabla de versiones
- Footer: Respaldo #14

---



### system-prompt.md
**v4.4 → v4.5**
- Comportamiento de saludo redefinido: presentación con lema en primera persona ("Soy Fulgurar. Consumo letras. Produzco luz.") seguida de tres vías numeradas: Descripción del sistema · Auto-diagnóstico · Entrar
- Eliminado el diagnóstico automático como respuesta al saludo — ahora es una opción que el usuario elige
- Detección de `toc.ncx` movida al Umbral — el saludo no la menciona
- Flujo de "Entrar" delegado completamente al Umbral

### protocolo-umbral.md
**v1.2 → v1.3**
- Modo 5 corregido: el Umbral ya no ejecuta automáticamente el Protocolo de Ingesta al detectar `toc.ncx` — pregunta primero y espera confirmación explícita
- Sección MODOS DE ENTRADA reescrita: el Umbral se activa desde el saludo y guía al usuario por los modos disponibles, incluyendo la mención de `toc.ncx` si existe
- Registro de voz ampliado con líneas de activación desde el saludo y línea de detección de `toc.ncx`
- Todas las referencias a encabezados HTML y SVG eliminadas
- `index.html` eliminado del diagrama de flujo del sistema

### fulgurar.md
**v3.1 → v3.2**
- "La Convergencia" eliminado como nombre arquitectónico — el elemento integrador es el Oráculo en todas las instancias
- Invariante sobre "La Convergencia" reemplazada por invariante sobre el Oráculo
- Biblioteca redeclarada como capa completamente independiente — sin mención al Prisma como dueño o productor principal; el Oráculo es quien escribe en la Biblioteca
- El Umbral reposicionado como protocolo de entrada, separado de los seis talleres — no aparece en la lista de talleres
- Sección IDENTIDAD DEL SISTEMA reestructurada: Umbral como protocolo de entrada · Los seis talleres · El elemento integrador · La Biblioteca
- Tabla de Marcas: Umbral separado visualmente de los talleres, "Telégrafo" duplicado eliminado
- RECEPCIÓN — Oferta de talleres: Umbral eliminado de la lista de talleres; la oferta aplica solo tras el Umbral
- PRODUCCIÓN — Sección de producto opcional HTML eliminada completamente
- PRODUCCIÓN — Referencia a SVG eliminada
- VERSIONADO — Lista de archivos: todos los `*-header.html` eliminados, `index.html` eliminado
- Sección IDENTIDAD VISUAL — Tipografía Fulgurar y tabla de contraste eliminadas (eran para HTML)
- Sección VOCABULARIO — "IDENTIDAD VISUAL" y "MARCA" actualizados para no mencionar SVG embebidos
- Párrafo de apertura: "El Umbral recibe" separado de los talleres en la descripción
- Invariante duplicada eliminada (el archivo tenía INVARIANTES DEL SISTEMA dos veces)

### protocolo-bodega.md
**v1.6 → v1.7**
- Orden de productos redefinido: Copa Maestra → Barricas → Cartografía → Sedimento → Cata
- Secciones Destilados y Cosecha fusionadas en nueva sección **Barricas** — cada capítulo contiene su destilado seguido de sus joyas
- Subtítulo de Barricas: *La esencia y las joyas de cada capítulo.*
- Cata movida al final — después del Sedimento
- Copa Maestra movida al inicio — da la imagen completa antes del detalle
- Vocabulario: COSECHA eliminado, BARRICA añadido
- Texto introductorio actualizado para reflejar el nuevo orden y la nueva sección
- Bitácora de procesamiento actualizada: "Cosechando joyas" y "Destilando capítulo por capítulo" reemplazados por "Destilando barrica por barrica"
- Sección Producto opcional HTML con SVG eliminada completamente
- Especificaciones SVG de imagen de cata eliminadas
- Referencia a SVG embebido en sección Cata eliminada

### protocolo-respaldo.md
**v2.0 → v2.1**
- Paso 4 (index.html) eliminado completamente — ya no se genera index.html
- Bitácora: líneas sobre index.html eliminadas
- Lista del paquete: todos los `*-header.html` eliminados, `index.html` eliminado
- Lista de revisión en Paso 1: línea de encabezados HTML eliminada
- 16 archivos en el paquete (antes 23)

### README.md
**Respaldo #12 → Respaldo #13**
- Nota inicial reemplazada: dos links con descripción — página del proyecto y repositorio GitHub
- Sección "Cómo funciona": Bodega actualizada con nuevo orden (copa maestra, barricas, etc.); Oráculo: "La Convergencia" eliminado
- Diagrama de arquitectura: "ORÁCULO — LA CONVERGENCIA" → "ORÁCULO"; descripción de Biblioteca actualizada para no mencionar al Prisma
- Sección "Cómo actualizar" eliminada
- Sección "Origen" eliminada
- Árbol de archivos: todos los `*-header.html` eliminados, `index.html` eliminado, `protocolo-oraculo.md` descripción sin "La Convergencia"
- Paso 4 de instalación: línea "El sistema leerá…" eliminada
- Tabla de versiones: archivos HTML eliminados, versiones actualizadas
- Footer: Respaldo #13

---

## RESPALDO #12 — 2026-03-20

### README.md
- Sección Qué es: "protocolo de entrada, seis talleres activos" — Umbral mencionado
- Sección Cómo funciona: El Umbral añadido como primer elemento antes de La Bodega
- Diagrama de arquitectura: UMBRAL añadido entre CORPUS y SEIS TALLERES
- Árbol de archivos: `protocolo-umbral.md` añadido; `system-prompt.md` — descripción corregida de "nunca cambia" a "instrucciones de arranque del sistema"
- Instrucciones de instalación paso 3: corregida la confusión — "Esta instrucción en el recuadro nunca cambia. Es system-prompt.md el que evoluciona."
- Tabla de versiones: actualizada con todas las versiones del Respaldo #12
- Sección Origen: párrafo del Umbral añadido
- Footer: Respaldo #10 → Respaldo #12

### fulgurar.md
**v3.1** *(corrección de invariante)*
- Invariante "El system prompt nunca cambia" corregida a "La instrucción del recuadro del proyecto nunca cambia" — con aclaración explícita de que es system-prompt.md el que evoluciona

### system-prompt.md
**v4.3 → v4.4**
- Umbral integrado: "Al recibir un corpus, lee siempre primero protocolo-umbral.md. El Umbral precede a cualquier taller sin excepción."
- Modo Flota actualizado: el Umbral produce la carta de presentación del autor
- Reglas absolutas: "Emite bitácora durante todo procesamiento — sin excepción" añadida
- "Nunca menciones los archivos del sistema en los productos entregados" simplificado

### index.html
**Regenerado completo desde README.md actualizado**
- Sección Talleres: El Umbral añadido como tarjeta ancho completo al inicio del grid, con badge "Primer paso · siempre"
- Sección Arquitectura: diagrama actualizado con UMBRAL entre CORPUS y SEIS TALLERES
- Sección Archivos: `protocolo-umbral.md` añadido al árbol con color propio (`umbral-f`); `system-prompt.md` — descripción corregida
- Sección Instalar paso 3: corrección de la confusión sobre qué nunca cambia
- Sección Versiones: tabla completa con versiones del Respaldo #12, `protocolo-umbral.md` marcado como nuevo
- Sección Origen: párrafo del Umbral añadido
- Footer: Respaldo #12

---

## RESPALDO #11 — 2026-03-20

### protocolo-umbral.md — archivo nuevo
- v1.2 — protocolo de entrada completo
- El Umbral es el primer paso antes de cualquier taller — recibe el corpus, produce la carta de presentación y el prompt de portada
- Cinco modos de entrada documentados: archivo adjunto, título y autor, ZIP Plano, nombre de autor (Modo Flota), corpus en proyecto
- Protocolo de Ingesta ZIP unificado para Modo 3 y Modo 5 — mismo procedimiento, distinta fuente
- Modo 5 — Corpus en proyecto: el Umbral detecta `toc.ncx` en los archivos del sistema y ejecuta el Protocolo de Ingesta desde ahí; corpus permanente disponible en sesiones posteriores
- Carta de presentación con seis secciones: Registro de Ingesta (primera, siempre) · Sinopsis · Personajes o Figuras Clave · Estructura del Corpus · Contexto · Temas Centrales
- Registro de Ingesta como primera sección — trazabilidad del proceso, formato distinto por modo de entrada
- El Registro de Ingesta se genera después de la confirmación del usuario en Modos 3 y 5 — refleja el corpus ya delimitado
- Prompt de portada: atmósfera del corpus, no ilustración de escena; etiqueta `FULGURAR · TÍTULO · APELLIDO` en esquina inferior
- Registro de voz propio: quien abre la puerta — preciso, útil, sin demora
- Modos de entrada y Protocolo de Ingesta ZIP migrados desde `fulgurar.md` — su lugar natural es el Umbral
- Diagrama de flujo del sistema con bifurcación ZIP/proyecto vs modos directos
- Bloques de actualización para `fulgurar.md`, `system-prompt.md` y `protocolo-respaldo.md` documentados al final

### fulgurar.md
**v3.0 → v3.1**
- Párrafo de apertura: El Umbral añadido al inicio de la lista de talleres
- IDENTIDAD DEL SISTEMA: El Umbral añadido como primer elemento, conteo actualizado a "protocolo de entrada, seis talleres activos y La Convergencia"
- Tabla de Marcas: `UMBRAL OSMANCITO · ENTRADA` añadida
- RECEPCIÓN: modos de entrada y Protocolo de Ingesta ZIP eliminados — migrados a `protocolo-umbral.md`; sección ahora contiene solo la oferta de talleres con referencia al Umbral
- Oferta de talleres: Umbral añadido como primer elemento, Telégrafo duplicado eliminado
- OPERACIÓN — Registros de voz: Umbral añadido como primer registro
- OPERACIÓN — Reglas generales: referencia al Protocolo de Ingesta ZIP actualizada para apuntar al Umbral
- PRODUCCIÓN — Nombres de archivo: Umbral añadido con sus dos productos
- VERSIONADO — Lista de archivos: `protocolo-umbral.md` añadido

### protocolo-bodega.md
**v1.5 → v1.6**
- Sección REGISTRO DE VOZ añadida — acuse de recibo y bitácora por etapas de destilación
- Bitácora cubre: lectura del corpus, destilación por capítulo, cartografía, cosecha, copa maestra, cata, sedimento, prompt de imagen

### protocolo-astillero.md
**v1.7 → v1.8**
- Sección REGISTRO DE VOZ añadida — acuse de recibo y bitácora para Modo Nave y Modo Flota por separado
- Bitácora Modo Nave cubre los diez estratos en secuencia, dictamen, cata y prompt
- Bitácora Modo Flota cubre: identificación del capitán, mapeo de la flota, clasificación, tensiones, veredicto, carta náutica, prompt

### protocolo-taller.md
**v1.1 → v1.2**
- Sección REGISTRO DE VOZ añadida — el sistema en modo de expansión construyéndose a sí mismo
- Bitácora diferenciada para Fase 1 (exploración) y Fase 2 (propuesta completa)

### protocolo-respaldo.md
**v1.9 → v2.0**
- Sección REGISTRO DE VOZ añadida — archivero metódico, preciso, sin drama
- Bitácora paso a paso: revisión de archivos, actualizaciones, CHANGELOG, pregunta sobre index.html, ensamblado del paquete
- `protocolo-umbral.md` añadido al Paso 1 de revisión de archivos operativos
- `protocolo-umbral.md` añadido a la lista completa del paquete

---

## RESPALDO #10 — 2026-03-19

### README.md
- Diagrama arquitectura corregido: Oráculo unificado en una sola línea — operaciones en la misma línea que el nombre
- protocolo-oraculo.md en árbol de archivos: descripción actualizada con "— La Convergencia"
- Sección Horizontes agregada entre Arquitectura y Archivos
- "los cuatro talleres no podían responder" → "los talleres anteriores"
- Footer actualizado: Respaldo #7 → Respaldo #9 (en esta entrega #10)

### estado-desarrollo.md
- "los cuatro talleres no podían responder solos" → "los talleres anteriores no podían responder solos" en la sección Historia

### protocolo-respaldo.md
**v1.8 → v1.9**
- Paso 4 reforzado: verificar que README.md está completo y consistente antes de generar index.html
- Regla explícita: el README es la fuente de verdad del contenido — el index.html se genera desde él, no al revés


---

## RESPALDO #9 — 2026-03-19

### fulgurar.md
**v2.9 → v3.0**
- Paleta Fulgurar expandida con dos tablas nuevas:
  - Tipografía Fulgurar: fuente base 20px/1.75, nav 0.75rem, h1 clamp(1.3rem,3vw,1.6rem), h2 1.0rem, monoespaciado 0.92rem, etiquetas 0.78rem
  - Contraste mínimo sobre fondo oscuro: cuerpo 0.85, secundario 0.72, terciario 0.60, decorativo 0.45
- Nota canónica: estos valores son la referencia para cualquier documento HTML del sistema

### protocolo-respaldo.md
**v1.7 → v1.8**
- Paso 4 actualizado: el index.html se genera aplicando la tipografía y contraste definidos en la paleta Fulgurar de fulgurar.md — no se reinventa el diseño en cada respaldo

### index.html · estado-desarrollo.md · README.md
- Ajustes de legibilidad y diagrama de arquitectura actualizado

---

## RESPALDO #8 — 2026-03-19

### fulgurar.md · protocolo-oraculo.md · protocolo-telegrafo.md · protocolo-prisma.md
- Prefijo `Producto —` aplicado a todos los outputs
- INVARIANTES DEL SISTEMA agregadas
- La Convergencia establecida como nombre arquitectónico del Oráculo

---

## RESPALDO #7 — 2026-03-19

### protocolo-telegrafo.md — archivo nuevo · telegrafo-header.html — archivo nuevo
### fulgurar.md · system-prompt.md · protocolo-prisma.md · protocolo-oraculo.md · protocolo-respaldo.md
- Telégrafo integrado al sistema

---

# Fulgurar — Changelog
*Registro completo de cambios del proyecto*

---

## RESPALDO #6 — 2026-03-19

### protocolo-prisma.md — archivo nuevo · protocolo-oraculo.md — archivo nuevo
### corpus-biblioteca.md · estado-desarrollo.md · fulgurar.md · system-prompt.md · protocolo-respaldo.md
- Prisma y Oráculo integrados al sistema; 8 corpus en Biblioteca; 6 hallazgos

---

## RESPALDO #5 — 2026-03-19

### system-prompt.md · fulgurar.md · protocolo-respaldo.md · README.md
### estado-desarrollo.md — archivo nuevo · prisma-arquitectura.md — archivo nuevo · corpus-biblioteca.md — archivo nuevo
- Prisma como taller en desarrollo; diagnóstico automático al saludo

---

## RESPALDO #4 — 2026-03-16

### README.md
- Nota al inicio simplificada

---

## RESPALDO #3 — 2026-03-16

### fulgurar.md · protocolo-respaldo.md · README.md · index.html
- URL del sistema; index.html como página principal del repositorio

---

## RESPALDO #2 — 2026-03-16

### README.md · protocolo-respaldo.md · fulgurar.md
- Instrucciones de instalación simplificadas

---

## RESPALDO #1 — 2026-03-16

### fulgurar.md · system-prompt.md · protocolo-respaldo.md
### protocolo-escuadra.md — nuevo · protocolo-jardin.md — nuevo · protocolo-taller.md — nuevo
- Sistema renombrado a Fulgurar; Escuadra y Jardín añadidos

---

## SESIONES 2026-03-15

### Versiones iniciales del sistema
- Protocolo Θ∆ → Fulgurador Osmancito → Fulgurar
- Bodega, Astillero, paletas, README, CHANGELOG

---

*Fulgurar · Consume letras. Produce luz.*
