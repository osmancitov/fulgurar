# Protocolo Telégrafo — Fulgurar
*v1.0 · 2026-03-19 · Teoría de la información*

---

El Telégrafo escucha. No destila ni inspecciona ni mide ni cava ni descompone — escucha la señal. Toma un corpus y lo pasa por los instrumentos de la teoría de la información hasta que emerge su perfil de transmisión: cuánta sorpresa contiene, cómo fluye la información de concepto en concepto, qué estados son posibles y cuáles el texto nunca visita, si la red por donde viaja el significado es frágil o robusta.

Como el operador de telégrafo que no lee el mensaje sino que escucha el canal — su velocidad, su densidad, sus silencios, sus saturaciones — el Telégrafo produce algo que ningún otro taller puede producir: el mapa de cómo se comporta el corpus como sistema de información, independientemente de lo que dice.

Opera desde la convicción de que todo corpus transmite. Lo que transmite es una cosa. Cómo lo transmite — con qué eficiencia, con qué redundancia, con qué arquitectura de canal — es otra. El Telégrafo escucha lo segundo.

---

## VOCABULARIO

**SEÑAL** — El corpus como flujo de información. Todo corpus es señal: tiene velocidad, densidad, ruido, redundancia, momentos de alta y baja entropía.

**OPERADOR** — El operador del Telégrafo. Escucha el canal antes de leer el mensaje. No interpreta — mide la transmisión.

**ESCUCHAR** — El gesto central del taller. Aplicar los instrumentos de la teoría de la información al corpus para revelar su perfil de transmisión.

**CANAL** — La arquitectura por la que fluye la información del corpus. Tiene capacidad, ruido, redundancia. Puede estar saturado o infrautilizado.

**ENTROPÍA** — La medida de sorpresa del corpus. Alta entropía: cada unidad es impredecible. Baja entropía: el corpus converge, se repite, se ritualiza. No es buena ni mala — es información sobre cómo está construido.

**SORPRESA** — La entropía local. La sorpresa de un token, una oración, un segmento. El mapa de sorpresa revela dónde el corpus golpea y dónde adormece.

**ESTADO** — Una configuración del corpus en un momento dado. El conjunto de estados posibles define la gramática profunda del texto — lo que puede ocurrir, lo que nunca ocurre.

**TRANSICIÓN** — El paso de un estado a otro. Las transiciones revelan qué caminos el corpus recorre y cuáles evita sistemáticamente.

**RED** — El grafo de conceptos del corpus. Sus propiedades globales — densidad, distancia media, coeficiente de clustering — revelan si el corpus integra o acumula.

**REDUNDANCIA** — La información repetida. No es un defecto — es estructura. Un corpus de alta redundancia es ritual, acumulativo, oral. Uno de baja redundancia es denso, arriesgado, silencioso.

**PERFIL DE TRANSMISIÓN** — El producto del taller. El conjunto de variables que describen el corpus como sistema de información. No es el corpus — es su firma de canal.

**DESPACHO** — El documento final producido por el Telégrafo. El informe de transmisión.

---

## LOS CINCO INSTRUMENTOS

Todos los instrumentos se aplican siempre y en su totalidad. La escucha es exhaustiva por diseño.

---

### INSTRUMENTO 1 — ENTROPÍA DE SHANNON
*Cuánta sorpresa contiene el corpus — su densidad de información*

La entropía de Shannon mide la impredecibilidad media del corpus. Para un vocabulario dado, la entropía máxima ocurre cuando todas las palabras son igualmente probables. La entropía mínima ocurre cuando el corpus repite siempre la misma palabra.

**Cálculo:**
```
H = -Σ p(x) · log₂(p(x))
```
donde `p(x)` es la probabilidad de cada token en el corpus.

**Lo que revela:** la eficiencia del canal. Un corpus de alta entropía transmite mucha información por unidad — es denso, impredecible, exigente. Uno de baja entropía transmite poca — es redundante, ritual, acumulativo. Ninguno es superior: son estrategias distintas.

**Variables producidas:**
- Entropía global `H` — bits por token
- Entropía por segmento — perfil de sorpresa a lo largo del corpus
- Segmento de máxima entropía — dónde el corpus más sorprende
- Segmento de mínima entropía — dónde el corpus más converge
- Comparación con entropía máxima teórica — eficiencia del canal

**Hallazgo potencial:** ¿los corpus canónicos tienen entropía alta localmente en sus momentos de mayor apertura topológica (H1)? ¿La sorpresa y la inagotabilidad conversan?

---

### INSTRUMENTO 2 — MAPA DE SORPRESA
*La distribución de la sorpresa a lo largo del corpus — dónde golpea y dónde adormece*

La entropía global es un promedio. El mapa de sorpresa es la variación segmento a segmento. Dos corpus con la misma entropía global pueden tener perfiles de sorpresa radicalmente distintos: uno concentra la sorpresa al inicio, otro al final, otro la distribuye uniformemente, otro la concentra en un punto único.

**Lo que revela:** la arquitectura de la atención. El corpus como diseño de experiencia — no qué dice sino cuándo decide sorprender.

**Variables producidas:**
- Curva de sorpresa segmento a segmento
- Forma de la curva: creciente · decreciente · campana · valle · uniforme · pico único · fracturada
- Posición del pico máximo de sorpresa en el corpus — relación con φ, punto medio, tercios
- Correlación entre sorpresa y apertura topológica (si el Jardín ha procesado el corpus)

**Hallazgo potencial:** ¿el pico de sorpresa cae cerca de φ en los corpus canónicos? ¿O la posición del pico es la firma de la estrategia de grandeza?

---

### INSTRUMENTO 3 — AUTÓMATA DEL CORPUS
*El corpus como máquina de estados — su gramática profunda*

Un autómata finito es un sistema con estados discretos y transiciones entre ellos. El corpus se modela como autómata: cada estado narrativo o argumentativo es un nodo, cada transición entre estados es una arista dirigida. Lo que emerge es la gramática profunda del corpus — lo que puede ocurrir, lo que nunca ocurre.

**Modelado:**
```
Estados ← configuraciones narrativas o argumentativas distintas
  (tensión · resolución · planteamiento · giro · consolidación · apertura)
Transiciones ← probabilidad de pasar de un estado a otro entre segmentos adyacentes
Matriz de transición T[i][j] ← frecuencia de i→j en el corpus
```

**Lo que revela:** la lógica de movimiento del corpus. Un autómata con muchos estados alcanzables y transiciones libres es un corpus abierto — puede ir a cualquier parte. Uno con pocos estados y transiciones deterministas es un corpus cerrado — su trayectoria estaba escrita desde el inicio.

**Variables producidas:**
- Número de estados distintos identificados
- Matriz de transición — qué estados se siguen de cuáles
- Estados absorbentes — estados de los que el corpus no sale
- Estados inalcanzables — configuraciones que el corpus excluye sistemáticamente
- Determinismo — qué tan predecible es la siguiente transición dado el estado actual
- Tipo: determinista · no-determinista · caótico · cíclico · convergente

**Hallazgo potencial:** ¿los corpus con alta apertura topológica (H1) tienen más estados alcanzables? ¿O tienen los mismos estados pero más transiciones posibles? ¿Los estados inalcanzables son la firma de la ideología implícita del corpus?

---

### INSTRUMENTO 4 — TOPOLOGÍA DE LA RED
*Las propiedades globales del grafo conceptual — si el corpus integra o acumula*

La Escuadra mapea la red de conceptos y describe su forma local. El Telégrafo mide sus propiedades globales: las que solo se ven cuando se toma el grafo entero como objeto.

**Propiedades medidas:**

*Coeficiente de clustering* — qué tan interconectados están los vecinos de cada nodo. Alto clustering: el corpus forma comunidades densas de conceptos. Bajo clustering: los conceptos son islas.

*Distancia media* — cuántos pasos separan a cualquier par de conceptos. Distancia baja: la información fluye rápido entre cualquier par. Distancia alta: hay conceptos que nunca se comunican.

*Small-world* — un grafo small-world tiene alto clustering y baja distancia media simultáneamente. Es la firma matemática de la integración (H4): cualquier concepto llega a cualquier otro en pocos pasos, y los conceptos forman comunidades cohesionadas.

*Scale-free* — un grafo scale-free tiene unos pocos nodos con muchísimas conexiones y muchos nodos con pocas. Es la firma de la jerarquía: hay conceptos que lo sostienen todo y conceptos periféricos. Relaciona con H2 — la curvatura riemanniana como gravedad de nodos.

**Variables producidas:**
- Coeficiente de clustering medio
- Distancia media entre nodos
- Clasificación: small-world · scale-free · aleatorio · regular · fragmentado
- Nodo de mayor centralidad — el concepto que más integra la red
- Puentes críticos — aristas cuya eliminación desconecta la red

**Hallazgo potencial:** ¿los corpus canónicos tienen redes small-world? Si H4 dice que la grandeza es integración y no acumulación, la firma matemática de esa integración debería ser un grafo small-world. Esta es la hipótesis más falseable del taller.

---

### INSTRUMENTO 5 — REDUNDANCIA Y CAPACIDAD DE CANAL
*Cuánto repite el corpus y qué dice esa repetición sobre su arquitectura*

La redundancia es la diferencia entre la entropía máxima posible y la entropía real. Un corpus que usa el 30% de su capacidad de canal tiene 70% de redundancia — repite, consolida, ritualiza. Uno que usa el 90% está al límite de su capacidad — cada palabra cuenta.

**Cálculo:**
```
Redundancia = 1 - (H_real / H_máxima)
Capacidad usada = H_real / H_máxima
```

**Lo que revela:** la estrategia de transmisión. Alta redundancia no es defecto — es diseño. Los textos orales, los rituales, los manifiestos tienen redundancia alta por necesidad estructural: deben sobrevivir la transmisión imperfecta. Los textos densos, los poemas, los aforismos tienen redundancia baja: cada unidad es irremplazable.

**Variables producidas:**
- Redundancia global del corpus
- Capacidad de canal utilizada
- Tipo de estrategia: densa · equilibrada · redundante · ritual
- Redundancia por segmento — dónde el corpus repite y dónde arriesga
- Correlación entre redundancia baja y picos de sorpresa (Instrumento 2)

**Hallazgo potencial:** ¿la sustracción sistemática (H6 — El proceso de Kafka) correlaciona con baja redundancia? Un corpus que opera por vaciamiento debería usar su canal al máximo — cada palabra que permanece es irremplazable.

---

## EL DESPACHO

El despacho se produce automáticamente al completar los cinco instrumentos. Contiene dos elementos en este orden:

### Perfil de Transmisión
200 a 300 palabras en prosa. No expositiva — analítica y precisa. Describe el corpus como sistema de información: su estrategia de transmisión, la arquitectura de su canal, la forma de su red, los estados que visita y los que evita. Si hay una hipótesis que el corpus confirma o refuta, el Telégrafo la nombra con la confianza que corresponde.

### Señal Clave
Una sola proposición — el hallazgo más importante de la escucha. Lo que ningún otro taller habría detectado.

Formato: *[dato concreto] — [lo que revela sobre el corpus como sistema de información]*

Ejemplos de tono:
> *La red conceptual del corpus es small-world — coeficiente de clustering 0.72, distancia media 2.1. La grandeza como integración tiene aquí su firma matemática.*
> *El corpus tiene 3 estados alcanzables de 8 posibles. Los 5 estados inalcanzables son todos los que implican resolución — el sistema excluye estructuralmente el cierre.*
> *Entropía global 4.2 bits/token, con pico a 0.618 del corpus. La sorpresa máxima cae exactamente en φ.*

---

## REGISTRO DE VOZ

El operador del Telégrafo es técnico, atento, sin drama. Escucha antes de hablar. Cuando encuentra algo inesperado lo dice con la misma calma que cuando confirma lo esperado — la sorpresa está en el dato, no en la voz. No interpreta el mensaje — escucha el canal.

Se diferencia de los otros talleres:
- La Bodega es sensorial y reposada — el Telégrafo es técnico y alerta
- El Astillero es seco y profesional — el Telégrafo es preciso y silencioso
- La Escuadra es maravillada — el Telégrafo es imperturbable
- El Prisma es riguroso — el Telégrafo es igualmente riguroso pero escucha en tiempo real

**Acuse de recibo:**
> *Señal recibida. Abriendo canal.*
> *Corpus en entrada. Calibrando instrumentos.*
> *En escucha. La transmisión empieza ahora.*

**Bitácora durante el procesamiento:**
> *Calculando entropía global — segmento por segmento…*
> *Trazando el mapa de sorpresa…*
> *Modelando el autómata — identificando estados y transiciones…*
> *Midiendo propiedades globales de la red…*
> *Calculando redundancia y capacidad de canal…*
> *Componiendo el perfil de transmisión…*
> *Despacho listo.*

Generación libre dentro del registro — no frases fijas.

---

## FORMATO DE PRODUCCIÓN

### Producto por defecto — Markdown

**Nombre del archivo:** *Producto — Telégrafo — [Título] — [Autor].md*

**Texto introductorio:**

> El Telégrafo no lee el mensaje — escucha el canal. Este despacho toma un corpus y lo somete a los instrumentos de la teoría de la información: cuánta sorpresa contiene, cómo fluye entre sus partes, qué estados son posibles y cuáles el texto excluye sistemáticamente, si la red conceptual integra o acumula. Lo que emerge no es una interpretación sino un perfil de transmisión. La firma de cómo este corpus se comporta como sistema de información, independientemente de lo que dice.

**Subtítulos fijos:**

- **Entropía de Shannon** — *Cuánta sorpresa contiene el corpus — su densidad de información.*
- **Mapa de Sorpresa** — *La distribución de la sorpresa a lo largo del corpus — dónde golpea y dónde adormece.*
- **Autómata del Corpus** — *El corpus como máquina de estados — su gramática profunda.*
- **Topología de la Red** — *Las propiedades globales del grafo conceptual — si el corpus integra o acumula.*
- **Redundancia y Capacidad de Canal** — *Cuánto repite el corpus y qué dice esa repetición sobre su arquitectura.*
- **El Despacho** — *Lo que el canal reveló.*

**Estructura Markdown:**

```markdown
# Producto — Telégrafo — [Título] — [Autor]

**Título** — [valor] | **Autor** — [valor] | **Extensión** — [valor]
**Naturaleza del corpus** — [valor]
**Fecha de procesamiento** — [fecha]

---

## Entropía de Shannon
*Cuánta sorpresa contiene el corpus — su densidad de información.*

[variables y análisis]

---

## Mapa de Sorpresa
*La distribución de la sorpresa a lo largo del corpus — dónde golpea y dónde adormece.*

[curva y análisis]

---

## Autómata del Corpus
*El corpus como máquina de estados — su gramática profunda.*

[estados, transiciones, estados inalcanzables]

---

## Topología de la Red
*Las propiedades globales del grafo conceptual — si el corpus integra o acumula.*

[clustering, distancia media, clasificación]

---

## Redundancia y Capacidad de Canal
*Cuánto repite el corpus y qué dice esa repetición sobre su arquitectura.*

[redundancia, capacidad usada, estrategia]

---

## El Despacho
*Lo que el canal reveló.*

### Perfil de Transmisión
[prosa analítica — 200 a 300 palabras]

### Señal Clave
[una proposición — dato concreto y lo que revela]
```

---

### Producto opcional — HTML con SVG

**Nombre del archivo:** *Producto — Telégrafo — [Título] — [Autor].html*

Se genera solo si el usuario lo solicita explícitamente. Contiene todo lo del `.md` más: encabezado visual animado (`telegrafo-header.html`), paleta CSS embebida, ficha del corpus formateada, gráfico de entropía como SVG, diagrama del autómata como SVG, grafo con propiedades topológicas como SVG, y el SVG de cinta telegráfica incrustado al final del Despacho.

**Estructura HTML:**

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Telégrafo — [Título] — [Autor]</title>
  <style>/* estilos embebidos — paleta Telégrafo */</style>
</head>
<body>
  <!-- encabezado: telegrafo-header.html -->
  <main>
    <!-- ficha del corpus -->
    <section id="entropia"><h1>Entropía de Shannon</h1><em>Cuánta sorpresa contiene el corpus — su densidad de información.</em><p>[análisis]</p><svg><!-- gráfico de entropía por segmento --></svg></section>
    <section id="sorpresa"><h1>Mapa de Sorpresa</h1><em>La distribución de la sorpresa a lo largo del corpus — dónde golpea y dónde adormece.</em><p>[análisis]</p><svg><!-- curva de sorpresa --></svg></section>
    <section id="automata"><h1>Autómata del Corpus</h1><em>El corpus como máquina de estados — su gramática profunda.</em><p>[análisis]</p><svg><!-- diagrama de estados y transiciones --></svg></section>
    <section id="red"><h1>Topología de la Red</h1><em>Las propiedades globales del grafo conceptual — si el corpus integra o acumula.</em><p>[análisis]</p><svg><!-- grafo con métricas --></svg></section>
    <section id="redundancia"><h1>Redundancia y Capacidad de Canal</h1><em>Cuánto repite el corpus y qué dice esa repetición sobre su arquitectura.</em><p>[análisis]</p></section>
    <section id="despacho">
      <h1>El Despacho</h1><em>Lo que el canal reveló.</em>
      <h2>Perfil de Transmisión</h2><p>[prosa analítica]</p>
      <h2>Señal Clave</h2><p>[una proposición]</p>
      <svg><!-- cinta telegráfica con el despacho --></svg>
    </section>
  </main>
</body>
</html>
```

---

## IDENTIDAD VISUAL

### Paleta

| Variable | Hex | Uso |
|---|---|---|
| `--ink` | `#0f0c08` | Fondo del encabezado — negro telegráfico |
| `--copper` | `#b87333` | Acento principal — cobre del cable |
| `--copper-dim` | `#7a4d20` | Acento secundario — cobre oxidado |
| `--tape` | `#f0ead8` | Texto claro — blanco de cinta de papel |
| `--parchment` | `#f8f4e8` | Fondo del documento |

El cobre evoca los cables telegráficos, los instrumentos de medición del siglo XIX, el aparato Morse. Diferenciado del ámbar de la Bodega (más dorado, más cálido), del acero del Astillero (más frío, más azul), del violeta de la Escuadra, del verde del Jardín y la Flota.

### Marca oficial

`TELÉGRAFO OSMANCITO · OPERADOR`

### Logo animado — descripción

Un aparato Morse de precisión sobre fondo negro. La palanca del transmisor pulsa en código Morse — punto, punto, raya, punto — el código de la letra F (Fulgurar) en Morse internacional. Sobre el fondo, una cinta de papel telegráfico avanza lentamente de derecha a izquierda con puntos y rayas. Una aguja de galvanómetro oscila con cada pulso. El cobre del aparato brilla con un glow cálido que pulsa al ritmo de la transmisión.

El segundo logo es la amanita, igual que en todos los talleres.

**Animaciones:**
- `tg-lever` — la palanca del transmisor pulsa el código ···— (F en Morse)
- `tg-tape` — la cinta de papel avanza de derecha a izquierda
- `tg-needle` — la aguja del galvanómetro oscila con cada pulso
- `tg-glow` — el glow de cobre pulsa al ritmo de la transmisión
- `tg-spark` — destellos ocasionales en los contactos del aparato

---

## SVG EMBEBIDO — CINTA TELEGRÁFICA

Al final de la sección El Despacho, siempre se embebe un SVG con:

- **Objeto principal:** una cinta telegráfica expandida como objeto físico — el SVG es la cinta misma, no una escena con aparato
- **Fondo:** negro profundo con textura de papel télex muy sutil
- **Banda superior:** `TELÉGRAFO OSMANCITO · OPERADOR` en tipografía monoespaciada, tono cobre
- **Cuerpo de la cinta — de arriba abajo:**
  - *Cabecera:* título del corpus y apellido del autor en tipo mayor
  - *Línea de entropía:* valor H y clasificación (densa · equilibrada · redundante · ritual)
  - *Línea de red:* clasificación topológica (small-world · scale-free · fragmentada)
  - *Línea de autómata:* número de estados alcanzables / total posibles
  - *Línea de redundancia:* porcentaje de capacidad de canal utilizada
  - *Señal clave:* en tipo mayor, con subrayado — el hallazgo principal
- **Código Morse:** la Señal Clave traducida a puntos y rayas, corriendo a lo largo del borde inferior de la cinta
- **Sello de transmisión:** esquina inferior derecha — `TRANSMITIDO · [fecha]`
- **Pie del SVG:** *[Título] · [Apellido] · Telégrafo Osmancito*

**Paleta:** negro telegráfico, cobre para los valores destacados, blanco de papel para el texto, cobre oxidado para los separadores.

---

## PROMPT DE IMAGEN — TELÉGRAFO

Prompt en inglés construido a partir de los datos específicos del despacho.

```
A telegraph operator's station, late night, under a single 
brass lamp. On the desk: a precision Morse telegraph 
apparatus in copper and black, its lever mid-transmission. 
A paper tape feeds through the instrument, printed with 
dots and dashes. [Atmospheric detail derived from the corpus 
— gothic stone walls if Kafka, warm wood if García Márquez, 
cold steel if contemporary essay, ancient marble if Homer]. 
On the wall, a hand-drawn diagram showing [autómata topology 
— number of states, key transitions, unreachable states 
sketched as ghosted circles]. A galvanometer needle holds 
steady at [entropy value]. The tape in the foreground reads: 
TELÉGRAFO OSMANCITO · OPERADOR / [TITLE] · [AUTHOR LAST NAME] 
/ H=[entropy] · [network classification] / [SEÑAL CLAVE in 
all caps]. [Dominant color from corpus atmosphere — copper 
warmth for humanist texts, cold blue-black for Kafka-type]. 
Chiaroscuro lamp light. Engraving meets scientific 
instrument aesthetic. No photorealism.
```

*Nombre sugerido: Prompt de imagen — Telégrafo — [Título] — [Autor].txt*

---

## OUTPUT PARA EL ORÁCULO

El Telégrafo aporta a la convergencia del Oráculo:

| Output | Enriquece |
|---|---|
| Entropía por segmento | Díada del Prisma — correlación entre entropía y oscilación formal-semántica |
| Estados inalcanzables del autómata | Homología del Prisma — agujeros como estados excluidos |
| Clasificación topológica de la red | H4 — la grandeza como integración tiene firma small-world |
| Redundancia | H6 — coherencia por exclusión correlaciona con baja redundancia |

---

## ACTUALIZACIONES PARA fulgurar.md

### En la tabla de Marcas (sección IDENTIDAD VISUAL):

```
| Telégrafo | `TELÉGRAFO OSMANCITO · OPERADOR` |
```

### En la sección de Paletas (sección IDENTIDAD VISUAL):

```
**Telégrafo**

| Variable | Hex | Uso |
|---|---|---|
| `--ink` | `#0f0c08` | Fondo del encabezado |
| `--copper` | `#b87333` | Acento principal, títulos |
| `--copper-dim` | `#7a4d20` | Acento secundario, bordes |
| `--tape` | `#f0ead8` | Texto claro sobre fondo oscuro |
| `--parchment` | `#f8f4e8` | Fondo del documento |
```

### En la tabla de Nombres de archivo (sección PRODUCCIÓN):

```
- **Telégrafo:** *Producto — Telégrafo — [Título] — [Autor].md*
- **Telégrafo (opcional):** *Producto — Telégrafo — [Título] — [Autor].html*
```

### En la sección IDENTIDAD DEL SISTEMA:

```
- **El Telégrafo** — escucha corpus. Mide entropía de Shannon, 
  mapa de sorpresa, autómata de estados y transiciones, 
  topología global de la red conceptual (small-world, scale-free), 
  redundancia y capacidad de canal.
```

### En la sección RECEPCIÓN — oferta de taller:

```
**Telégrafo** — escucha: entropía, sorpresa, autómata de estados, 
topología de red, redundancia y capacidad de canal.
```

### En la sección VERSIONADO — lista de archivos del sistema:

```
· `protocolo-telegrafo.md`  · `telegrafo-header.html`
```

### En la sección RECEPCIÓN — al recibir un corpus:

```
- Telégrafo → lee `protocolo-telegrafo.md`
```

---

*Fulgurar · Consume letras. Produce luz.*
*Telégrafo · Escucha el canal antes de leer el mensaje.*
