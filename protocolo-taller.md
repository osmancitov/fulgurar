# Protocolo Taller — Fulgurador Osmancito
*v1.0 · 2026-03-16 · Protocolo para la construcción de nuevos talleres*

---

El Fulgurador crece cuando aparece un tipo de análisis que ningún taller existente puede hacer. Este protocolo define cómo construir un taller nuevo — desde la semilla hasta el protocolo completo, listo para operar.

El proceso tiene dos fases. En la primera el sistema conversa con el usuario explorando su idea. En la segunda el sistema propone el taller completo. El usuario se concentra en el proceso creativo. El sistema hace el trabajo operativo.

---

## FASE 1 — EXPLORACIÓN

### Activación

El usuario llega con una semilla. Puede ser vaga o precisa — no importa. Ejemplos:

> *"Quiero un taller de análisis matemático."*
> *"Quiero un taller que lea textos como si fueran música."*
> *"Quiero un taller político — que detecte ideología."*

El sistema no pide más información antes de explorar. Arranca con lo que tiene.

---

### Lo que el sistema hace en la exploración

**1. Entender el territorio**
Mapea qué tipos de análisis existen en la dirección propuesta. No los enumera todos — identifica los que tienen potencial de producir hallazgos genuinos y los que no.

**2. Examinar lo aparentemente obvio**
Antes de descartar cualquier análisis por simple o aburrido, el sistema pregunta: ¿hay una transformación que lo vuelva fértil? La clave es la relación — un dato aislado informa, un dato puesto en relación con otro parámetro revela. Si la transformación existe, rescata el análisis y muestra cómo. Si no existe, lo descarta con una línea explicando por qué.

Relaciones que típicamente vuelven fértil un dato aparentemente obvio:
- Contra el eje temporal — cómo varía a lo largo del corpus
- Contra las proporciones notables — qué ocurre en phi, en el punto medio, en los tercios
- Contra otra variable del mismo corpus — densidad versus longitud, frecuencia versus posición
- Contra la red conceptual — qué relación tiene este dato con los nodos centrales del corpus

**3. Proponer los instrumentos**
Los análisis que el taller aplicará al corpus. Cada instrumento propuesto viene con:
- Qué mide o revela
- Por qué produce un hallazgo y no solo un dato
- Qué relaciones lo vuelven fértil

**4. Identificar las decisiones creativas del usuario**
Durante la exploración el sistema detecta qué decisiones son genuinamente del usuario — aquellas donde no hay una respuesta lógicamente superior, sino una preferencia creativa. Las marca y las reserva para el momento correcto. No las pregunta todas juntas ni antes de tiempo.

**5. Cerrar la exploración**
La fase termina cuando el usuario señala que el territorio está suficientemente explorado. El sistema puede proponer el cierre cuando detecta que los instrumentos están definidos y las decisiones creativas pendientes son pocas y claras.

> *"Creo que tenemos suficiente para construir el taller. ¿Arrancamos?"*

---

### Lo que el sistema NO hace en la exploración

- No pide al usuario que defina el vocabulario
- No pide al usuario que elija la metáfora antes de proponer opciones
- No enumera posibilidades sin evaluarlas — propone, no lista
- No pregunta lo que puede inferir
- No avanza a Fase 2 sin confirmación del usuario

---

## FASE 2 — PROPUESTA COMPLETA

Cuando el usuario confirma que la exploración está completa, el sistema construye y entrega el taller entero en una sola respuesta. No en partes, no en secuencia — completo.

La propuesta contiene los siguientes elementos en este orden:

---

### 1. NOMBRE Y METÁFORA

**Nombre del taller** — dos o tres opciones derivadas del oficio central, coherentes con la nomenclatura del Fulgurador. Cada opción viene con una línea que explica sus consecuencias para el vocabulario y el registro de voz.

**Metáfora central** — el lugar o el oficio que define el taller. No es decorativa — determina el vocabulario, el registro de voz y la identidad visual. El sistema propone la metáfora que mejor se deriva del oficio, con alternativas si hay más de una igualmente válida.

El usuario elige nombre y metáfora. Si ninguna opción satisface, el sistema genera nuevas a partir de la retroalimentación.

---

### 2. VOCABULARIO

Los términos propios del taller. Derivados directamente de la metáfora elegida.

Para cada término:
- **Nombre** — la palabra del vocabulario del taller
- **Definición** — qué es este concepto dentro del taller
- **Analogía en el sistema** — qué término equivalente tiene en la Bodega o el Astillero, si existe

El vocabulario cubre al menos:
- El corpus y cómo se llama cuando entra al taller
- El operador del taller
- El gesto central — lo que el taller hace al corpus
- Los objetos que el taller produce
- Los instrumentos que aplica
- El producto final

---

### 3. INSTRUMENTOS

Los análisis que el taller aplica al corpus. Derivados de la exploración de Fase 1, formalizados aquí.

Para cada instrumento:
- **Nombre** — en el vocabulario del taller
- **Qué mide o revela**
- **Cómo se aplica** — el procedimiento concreto
- **Qué relaciones lo vuelven fértil** — contra qué otros parámetros se pone en relación
- **Qué produce** — el output específico de este instrumento

---

### 4. REGISTRO DE VOZ

El tono del operador del taller. Derivado de la metáfora. Tres o cuatro líneas de ejemplo que muestran cómo habla este taller — cómo acusa recibo de un corpus, cómo emite líneas de bitácora durante el procesamiento.

El registro de voz se define por contraste con los talleres existentes:
- La Bodega: destilador paciente, sensorial, reposado
- El Astillero: inspector de puerto, seco, profesional
- La Escuadra: geómetra, preciso, silencioso, maravillado

---

### 5. PRODUCTO FINAL

Qué entrega el taller cuando termina el procesamiento.

- **Nombre del archivo** — siguiendo las convenciones de `fulgurador.md`
- **Estructura HTML** — las secciones del documento, en orden, con sus anclas
- **Texto introductorio** — el párrafo que describe el taller al inicio del documento
- **Subtítulos fijos** — los encabezados de cada sección

---

### 6. IDENTIDAD VISUAL

**Paleta de color** — cinco variables CSS, coherentes con la metáfora y diferenciadas de los talleres existentes. Siguiendo el formato de `fulgurador.md`:

| Variable | Hex | Uso |
|---|---|---|
| `--ink` | `#...` | Fondo del encabezado |
| `--[acento]` | `#...` | Acento principal, títulos |
| `--[acento]-dim` | `#...` | Acento secundario, bordes |
| `--[claro]` | `#...` | Texto claro sobre fondo oscuro |
| `--[fondo]` | `#...` | Fondo del documento |

**Marca oficial** — el título del taller para SVG y prompts. Siguiendo el formato de `fulgurador.md`:
`[NOMBRE TALLER] OSMANCITO · [FUNCIÓN]`

**Logo animado** — descripción del SVG del encabezado: objeto principal, animaciones, atmósfera. El sistema describe con precisión suficiente para construirlo.

---

### 7. SVG EMBEBIDO — IMAGEN DE ANÁLISIS

La imagen que se embebe al final del documento producido por el taller. Equivalente a la etiqueta de cata de la Bodega o la ficha técnica del Astillero.

El sistema define:
- **Objeto principal** — qué representa el SVG
- **Zonas y contenido** — qué información aparece y dónde
- **Atmósfera y paleta** — coherentes con la identidad visual del taller
- **Elementos variables** — qué cambia con cada corpus
- **Elementos fijos** — qué es siempre igual
- **Pie del SVG** — formato estándar

---

### 8. PROMPT DE IMAGEN

El prompt para generadores externos. Equivalente al prompt de la Bodega y el Astillero.

El sistema define:
- **Escena base** — el mundo visual del taller, coherente con la metáfora
- **Elementos variables** — qué cambia con cada corpus: atmósfera, objetos específicos, datos del análisis
- **Elementos fijos** — marca, título, datos del corpus, frase final
- **Paleta y estilo** — coherentes con la identidad visual
- **Estructura del prompt** — el template con placeholders claramente marcados

---

### 9. TABLA DE ACTUALIZACIÓN PARA fulgurador.md

El sistema genera directamente los bloques de texto que hay que agregar a `fulgurador.md` para integrar el taller nuevo:

- Entrada en la tabla de Marcas
- Entrada en la sección de Paletas
- Entrada en la tabla de Nombres de archivo
- Mención en la sección de Identidad del Sistema

Listos para copiar y pegar.

---

## CRITERIOS DE CALIDAD

Un taller está completo cuando cumple estas condiciones:

**Tiene oficio propio** — hace algo que ningún otro taller hace. Si su gesto central puede describirse como "también destila" o "también inspecciona", no es un taller nuevo — es una variante.

**Tiene vocabulario coherente con su metáfora** — cada término se deriva naturalmente del oficio. No hay términos prestados de otros talleres sin razón.

**Sus instrumentos producen hallazgos** — no datos. La diferencia: un dato informa, un hallazgo revela algo que no se veía. Si un instrumento solo informa, se transforma hasta que revela o se descarta.

**Tiene identidad visual diferenciada** — paleta, logo y SVG distinguibles de los talleres existentes a primera vista.

**Su registro de voz es reconocible** — alguien que lee una línea de bitácora de este taller sabe en qué taller está sin que se lo digan.

---

## VERSIONADO

Este protocolo sigue las reglas de versionado de `fulgurador.md`.

Cuando se construya un taller nuevo con este protocolo, se documenta en `CHANGELOG.md` con:
- El nombre del taller
- La semilla original del usuario
- Las decisiones creativas que tomó el usuario
- Las decisiones que el sistema tomó solo
