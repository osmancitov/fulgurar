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

### index.html
**Ajustes de legibilidad para pantallas de baja resolución**
- Fuente base: 18px → 20px · interlineado 1.7 → 1.75
- Nav links: 0.6rem → 0.75rem · letter-spacing reducido · padding más generoso
- Títulos de sección: clamp mínimo subido a 1.3rem
- Subtítulos h2: 0.9rem → 1.0rem
- Texto monoespaciado (árbol, diagrama, tabla): 0.82rem → 0.92rem
- Etiquetas pequeñas: 0.65rem → 0.78rem
- Contraste general subido: párrafos 0.75→0.85, nav 0.35→0.60, descripciones árbol 0.4→0.65, footer 0.25→0.45
- Diagrama arquitectura: Oráculo unificado en una sola línea — operaciones en la misma línea que el nombre
- Tabla de versiones: fulgurar.md v3.0, protocolo-respaldo.md v1.8

### estado-desarrollo.md · README.md
- Diagrama arquitectura actualizado: Oráculo unificado en una sola línea


---

## RESPALDO #8 — 2026-03-19

### fulgurar.md
**v2.7 → v2.9**
- v2.8: Prefijo `Producto —` aplicado a todos los nombres de archivo de output
- v2.8: Telégrafo duplicado en registros de voz y nombres de archivo eliminado
- v2.9: Sección INVARIANTES DEL SISTEMA agregada antes de VOCABULARIO — seis reglas estructurales que gobiernan cómo evoluciona el sistema sin crear inconsistencias en cascada
- v2.9: Regla estructural del system prompt migrada de IDENTIDAD DEL SISTEMA a INVARIANTES

### protocolo-oraculo.md
**v1.1 → v1.2**
- Subtítulo corregido: "Séptimo elemento" → "La Convergencia — integrador del sistema"
- Sección MODOS DE OPERACIÓN agregada antes de LOS CUATRO MOMENTOS
- Modo sesión única documentado con flujo completo
- Modo dos sesiones documentado: archivos Producto temporales, corpus-biblioteca.md como registro permanente
- Cómo el Oráculo ofrece la elección al usuario documentado
- Prefijo `Producto —` aplicado al nombre de archivo de output

### protocolo-telegrafo.md
**v1.0** *(subtítulo corregido)*
- Subtítulo corregido: "Séptimo taller" → "Teoría de la información" — sin ordinal de posición
- Prefijo `Producto —` aplicado al nombre de archivo de output y al prompt de imagen

### protocolo-prisma.md
**v1.1** *(nombres de archivo actualizados)*
- Prefijo `Producto —` aplicado a nombres de archivo
- "todos los talleres" en lugar de "seis talleres" — agnóstico al conteo

### protocolo-bodega.md · protocolo-astillero.md · protocolo-escuadra.md · protocolo-jardin.md
**sin cambio de versión** *(nombres de archivo actualizados)*
- Prefijo `Producto —` aplicado a todos los nombres de archivo de output y prompts de imagen

### protocolo-taller.md
**v1.1** *(sin cambio de versión — correcciones menores)*
- "Fase 1" y "Fase 2" eliminados — reemplazados por lenguaje descriptivo sin ordinales
- Lista de registros de voz de contraste completada: Jardín, Prisma y Telégrafo agregados

### estado-desarrollo.md
**v0.3 → v0.4**
- Subtítulo: "Fase 1 completa · Fase 2 en diseño" → "Arquitectura completa · Tres horizontes"
- Párrafo de apertura: referencias a fases eliminadas — el sistema opera y crece
- Encabezado "Estado actual — Fase 1 completa" → "Estado actual"
- Sección "Hoja de ruta" con cuatro fases reemplazada por "Horizontes"
  - Horizonte 1 — Masa crítica: más corpus, H6 y hipótesis small-world del Telégrafo
  - Horizonte 2 — Profundidad operativa: La Convergencia produciendo El Elemento
  - Horizonte 3 — Apertura: manual, sistema listo para otros usuarios
- Tabla de archivos del sistema completada con todos los protocolos
- "Séptimo elemento" → "La Convergencia" en tabla de archivos
- "La pregunta que los cinco talleres no podían responder" → "los talleres anteriores"

### index.html
**Regenerado completo desde Respaldo #6 a Respaldo #8**
- Hero badge: "La Convergencia en construcción · Potencia 45%"
- Nav: sección Horizontes agregada
- Sección Qué es: seis talleres, La Convergencia
- Sección Talleres: El Telégrafo agregado con tarjeta y color cobre — grid ahora de 7 elementos
- Sección Arquitectura: diagrama actualizado con SEIS TALLERES y LA CONVERGENCIA, flujo Producto documentado
- Sección Horizontes: nueva — los tres horizontes con sus indicadores de llegada
- Sección Archivos: árbol completo con telegrafo-header.html y protocolo-telegrafo.md, descripciones actualizadas
- Sección Versiones: tabla actualizada con todas las versiones actuales, Telégrafo marcado como nuevo
- Sección Origen: Telégrafo y La Convergencia en la narrativa
- Footer: Respaldo #8

### README.md
- Sección Horizontes agregada — reemplaza referencias implícitas a fases
- Tabla de versiones actualizada: fulgurar.md v2.9, protocolo-oraculo.md v1.2, protocolo-respaldo.md v1.7, estado-desarrollo.md v0.4

### Arquitectura — cambios conceptuales de esta sesión
- **La Convergencia** establecida como nombre arquitectónico del Oráculo — estable independientemente del número de talleres
- **INVARIANTES DEL SISTEMA** en fulgurar.md — fuente de verdad para las reglas estructurales del sistema
- **Prefijo `Producto`** — convención oficial para todos los outputs de talleres
- **Modo dos sesiones** documentado en protocolo-oraculo.md — flujo de corpus-biblioteca.md como registro permanente liviano
- **Ordinales eliminados** de subtítulos de protocolos — ningún protocolo declara su posición en el sistema


---

## RESPALDO #7 — 2026-03-19

### protocolo-telegrafo.md — archivo nuevo
- v1.0 — protocolo completo del Telégrafo como séptimo taller
- Semilla: instrumentos de teoría de la información — Shannon, autómatas Moore/Mealy, grafos topológicos
- Cinco instrumentos: Entropía de Shannon · Mapa de Sorpresa · Autómata del Corpus · Topología de la Red · Redundancia y Capacidad de Canal
- Vocabulario completo derivado de la metáfora del operador de telégrafo
- Hipótesis falseable central: los corpus canónicos tienen redes conceptuales small-world (firma matemática de H4)
- Registro de voz: operador técnico, alerta, imperturbable
- Producto: Despacho — Perfil de Transmisión + Señal Clave
- SVG embebido: cinta telegráfica expandida con datos del análisis y código Morse de la Señal Clave
- Prompt de imagen: estación telegráfica nocturna bajo lámpara de latón
- Output para el Oráculo: tabla de inputs definida

### telegrafo-header.html — archivo nuevo
- v1.0 — encabezado visual Telégrafo, paleta cobre telegráfico
- Logo: aparato Morse animado — palanca pulsa código F (··-·) en Morse, galvanómetro oscila, cinta de papel corre, chispa en los contactos
- Animaciones: tg-lever · tg-needle · tg-spark · tg-glow · tg-tape

### fulgurar.md
**v2.6 → v2.7**
- Párrafo de apertura actualizado: Telégrafo mencionado
- IDENTIDAD DEL SISTEMA: seis talleres activos + Oráculo en construcción — Telégrafo agregado
- Tabla de Marcas: Telégrafo agregado — `TELÉGRAFO OSMANCITO · OPERADOR`
- Paletas: Telégrafo agregado — cobre `#b87333`, fondo negro `#0f0c08`
- RECEPCIÓN — Oferta de taller: Telégrafo agregado
- OPERACIÓN — Registros de voz: Telégrafo agregado
- PRODUCCIÓN — Nombres de archivo: Telégrafo agregado (.md y .html)
- VERSIONADO — Lista de archivos: `protocolo-telegrafo.md` y `telegrafo-header.html` agregados

### system-prompt.md
**v4.2 → v4.3**
- Telégrafo agregado al flujo de recepción: `Telégrafo → lee protocolo-telegrafo.md`

### protocolo-prisma.md
**v1.0 → v1.1**
- Sección RELACIÓN CON LOS OTROS TALLERES reemplazada por RELACIÓN CON EL ORÁCULO
- La tabla de inputs que vivía aquí migrada al protocolo-oraculo.md donde pertenece
- El Prisma opera ahora sobre texto crudo exclusivamente — produce firma autónoma
- Frontera con el Oráculo limpia: el Prisma mide, el Oráculo integra

### protocolo-oraculo.md
**v1.0 → v1.1**
- Tabla de inputs de talleres migrada aquí desde protocolo-prisma.md
- Telégrafo agregado a la tabla: entropía, autómata, topología de red — enriquece H4 y H6
- Clarificación explícita: es el Oráculo quien integra los outputs, no el Prisma

### protocolo-respaldo.md
**v1.6 → v1.7**
- Paso 4 modificado: el sistema pregunta al usuario antes de generar index.html
- Si el usuario declina, incluye el index.html existente sin modificaciones


---

# Fulgurar — Changelog
*Registro completo de cambios del proyecto*

---

## RESPALDO #6 — 2026-03-19

### protocolo-prisma.md — archivo nuevo
- v1.0 — protocolo completo del Prisma como quinto taller
- Absorbe `prisma-arquitectura.md` — ese archivo queda retirado del sistema
- Origen y filosofía de la Díada: φ como atractor, no como axioma
- Las cinco geometrías con variables, pseudocódigo y hallazgos empíricos por geometría
- Relación con los cuatro talleres — tabla de inputs
- Registro de voz, formato de producción (.md por defecto, .html opcional), identidad visual

### protocolo-oraculo.md — archivo nuevo
- v1.0 — diseño completo del Oráculo como sexto elemento del sistema
- Vocabulario propio: convergencia, convergencia parcial, situación, calibración, confianza por hallazgo, potencia nominal
- Los cuatro momentos: Integrar · Situar · Calibrar · Ejecutar — con criterios explícitos
- Las cuatro operaciones: Verificar · Corregir · Traducir · Generar — con pseudocódigo
- Tabla de confianza por hallazgo con 8 corpus
- Dos modos de operación: convergencia completa vs parcial
- Potencia nominal al 45% con escala logarítmica sobre 100 corpus
- Estado actual de capacidades operativas
- Registro de voz: el sistema hablando sobre sí mismo, calibrado
- Formato de producción, identidad visual, actualizaciones para el sistema

### corpus-biblioteca.md
**v0.3 → v0.4**
- Corpus #8 agregado: El proceso — Franz Kafka · Novela · 1925 (póstuma)
- Firma geométrica completa de Kafka: curvatura 0.72, apertura 3/4, dimensión 1.8, espiral descendente sin retorno, red sin centro estable
- Hallazgo específico: K. tiene la curvatura más baja de los conceptos principales de su propia novela
- Tabla de corpus actualizada: 8 corpus · formato revisado
- Tabla de firmas geométricas actualizada con columna Kafka
- H1 actualizado: tabla incluye El proceso (3/4), correlación sostenida
- H2 refinado: primera excepción canónica (Kafka 0.72) — dos rutas a la grandeza
- H3 actualizado: seis estrategias (sustracción sistemática agregada)
- H5: confirmación estructural en Kafka
- H6 nuevo: coherencia por exclusión como categoría propia (provisional, 1/8)
- Próximos corpus actualizado: El proceso eliminado, El extranjero agregado como segunda prueba de H6

### estado-desarrollo.md
**v0.1 → v0.2**
- Reescritura completa con arquitectura correcta del sistema
- Arquitectura: cinco talleres + Oráculo + Biblioteca (diagrama actualizado)
- Notas de arquitectura: modo parcial, Escuadra/Prisma independientes, potencia nominal
- Tabla de 8 corpus con curvatura, apertura y estrategia
- Seis hallazgos con nivel de confianza
- Hoja de ruta actualizada: Fase 1 marcada completa, Fase 2 como siguiente paso
- Tabla de archivos del sistema actualizada

### fulgurar.md
**v2.5 → v2.6**
- Texto de apertura actualizado: menciona los cinco talleres y el Oráculo
- IDENTIDAD DEL SISTEMA: cinco talleres activos + Oráculo en construcción con potencia 45%
- Tabla de Marcas: Prisma y Oráculo agregados
- RECEPCIÓN: Prisma y Oráculo agregados a la oferta de taller
- OPERACIÓN: Oráculo agregado a los registros de voz
- PRODUCCIÓN: Oráculo agregado a nombres de archivo
- VERSIONADO: lista de archivos actualizada — `prisma-arquitectura.md` reemplazado por `protocolo-prisma.md` y `protocolo-oraculo.md`

### system-prompt.md
**v4.1 → v4.2**
- Prisma: `prisma-arquitectura.md` reemplazado por `protocolo-prisma.md`
- Oráculo agregado al flujo de lectura: lee `protocolo-oraculo.md` y `corpus-biblioteca.md`
- Diagnóstico de saludo actualizado: menciona fase del Oráculo en lugar de fase del Prisma

### protocolo-respaldo.md
**v1.6 → v1.6** *(sin cambio de versión — solo actualización de lista)*
- `prisma-arquitectura.md` reemplazado por `protocolo-prisma.md` en la lista de revisión
- `protocolo-oraculo.md` agregado a la lista de revisión y al paquete
- Lista del paquete actualizada: 20 archivos

### protocolo-bodega.md
**v1.5** *(sin cambios adicionales en esta sesión)*

### protocolo-astillero.md
**v1.7** *(sin cambios adicionales en esta sesión)*

### protocolo-escuadra.md
**v1.1** *(sin cambios adicionales en esta sesión)*

### protocolo-jardin.md
**v1.1** *(sin cambios adicionales en esta sesión)*

### protocolo-taller.md
**v1.1** *(sin cambios adicionales en esta sesión)*

### README.md
- Reescritura completa
- Descripción actualizada: cinco talleres + Oráculo en construcción
- Sección "Arquitectura" nueva con diagrama completo
- Árbol de archivos actualizado: `prisma-arquitectura.md` reemplazado por `protocolo-prisma.md` y `protocolo-oraculo.md`
- Tabla de versiones actualizada con todos los archivos

### index.html
- Regenerado completo desde README.md actualizado
- Hero badge: "Oráculo en construcción · Potencia 45%"
- Sección Talleres: Prisma y Oráculo agregados como tarjetas
- Sección Arquitectura nueva: diagrama y descripción de la Biblioteca como capa independiente
- Sección Hallazgos nueva: 6 hallazgos con niveles de confianza
- Árbol de archivos actualizado
- Tabla de versiones actualizada
- Footer: Respaldo #6

### prisma-arquitectura.md — retirado
- Absorbido completamente por `protocolo-prisma.md`
- El archivo no forma parte del paquete a partir de este respaldo

---

## RESPALDO #5 — 2026-03-19

### system-prompt.md
**v3.0 → v4.0**
- Instrucción agregada: leer `estado-desarrollo.md` al arranque
- Prisma agregado como taller con sus archivos de referencia
- Instrucción de diagnóstico automático al recibir saludo sin corpus

### fulgurar.md
**v2.3 → v2.4**
- Regla estructural agregada en IDENTIDAD DEL SISTEMA: el system prompt nunca cambia — siempre dice *Lee system-prompt.md*
- Mención de expansión activa hacia Prisma en IDENTIDAD DEL SISTEMA
- Prisma agregado a la oferta de talleres en RECEPCIÓN
- Registro de voz del Prisma agregado en OPERACIÓN
- Nombre de archivo Prisma agregado en PRODUCCIÓN
- `estado-desarrollo.md`, `prisma-arquitectura.md`, `corpus-biblioteca.md` agregados a la lista de archivos del sistema en VERSIONADO

### protocolo-respaldo.md
**v1.4 → v1.5**
- Regla absoluta agregada al inicio: todo respaldo es siempre un paquete completo
- `estado-desarrollo.md`, `prisma-arquitectura.md`, `corpus-biblioteca.md` agregados a la lista de archivos del paquete y al paso 1 de revisión

### README.md
- Descripción actualizada con mención a Prisma
- Árbol de archivos actualizado con los tres archivos nuevos del proyecto Prisma
- Instrucciones de instalación actualizadas: paso 4 ahora dice escribir *Hola* y el sistema se orienta solo
- Tabla de versiones actualizada con todos los archivos

### index.html
- Regenerado completo desde README.md actualizado con paleta Fulgurar
- Árbol de archivos actualizado
- Instrucciones de instalación actualizadas
- Tabla de versiones actualizada
- Footer: Respaldo #5

### estado-desarrollo.md — archivo nuevo
- v0.1 — estado actual completo del proyecto Prisma
- Seis capas de la arquitectura documentadas
- Filosofía del proyecto: Díada, φ, instrumentos matemáticos
- Siete corpus procesados con tabla de firmas
- Cinco hallazgos empíricos
- Hoja de ruta Fases 1-4
- Próximo corpus: El proceso de Kafka

### prisma-arquitectura.md — archivo nuevo
- v0.2 — algoritmo completo con pseudocódigo
- Las cinco geometrías documentadas
- Las cuatro operaciones con pseudocódigo
- Notas de diseño: por qué cinco geometrías, por qué φ es referencia no axioma

### corpus-biblioteca.md — archivo nuevo
- v0.2 — siete corpus procesados
- Fichas individuales de cada corpus
- Tabla comparativa completa
- Cinco hallazgos empíricos con evidencia
- Próximos corpus a procesar

---


---

## RESPALDO #4 — 2026-03-16

### README.md
- Nota al inicio simplificada: *Esta información también está disponible en la página del proyecto.* con enlace directo — sin mencionar index.html

---

## RESPALDO #3 — 2026-03-16

### fulgurar.md
**v2.1 → v2.3**
- URL del sistema agregada en sección IDENTIDAD DEL SISTEMA: https://osmancitov.github.io/fulgurar/
- Sección PRODUCCIÓN: referencia a `index.html` como documentación visual del sistema
- Lista de archivos del sistema en VERSIONADO actualizada: `README.html` → `index.html`

### protocolo-respaldo.md
**v1.2 → v1.4**
- Paso 4: `README.html` renombrado a `index.html` — página principal del repositorio GitHub Pages
- Lista del paquete actualizada: `README.html` → `index.html`

### README.md
- Nota al inicio: versión en texto plano, con enlaces a `index.html` y a la página del proyecto
- Enlace de descarga agregado en instrucciones de instalación: `fulgurar-main.zip`
- Instrucciones de instalación actualizadas: nombre *Fulgurar*, descripción *Sistema de lectura profunda*, system prompt *Lee el archivo system-prompt.md*
- Tabla de versiones actualizada

### index.html *(antes README.html)*
- Renombrado para funcionar como página principal de GitHub Pages
- Botón de descarga agregado en sección de instalación
- Árbol de archivos actualizado: `README.html` → `index.html`
- Instrucciones de instalación actualizadas
- Tabla de versiones actualizada
- Footer: Respaldo #3

---

## RESPALDO #3 — 2026-03-16

### fulgurar.md
**v2.2 → v2.3**
- URL del sistema agregada en sección IDENTIDAD DEL SISTEMA: `https://osmancitov.github.io/fulgurar/`
- Sección PRODUCCIÓN: `index.html` como nombre oficial del archivo de documentación visual — reemplaza `README.html`
- Lista de archivos en sección VERSIONADO actualizada con `index.html`

### protocolo-respaldo.md
**v1.3 → v1.4**
- Paso 4 actualizado: genera `index.html` en lugar de `README.html`
- URL del sistema agregada en paso 4
- Lista del paquete actualizada: `index.html` en lugar de `README.html`

### README.md
- Nota al inicio: versión en texto plano, con enlaces a `index.html` y a la URL del sistema
- Enlace de descarga agregado en sección de instalación: `fulgurar-main.zip`
- Instrucciones de instalación actualizadas: nombre *Fulgurar*, descripción *Sistema de lectura profunda*, system prompt *Lee el archivo system-prompt.md*
- Tabla de versiones actualizada

### index.html *(antes README.html)*
- Renombrado a `index.html` — página principal del repositorio GitHub Pages
- Botón de descarga agregado en sección de instalación
- Árbol de archivos actualizado: `index.html` en lugar de `README.html`
- Instrucciones de instalación actualizadas
- Tabla de versiones actualizada
- Footer: Respaldo #3

---

## RESPALDO #2 — 2026-03-16

### README.md · README.html
- Instrucciones de instalación actualizadas:
  - Paso 1: nombre sugerido *Fulgurar*, descripción sugerida *Sistema de lectura profunda*
  - Paso 3: system prompt simplificado — escribir *Lee el archivo system-prompt.md* en el recuadro de instrucciones. Sin copiar ni pegar archivos.
- Instalación ahora completable sin ningún conocimiento previo de Claude

### protocolo-respaldo.md
**v1.2 → v1.3**
- Paso 5 actualizado: lista de archivos del paquete refleja 16 archivos

### fulgurar.md
**v2.1 → v2.2**
- Sección PRODUCCIÓN: dos archivos por taller por defecto ya documentados en versión anterior — sin cambios adicionales

---

## RESPALDO #1 — 2026-03-16 (versión final)

### fulgurar.md
**v2.0 → v2.1**
- Sección PRODUCCIÓN actualizada: dos archivos por taller por defecto — HTML de análisis y Markdown de prompt
- Prompt en español y en inglés, con placeholders resueltos para el corpus específico
- Nombres de archivo de prompt agregados como fuente de verdad

### protocolo-respaldo.md
**v1.1 → v1.2**
- Paso 5 reforzado: paquete incluye todos los archivos sin excepción — modificados y sin cambios
- Lista explícita de los 16 archivos del paquete agregada
- Instrucción: el usuario no debe completar el paquete con archivos de otras fuentes

---

## RESPALDO #1 — 2026-03-16

### fulgurar.md
**v1.6 → v2.0** *(versión mayor — renombramiento del sistema y expansión estructural)*
- Sistema renombrado de **Fulgurador Osmancito** a **Fulgurar**
- Dos talleres nuevos agregados: **Escuadra** y **Jardín**
- Sección IDENTIDAD DEL SISTEMA actualizada: cuatro talleres activos, mención a `protocolo-taller.md`
- Tabla de Marcas actualizada: Escuadra y Jardín agregados
- Paletas nuevas agregadas: Escuadra (violeta pizarra) y Jardín (verde musgo)
- Sección RECEPCIÓN — Oferta de taller expandida a cuatro talleres
- Registros de voz y bitácoras de Escuadra y Jardín agregados en sección OPERACIÓN
- Encabezados HTML y Nombres de archivo de Escuadra y Jardín agregados en sección PRODUCCIÓN
- Lista de archivos del sistema en sección VERSIONADO actualizada

### system-prompt.md
**v2.2 → v3.0** *(versión mayor — renombramiento y dos talleres nuevos)*
- Sistema renombrado a Fulgurar
- Escuadra y Jardín agregados al flujo de recepción
- `protocolo-taller.md` referenciado para construcción de talleres nuevos

### protocolo-respaldo.md
**v1.0 → v1.1**
- Sistema renombrado a Fulgurar
- `fulgurar.md` como nombre actualizado del módulo central
- Protocolos de Escuadra y Jardín agregados al paso 1
- `protocolo-taller.md` agregado al paso 1
- Contador de respaldos agregado al paso 3: el sistema cuenta entradas `## RESPALDO #N` anteriores y numera la nueva

### protocolo-escuadra.md
**v1.0 — archivo nuevo**
- Taller completo: vocabulario, seis instrumentos, el levantamiento, registro de voz, formato HTML, identidad visual, SVG carta geométrica, prompt mesa del arquitecto, bloques de actualización para `fulgurar.md`
- Semilla: *"quiero un taller de análisis matemático"*
- Decisiones del usuario: nombre Escuadra, operador Geómetra, SVG carta celeste, prompt mesa del arquitecto
- Decisiones del sistema: vocabulario, seis instrumentos, paleta violeta pizarra, estructura HTML completa

### escuadra-header.html
**v1.0 — archivo nuevo**
- Encabezado visual Escuadra: escuadra de precisión animada + amanita, paleta violeta pizarra
- Logo: escuadra que rota 90° en cada ángulo, cuadrícula de papel técnico, línea de trazo y punto de hallazgo animados

### protocolo-jardin.md
**v1.0 — archivo nuevo**
- Taller completo: vocabulario, cuatro estratos, el perfil, registro de voz, formato HTML, identidad visual, SVG carta del jardín, prompt corte de suelo, bloques de actualización para `fulgurar.md`
- Principio central: perfil de suelos — cada estrato admite lecturas simultáneas, las tensiones no se resuelven sino se exponen
- Nombre del taller derivado de PaRDeS — palabra hebrea para jardín y acrónimo de los cuatro niveles exegéticos; el vocabulario operativo es propio
- Decisiones del usuario: síntesis propia para los cuatro estratos, principio de tensiones simultáneas en todos los estratos
- Decisiones del sistema: nombres de los estratos, vocabulario, paleta verde musgo, estructura HTML completa

### jardin-header.html
**v1.0 — archivo nuevo**
- Encabezado visual Jardín: corte transversal de suelo animado + amanita, paleta verde musgo
- Logo: cuatro estratos que se iluminan en secuencia, raíz que desciende ramificándose, semilla dorada pulsando en el estrato más profundo

### protocolo-taller.md
**v1.0 — archivo nuevo**
- Protocolo meta-sistema para construcción de talleres nuevos
- Dos fases: exploración conversacional + propuesta completa
- Principio central: el sistema hace el trabajo operativo, el usuario se concentra en decisiones creativas irreducibles
- Principio de rescate: todo dato es candidato a instrumento si encuentra la relación correcta
- Corrección pendiente: la sección 6 debe especificar explícitamente que el encabezado HTML se construye como parte de la entrega — no solo se describe

### README.md
- Sistema renombrado a Fulgurar
- Cuatro talleres documentados
- Árbol de archivos actualizado con todos los archivos nuevos
- Tabla de versiones actualizada

### README.html
- Regenerado completo con nombre Fulgurar y cuatro talleres

---

## SESIÓN 2026-03-15 — Ronda 2

### protocolo-respaldo.md
**v1.0 — archivo nuevo**
- Protocolo de generación de respaldos extraído del system prompt y centralizado como archivo independiente. Contiene los cinco pasos del proceso de respaldo: revisión de archivos operativos, revisión del system prompt, revisión de documentación, generación de README.html, entrega del paquete.

### system-prompt.md
**v2.1 → v2.2**
- Sección RESPALDO DEL SISTEMA eliminada — migrada a `protocolo-respaldo.md`
- Reemplazada por una línea: *Para respaldos, lee `protocolo-respaldo.md`*
- System prompt reducido a su versión más minimalista

### fulgurador.md
**v1.5 → v1.6**
- Paleta Destello agregada en sesión anterior — documentada aquí
- Sección VERSIONADO actualizada: los historiales individuales de cada archivo se eliminan; el detalle vive en este CHANGELOG; cada archivo mantiene solo la línea de versión y fecha al inicio
- Lista de archivos del sistema actualizada para incluir `protocolo-respaldo.md`
- Bloque HISTORIAL eliminado del archivo

### protocolo-bodega.md
**v1.3 → v1.4**
- Bloque HISTORIAL eliminado del archivo

### protocolo-astillero.md
**v1.5 → v1.6**
- Bloque HISTORIAL eliminado del archivo

### README.md
- Árbol de archivos actualizado: agregados `README.html` y `protocolo-respaldo.md`
- Instrucciones de instalación corregidas: todos los archivos deben subirse al proyecto sin distinción (Opción A)
- Instrucciones de actualización actualizadas
- Tabla de versiones actualizada

### README.html
- Regenerado con paleta Destello
- Árbol de archivos actualizado
- Tabla de versiones actualizada

### CHANGELOG.md
- Orden invertido: lo más reciente aparece primero
- Menciones al nombre anterior del sistema eliminadas
- Este archivo es ahora la única fuente de verdad para el historial de todos los archivos

---

## SESIÓN 2026-03-15 — Ronda 1

### fulgurador.md
**v1.4 → v1.5**
- Paleta **Destello** agregada a la sección IDENTIDAD VISUAL — paleta del sistema completo, usada en documentación y README
- Variables: `--void #080808`, `--ember #c8922a`, `--ember-dim #7a5518`, `--spark #f5e8c8`, `--ash #1a1610`

### system-prompt.md
**v2.0 → v2.1**
- Instrucción de respaldo ampliada con revisión documental completa de README.md sección por sección
- Agregada generación de README.html con paleta Destello en cada respaldo

### README.md
- Corrección Opción A: todos los archivos deben subirse al proyecto, sin distinción entre operativos y documentación
- Tabla de versiones actualizada con fulgurador.md v1.5

### README.html — archivo nuevo
- Primera versión del README visual con paleta Destello del Fulgurador
- Fondo negro profundo, acento dorado intenso, tipografía Cinzel + EB Garamond
- Navegación sticky, árbol de archivos coloreado por tipo, tabla de versiones, pasos de instalación numerados

---

## SESIÓN 2026-03-15 — Compilación mayor

### fulgurador.md
**v1.3 → v1.4**
- Sistema renombrado a **Fulgurador Osmancito**; archivo renombrado
- Manifiesto del sistema agregado al inicio con subtítulo *Consume letras. Produce luz.*
- Definición de TALLER agregada al vocabulario — abierta, sin fijar número de talleres
- Nuevos términos en vocabulario: CORPUS, FICHA DEL CORPUS, NATURALEZA DEL CORPUS, IDENTIDAD VISUAL, MARCA
- Nueva sección IDENTIDAD VISUAL con marcas oficiales, tipografías y paletas de color
- Paleta Astillero Flota actualizada a verde marino
- Nueva sección FICHA DEL CORPUS con siete campos
- Nombres de archivo centralizados como única fuente de verdad
- Eliminados productos opcionales EPUB, PDF, DOCX

### protocolo-bodega.md
**v1.2 → v1.3**
- Sistema renombrado; marca actualizada

### protocolo-astillero.md
**v1.4 → v1.5**
- Sistema renombrado; marcas actualizadas

### astillero-header-flota.html
**v1.1 → v1.2**
- Paleta actualizada a verde marino

### system-prompt.md
**v1.1 → v2.0**
- Reescritura completa — reducido a instrucciones esenciales

### README.md — archivo nuevo
### CHANGELOG.md — archivo nuevo

---

## SESIÓN 2026-03-15 — Protocolo Bodega

### protocolo-bodega.md
**v1.1 → v1.2**
- SVG de Cata rediseñado: etiqueta de cata expandida como objeto principal
- Taxonomía de bebidas ampliada con cinco categorías y tres registros de calidad
- Criterios de asignación explicitados

---

## SESIÓN 2026-03-15 — Protocolo Astillero

### protocolo-astillero.md
**v1.3 → v1.4**
- Arquetipos de nave ampliados de 9 a 12
- Tres registros de calidad agregados a los doce arquetipos
- SVG modo Nave: ficha técnica de inspección naval
- Subtítulos descriptivos agregados a los diez estratos

---

## SESIÓN 2026-03-13 — Versión inicial

### fulgurador.md · protocolo-bodega.md · protocolo-astillero.md
- Versiones iniciales del sistema con dos talleres activos

### bodega-header.html · astillero-header-nave.html · astillero-header-flota.html
- Encabezados visuales animados — versiones iniciales

### system-prompt.md
- System prompt inicial unificado

---

*Fulgurar · Consume letras. Produce luz.*
