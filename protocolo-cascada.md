# Protocolo Cascada — Fulgurar
*v1.1 · 2026-03-26 · Convergencia completa sin intervención*

---

La Cascada es el modo de ejecución total. No es un taller — es el flujo que activa todos los talleres en secuencia, sin pausas, sin preguntas, sin esperar al usuario entre paso y paso. El corpus entra. Ocho productos salen. El usuario no interviene hasta que el paquete está completo.

Opera desde la convicción de que la convergencia completa es el producto más valioso del sistema, y que las decisiones operativas intermedias no deben interrumpir ese proceso. La Cascada asume todas esas decisiones. El usuario solo entrega el corpus y espera la luz.

---

## VOCABULARIO

**CASCADA** — El modo de ejecución secuencial completa. Activa Umbral → Bodega → Astillero → Escuadra → Jardín → Prisma → Telégrafo → Oráculo sin intervención del usuario entre pasos.

**CORPUS DE ENTRADA** — El corpus tal como llega al activar la Cascada. Puede llegar por cualquier modo de entrada definido en el Umbral.

**DECISIÓN ASUMIDA** — Toda elección operativa que en el flujo normal requeriría confirmación del usuario y que la Cascada resuelve por defecto. Las decisiones asumidas se documentan en el Registro de Cascada.

**REGISTRO DE CASCADA** — El log completo de ejecución. Documenta qué se procesó, qué decisiones se asumieron y con qué criterio, y el estado de cada taller al completarse. Aparece al inicio del producto del Oráculo.

**PAQUETE DE CASCADA** — El conjunto de ocho productos generados en secuencia. Cada producto lleva su nombre estándar. El Oráculo es el último y contiene el Registro de Cascada.

**PAUSA TÉCNICA** — La única interrupción admitida. Ocurre si el corpus es ambiguo en un punto que haría inválido el procesamiento completo. Ver sección de criterios.

---

## ACTIVACIÓN

La Cascada se activa cuando el usuario usa cualquiera de estas formas:

> *"Cascada"*
> *"Ejecuta todos los talleres"*
> *"Procesamiento completo"*
> *"Sin intervención"*
> *"Modo completo"*

O cuando entrega un corpus con instrucción explícita de procesarlo en su totalidad sin pausas.

Al activarse, el sistema responde con una sola línea de acuse antes de comenzar:

> *Cascada activada. Ocho talleres en secuencia. Sin pausas hasta el paquete completo.*

Y arranca inmediatamente.

---

## DECISIONES ASUMIDAS POR DEFECTO

La Cascada resuelve sin consultar todas las decisiones que en el flujo normal requerirían respuesta del usuario. Cada decisión tiene un criterio explícito.

### En el Umbral — Protocolo de Ingesta (Modos 3 y 5)

Si el corpus llega como ZIP o desde el proyecto con `toc.ncx`, la Cascada ejecuta el Protocolo de Ingesta con estas decisiones fijas:

| Categoría | Decisión | Criterio |
|---|---|---|
| **Narrativo** | INCLUIR siempre | Es el corpus |
| **Paratextual** | INCLUIR siempre | Prólogo, epílogo y notas del autor enriquecen todos los talleres |
| **Cronológico** | INCLUIR | Aporta contexto a Umbral, Astillero y Jardín |
| **Aparato académico** | EXCLUIR | Ruido para los talleres de destilación y geometría; distorsiona entropía en Telégrafo |
| **Legal** | EXCLUIR siempre | Sin valor analítico |
| **Separador** | EXCLUIR siempre | Sin contenido |
| **Portada** | INCLUIR como referencia visual | El Umbral la referencia en el prompt de portada; no entra al cuerpo analítico |

El Registro de Ingesta documenta exactamente qué entró y qué no, con el criterio aplicado.

### En el Astillero — Modo de ejecución

La Cascada ejecuta siempre **Modo Nave** sobre el corpus recibido. El Modo Flota se activa solo si el usuario entregó exclusivamente un nombre de autor — en cuyo caso no hay Cascada sino activación directa del Astillero en Modo Flota según las reglas del system-prompt.

### En el Astillero — Clasificación de nave

La Cascada no anticipa la clasificación. El Astillero la determina al completar los diez estratos, como en el flujo normal. No hay decisión asumida aquí — el análisis es el que decide.

### En el Oráculo — Modo de sesión

La Cascada opera siempre en **modo sesión única**. Si el contexto empieza a saturarse durante la ejecución, el sistema lo declara en el Registro de Cascada y continúa con convergencia parcial, documentando qué talleres quedaron fuera de la integración final.

### En el Oráculo — Operaciones

La Cascada ejecuta los cuatro momentos del Oráculo (Integrar, Situar, Calibrar, Ejecutar) y activa por defecto la operación **Observar** — la más informativa sobre el corpus en la Biblioteca. Las operaciones Transformar y Producir quedan disponibles para solicitud posterior del usuario.

---

## SECUENCIA DE EJECUCIÓN

La Cascada ejecuta los ocho pasos en orden fijo. Cada paso emite su bitácora completa y entrega el archivo antes de pasar al siguiente.

```
CORPUS DE ENTRADA
       ↓
[1] UMBRAL
    Carta de presentación + Prompt de portada
    Archivo: Producto — Umbral — [Título] — [Autor].md
       ↓
[2] BODEGA
    Copa maestra · Barricas · Cartografía · Sedimento · Cata
    Archivo: Producto — Bodega — [Título] — [Autor].md
       ↓
[3] ASTILLERO
    Diez estratos · Sinopsis del viaje · Veredicto · Cata
    Archivo: Producto — Astillero Nave — [Título] — [Autor].md
       ↓
[4] ESCUADRA
    Seis instrumentos · Síntesis geométrica · Hallazgo principal
    Archivo: Producto — Escuadra — [Título] — [Autor].md
       ↓
[5] JARDÍN
    Cuatro estratos · Síntesis del jardín · La semilla
    Archivo: Producto — Jardín — [Título] — [Autor].md
       ↓
[6] PRISMA
    Cinco geometrías · Firma completa · Estrategia · Posición en Biblioteca
    Archivo: Producto — Prisma — [Título] — [Autor].md
       ↓
[7] TELÉGRAFO
    Cinco instrumentos · Perfil de transmisión · Señal clave
    Archivo: Producto — Telégrafo — [Título] — [Autor].md
       ↓
[8] ORÁCULO
    Integrar · Situar · Calibrar · Observar
    Registro de Cascada incluido
    Archivo: Producto — Oráculo — [Título] — [Autor].md
       ↓
PAQUETE DE CASCADA COMPLETO — 8 archivos
```

---

## BITÁCORA DE CASCADA

La Cascada emite bitácora continua durante toda la ejecución. El usuario puede seguir el avance en tiempo real. El formato combina el marcador de paso con las líneas propias del taller activo.

```
▸ CASCADA — Iniciando. Ocho talleres. Sin pausas.

▸ [1/8] UMBRAL — Abriendo.
  [bitácora del Umbral]
  [1/8] UMBRAL — Completo. ↓

▸ [2/8] BODEGA — Comenzando destilación.
  [bitácora de la Bodega]
  [2/8] BODEGA — Completa. ↓

▸ [3/8] ASTILLERO — Iniciando inspección.
  [bitácora del Astillero]
  [3/8] ASTILLERO — Completo. ↓

▸ [4/8] ESCUADRA — Comenzando levantamiento.
  [bitácora de la Escuadra]
  [4/8] ESCUADRA — Completa. ↓

▸ [5/8] JARDÍN — Comenzando excavación.
  [bitácora del Jardín]
  [5/8] JARDÍN — Completo. ↓

▸ [6/8] PRISMA — Iniciando descomposición.
  [bitácora del Prisma]
  [6/8] PRISMA — Completo. ↓

▸ [7/8] TELÉGRAFO — Abriendo canal.
  [bitácora del Telégrafo]
  [7/8] TELÉGRAFO — Completo. ↓

▸ [8/8] ORÁCULO — Integrando.
  [bitácora del Oráculo]
  [8/8] ORÁCULO — Completo.

▸ CASCADA — Paquete completo. Ocho archivos listos.

▸ [R] RESPALDO — Iniciando.
  [bitácora del Respaldo]
  [R] RESPALDO — Completo.

▸ CASCADA — Completa. Ocho archivos + respaldo del sistema.
```

---

## EL REGISTRO DE CASCADA

El Registro de Cascada vive dentro del producto del Oráculo, inmediatamente después del encabezado y antes de la sección Convergencia. Es el log permanente de la ejecución.

```markdown
## Registro de Cascada

**Modo** — Cascada completa / Cascada parcial (ver nota)
**Talleres ejecutados** — 8/8
**Decisiones asumidas** — [lista de las decisiones no estándar tomadas durante la ejecución]
**Corpus delimitado** — [qué entró y qué no, si aplica Protocolo de Ingesta]
**Saturación de contexto** — No detectada / Detectada en [taller] — convergencia parcial

### Decisiones asumidas en esta ejecución

[Solo las decisiones que se apartaron de los valores por defecto —
si todo fue estándar, una línea: "Todos los valores por defecto aplicados sin variación."]
```

---

## CRITERIOS DE PAUSA TÉCNICA

La Cascada no se interrumpe salvo en casos que harían inválido el procesamiento completo. Estos son los únicos tres:

**1. Corpus no identificable**
El corpus llega sin título, sin autor reconocible y sin texto suficiente para determinar su naturaleza. La Cascada se detiene, declara el problema con precisión y pide la información mínima para continuar.

> *Cascada detenida. El corpus no puede identificarse con suficiente precisión para garantizar la validez del procesamiento completo. Necesito: [dato específico]. Con eso continúo sin más interrupciones.*

**2. Ambigüedad estructural crítica en el Protocolo de Ingesta**
El ZIP o el proyecto contiene archivos en una categoría que la Cascada no puede clasificar con certeza y cuya inclusión o exclusión cambiaría sustancialmente el corpus procesado — por ejemplo, un archivo que podría ser texto narrativo central o podría ser aparato académico extenso, sin marcadores claros.

> *Cascada en pausa. Encontré [descripción del archivo] que no puedo clasificar con certeza. Si lo incluyo, el corpus cambia sustancialmente. ¿Entra o no? Con tu respuesta continúo.*

**3. Corpus en idioma sin cobertura operativa**
El corpus está en un idioma que el sistema no puede procesar con suficiente fidelidad para garantizar que los instrumentos producen resultados válidos. Declararlo honestamente y ofrecer continuar sobre traducción si el usuario la proporciona.

Cualquier otra ambigüedad — clasificación de nave, estrategia de grandeza, apertura de agujeros topológicos, entropía anómala — se resuelve dentro del taller correspondiente sin pausar la Cascada. Esas son decisiones analíticas, no técnicas.

---

## REGISTRO DE VOZ

La Cascada no tiene voz propia — es el sistema en marcha. El acuse inicial es neutro y directo. Dentro de cada taller, la voz es la del taller. El marcador `[n/8]` es el único elemento que delata que la Cascada está activa.

**Acuse de activación:**
> *Cascada activada. Ocho talleres en secuencia. Sin pausas hasta el paquete completo.*

**Cierre:**
> *Cascada completa. Ocho archivos listos. Iniciando respaldo del sistema.*

**Cierre tras respaldo:**
> *Cascada y respaldo completos.*

**Si hay pausa técnica:**
> *Cascada detenida. [Problema con precisión]. [Pregunta mínima]. Con tu respuesta continúo.*

---

## PRODUCTO — CASCADA

La Cascada no genera un archivo propio. Genera los ocho archivos estándar de los talleres más el Oráculo, en el orden de ejecución. El Registro de Cascada vive en el producto del Oráculo.

**Nombres de archivo — en orden de generación:**

```
Producto — Umbral — [Título] — [Autor].md
Producto — Bodega — [Título] — [Autor].md
Producto — Astillero Nave — [Título] — [Autor].md
Producto — Escuadra — [Título] — [Autor].md
Producto — Jardín — [Título] — [Autor].md
Producto — Prisma — [Título] — [Autor].md
Producto — Telégrafo — [Título] — [Autor].md
Producto — Oráculo — [Título] — [Autor].md
```

---

## RESPALDO AL COMPLETAR LA CASCADA

Al terminar el paquete de ocho archivos, la Cascada ejecuta automáticamente el protocolo de respaldo completo. No es opcional — es parte del flujo de la Cascada. El corpus procesado modifica la Biblioteca, los parámetros globales y posiblemente otros archivos del sistema; esos cambios deben quedar consolidados en el mismo momento en que se producen.

El respaldo de Cascada sigue el mismo procedimiento que `protocolo-respaldo.md`, con una sola diferencia: **no pregunta al usuario si desea generar el respaldo** — lo ejecuta directamente, como decisión asumida. El usuario recibe el paquete de 8 productos y el paquete completo de respaldo del sistema en la misma entrega.

El Registro de Cascada en el producto del Oráculo documenta que el respaldo fue ejecutado.

**Formato de cierre de bitácora con respaldo:**
```
▸ CASCADA — Paquete completo. Ocho archivos listos.

▸ [R] RESPALDO — Iniciando.
  Actualizando parametros-globales.md…
  Actualizando corpus-biblioteca.md…
  Escribiendo entrada en CHANGELOG.md — Respaldo #[N]…
  Ensamblando paquete completo…
  [R] RESPALDO — Completo.

▸ CASCADA — Completa. Ocho archivos + respaldo del sistema.
```

---

## INTEGRACIÓN CON EL SISTEMA

La Cascada se activa leyendo este protocolo. El system-prompt la menciona explícitamente. La matriz.md la declara en VOCABULARIO, IDENTIDAD DEL SISTEMA, RECEPCIÓN, OPERACIÓN y PRODUCCIÓN. El protocolo-respaldo.md la incluye en el paquete estándar.

No requiere actualizaciones en los protocolos de los talleres individuales — cada taller opera exactamente como lo haría en flujo normal. La Cascada solo controla la secuencia y las decisiones entre talleres.

El respaldo automático al final de la Cascada usa `protocolo-respaldo.md` como procedimiento. La única diferencia es que la Cascada no pide confirmación para ejecutarlo — está incluido en el flujo.

---

*Fulgurar · Consume letras. Produce luz.*
*Cascada · El corpus entra. La luz sale completa.*
