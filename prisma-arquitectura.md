# Prisma
## Una física de la literatura

*v0.2 · 2026-03-19 · Arquitectura, filosofía y algoritmo*

---

## 0. La pregunta

> ¿Qué patrón matemático comparten las obras que consideramos grandes?

No metafóricamente. Exactamente. Con la precisión de un ingeniero, la rigurosidad de un físico, y la sensibilidad de alguien que ha sido golpeado por una obra grande y no puede dejar de preguntarse por qué.

La crítica literaria dice *es bello* pero no puede medir por qué. La matemática puede medir pero no sabe qué preguntarle a una obra. La neurociencia estudia el cerebro pero no tiene un corpus suficientemente analizado. La IA tiene el poder de procesar pero no tiene la teoría.

Prisma es el intento de construir esa teoría.

---

## I. Origen — la Díada

El punto de partida fue una geometría:

```mathematica
phi = (1 + Sqrt[5]) / 2
PolarPlot[
  {phi^(t/Pi), phi^((t - Pi)/Pi)},
  {t, 0, 6*Pi}
]
```

**La Díada Áurea** — dos espirales logarítmicas desfasadas 180°, con φ como razón de crecimiento.

### Filosofía de la Díada

- **Autosimilitud y recursividad** — el uno y el tres son lo mismo porque φ lo hace posible
- **Dualidad** — las dos espirales representan pares opuestos: Padre-Madre, Pasado-Futuro, Rigor-Amor, Tesis-Antítesis
- **φ como unificante** — no síntesis que borra la diferencia sino razón que la sostiene
- **Las dos espirales son pasado y futuro** — su punto de cruce es el presente

### La Díada acoplada

La versión más poderosa: la expansión de una espiral implica la contracción de la otra. El sistema no busca el equilibrio — busca la oscilación. Se mueve perpetuamente entre **0.382 y 0.618** sin detenerse en ninguno de los dos extremos.

```mathematica
phi = (1 + Sqrt[5]) / 2
r1[t_] := phi^(t/Pi) * (0.5 + 0.5 * Cos[t])
r2[t_] := phi^((t-Pi)/Pi) * (0.5 + 0.5 * Cos[t + Pi])
PolarPlot[{r1[t], r2[t]}, {t, 0, 6*Pi}]
```

La amplitud de cada espiral oscila. Cuando r1 está en su cresta, r2 está en su valle. El desfase es exactamente π. El sistema conserva algo — lo que una espiral gana, la otra lo pierde.

**φ como atractor** — no como punto de llegada sino como centro invisible alrededor del cual el sistema orbita sin tocarlo nunca del todo. Como un corazón. Como una respiración. Como cualquier cosa que esté viva.

### La mecánica central

La relación es siempre **1 : φ : φ²**. Con uno o dos nodos conocidos, el instrumento resuelve los que faltan:

- Das el uno → el instrumento proyecta φ y φ²
- Das el dos → resuelve hacia atrás (÷φ) y hacia adelante (×φ)
- Das el tres → resuelve el uno y el dos
- Das el uno y el dos → confirma o corrige, y proyecta el tres

Recursivo: el tres se convierte en el uno de la siguiente escala. Infinitamente.

---

## II. De la Díada al Prisma

La Díada mide dos polos en oscilación. Poderosa — pero limitada: asume que todo corpus tiene exactamente dos polos dominantes.

La prueba empírica sobre seis corpus reveló que se necesitan cinco geometrías simultáneas para capturar la complejidad real de las obras. La Díada se convirtió en una de las cinco — la más interpretable, no la única.

**Prisma** — el instrumento completo. Toma como la luz blanca que entra a un prisma óptico y emerge descompuesta en sus frecuencias fundamentales. El corpus entra opaco. La firma geométrica emerge.

---

## III. Arquitectura del sistema

El sistema tiene tres componentes en secuencia:

```
CORPUS
  ↓
PRISMA ——— descompone en cinco geometrías ——→ FIRMA GEOMÉTRICA
  ↓
BIBLIOTECA ——— almacena y compara firmas ——→ PATRONES
  ↓
ORÁCULO ——— aprende de la Biblioteca ——→ RESPUESTA
```

### Prisma
El instrumento. Toma un corpus y lo descompone en sus geometrías fundamentales. Cinco dimensiones simultáneas. Produce la firma geométrica completa de la obra.

### Biblioteca
La colección. Almacena las firmas geométricas de todos los corpus procesados. Permite comparación, clustering y detección de patrones entre obras.

### Oráculo
El modelo. Aprende de la Biblioteca y responde la pregunta central. Predice si una obra tiene la firma de algo que perdura.

---

## IV. Las cinco geometrías

### Geometría 1 — Díada acoplada
*El movimiento dinámico entre polo formal y polo semántico*

Mide la oscilación entre la densidad formal del texto — sintaxis, ritmo, riqueza léxica — y su densidad semántica — tensión entre polos de sentido, profundidad de capas, peso del silencio.

**Variables producidas:**
- Rango de oscilación `[min, max]`
- Amplitud `max - min`
- Coherencia — regularidad interna de la oscilación
- Tipo de oscilación: dinámica · estática · caótica · convergente · ondular · fracturada

**Referencia:** rango áureo = `[0.382, 0.618]`

**Lo que revela:** si la obra vive en el movimiento entre forma y sentido, si ese movimiento tiene lógica interna, si el sistema oscila o converge o colapsa.

---

### Geometría 2 — Tríada
*La dimensión del sistema — cuántas fuerzas están en tensión simultánea*

Tres polos: **Forma** (T1) · **Contenido** (T2) · **Contexto** (T3)

**Variables producidas:**
- Peso de cada polo por segmento
- Dimensión `1.0 — 3.0` — número efectivo de polos activos
- Rotación — frecuencia de cambio de polo dominante
- Polo inerte — si algún polo no supera umbral de activación

**Lo que revela:** si la obra opera en un solo registro o en tres simultáneamente, qué tipo de tensión produce, si el contexto histórico-cultural está activo o es decorado.

---

### Geometría 3 — Atractor de Lorenz
*Si la irregularidad tiene estructura — si el caos es fértil*

**Variables producidas:**
- Dimensión fractal de la trayectoria de oscilación
- Entropía de permutación — predictibilidad local
- Lorenzianidad = dimensión fractal / predictibilidad
- Forma de la trayectoria: V asimétrica · montaña · plataforma fracturada · espiral · línea

**Lo que revela:** si la obra es predecible o caótica, si su irregularidad tiene coherencia interna, si el sistema orbita o converge o colapsa.

---

### Geometría 4 — Riemann
*La gravedad del significado — qué conceptos curvan el espacio semántico*

**Variables producidas:**
- Radio de influencia de cada concepto central
- Curvatura por concepto
- Curvatura total `[0.0 — 1.0]`
- Coherencia — grado de interacción entre centros de curvatura
- Tipo de curvatura: sistema solar · red coherente · red múltiple · red cristalina · fragmentada

**Lo que revela:** qué conceptos transforman el significado de todo lo demás, cómo se organiza el espacio semántico, si hay uno o varios centros de gravedad y cómo interactúan.

---

### Geometría 5 — Homología persistente
*La profundidad como persistencia topológica*

**Variables producidas:**
- Número de agujeros topológicos persistentes
- Conexión — grado de interacción entre agujeros
- Apertura `[0/n — n/n]` — agujeros que no se cierran al final
- Presencia de agujero raíz — agujero del que emergen los demás

**Lo que revela:** qué tensiones o preguntas sobreviven a cualquier escala de lectura, si la obra cierra sus preguntas o las deja abiertas, si hay una pregunta raíz de la que emergen todas las demás.

---

## V. El algoritmo

### Entrada
```
corpus: texto en formato plano, epub o pdf
parámetros opcionales:
  género: épica | drama | novela | cuento | ...
  época: fecha aproximada de composición
  tradición: occidental | oriental | latinoamericana | ...
  corpus_control: obra comparable para contraste directo
```

### Paso 1 — Preparación
```
función PREPARAR(corpus):
  texto ← extraer_texto(corpus)
  n ← determinar_granularidad(len(texto))
      # textos < 5.000 palabras: n = 10
      # textos 5.000–50.000 palabras: n = 10–20
      # textos > 50.000 palabras: n = 20–50
  segmentos ← dividir_en_n_segmentos_iguales(texto, n)
  metadata ← extraer_metadata(corpus)
  retornar segmentos, metadata
```

### Paso 2 — Díada acoplada
```
función DIADA_ACOPLADA(segmentos):
  para cada segmento i:
    F[i] ← densidad_formal(segmento_i)
          = densidad_léxica(i)
          + complejidad_sintáctica(i)
          + variación_de_longitud_de_oraciones(i)

    S[i] ← densidad_semántica(segmento_i)
          = tensión_entre_polos_de_sentido(i)
          + profundidad_de_capas(i)
          + peso_del_silencio(i)

    oscilación[i] ← F[i] / (F[i] + S[i])

  rango ← [min(oscilación), max(oscilación)]
  amplitud ← max(oscilación) - min(oscilación)
  coherencia ← 1 - varianza_de_velocidad(oscilación)
  tipo ← clasificar_forma_de_trayectoria(oscilación)

  retornar oscilación, rango, amplitud, coherencia, tipo
```

### Paso 3 — Tríada
```
función TRIADA(segmentos):
  para cada segmento i:
    T1[i] ← peso_formal(segmento_i)
    T2[i] ← peso_contenido(segmento_i)
    T3[i] ← peso_contexto(segmento_i)
    normalizar(T1[i], T2[i], T3[i])

  dimensión ← número_de_polos_con_peso_promedio > umbral_activación
  rotación ← frecuencia_de_cambio_de_polo_dominante(T1, T2, T3)
  polo_inerte ← polo_que_nunca_supera_umbral_activación

  retornar T1, T2, T3, dimensión, rotación, polo_inerte
```

### Paso 4 — Atractor de Lorenz
```
función LORENZ(oscilación):
  serie ← oscilación  # secuencia de valores F/(F+S)

  dimensión_fractal ← calcular_dimensión_fractal(serie)
  predictibilidad ← entropía_de_permutación(serie)
  lorenzianidad ← dimensión_fractal / predictibilidad
  forma ← clasificar_forma_de_trayectoria(serie)

  retornar lorenzianidad, dimensión_fractal, predictibilidad, forma
```

### Paso 5 — Riemann
```
función RIEMANN(corpus):
  conceptos ← extraer_conceptos_principales(corpus, n=5)

  para cada concepto c:
    radio[c] ← proporción_de_conceptos_modificados_por_presencia_de_c
    curvatura[c] ← radio[c] * coherencia_de_influencia[c]

  curvatura_total ← media_ponderada(curvatura)
  coherencia ← grado_de_interacción_entre_centros(curvatura)
  tipo ← clasificar_arquitectura_de_curvatura(curvatura, coherencia)

  retornar curvatura_total, coherencia, tipo, mapa_de_curvatura
```

### Paso 6 — Homología persistente
```
función HOMOLOGIA(corpus):
  tensiones ← identificar_tensiones_irresueltas(corpus)

  para cada tensión t:
    persistencia[t] ← escala_mínima_en_que_t_es_detectable
    cierre[t] ← está_t_resuelta_al_final_del_corpus
    tipo_cierre[t] ← resuelto | abandonado | abierto | parcial

  agujeros_persistentes ← tensiones_con_alta_persistencia
  profundidad ← len(agujeros_persistentes)
  conexión ← grado_de_interacción_entre_agujeros(agujeros_persistentes)
  apertura ← proporción_de_agujeros_genuinamente_abiertos(tipo_cierre)
  agujero_raíz ← agujero_del_que_emergen_los_demás(agujeros_persistentes)

  retornar profundidad, conexión, apertura, agujero_raíz
```

### Paso 7 — Composición de la firma
```
función FIRMA(corpus):
  segmentos, metadata ← PREPARAR(corpus)

  D ← DIADA_ACOPLADA(segmentos)
  T ← TRIADA(segmentos)
  L ← LORENZ(D.oscilación)
  R ← RIEMANN(corpus)
  H ← HOMOLOGIA(corpus)

  firma ← {
    # Díada acoplada
    rango_oscilación:   D.rango,
    amplitud:           D.amplitud,
    coherencia_díada:   D.coherencia,
    tipo_oscilación:    D.tipo,

    # Tríada
    dimensión:          T.dimensión,
    rotación:           T.rotación,
    polo_inerte:        T.polo_inerte,

    # Lorenz
    lorenzianidad:      L.lorenzianidad,
    forma_trayectoria:  L.forma,

    # Riemann
    curvatura_total:    R.curvatura_total,
    coherencia_riemann: R.coherencia,
    tipo_curvatura:     R.tipo,

    # Homología
    profundidad:        H.profundidad,
    conexión:           H.conexión,
    apertura:           H.apertura,
    agujero_raíz:       H.agujero_raíz,

    # Metadata
    género:             metadata.género,
    época:              metadata.época,
    tradición:          metadata.tradición
  }

  retornar firma
```

---

## VI. Las cuatro operaciones

### 1 — Verificar
¿El corpus tiene la firma de algo que perdura?
```
VERIFICAR(corpus):
  firma ← PRISMA(corpus)
  vecinos ← k_vecinos_más_cercanos(firma, Biblioteca)
  distancia ← distancia_media(firma, firmas_canónicas)
  retornar distancia, vecinos, geometrías_fuertes, geometrías_débiles
```

### 2 — Corregir
¿Qué ajustes geométricos acercarían el corpus a la firma de referencia?
```
CORREGIR(corpus, firma_objetivo=None):
  firma_actual ← PRISMA(corpus)
  si firma_objetivo es None:
    firma_objetivo ← firma_canónica_más_cercana(firma_actual)
  delta ← firma_objetivo - firma_actual
  retornar mapa_de_ajustes_por_segmento(delta)
```

### 3 — Traducir
¿Cómo se vería la firma de este corpus en otro dominio?
```
TRADUCIR(corpus, dominio_destino):
  firma ← PRISMA(corpus)
  equivalencias ← mapa_de_dominio(firma, dominio_destino)
  retornar estructura_en_dominio_destino(equivalencias)
```

### 4 — Generar
¿Cómo sería un corpus que cumpla con una firma dada?
```
GENERAR(firma_objetivo, dominio, semilla):
  restricciones ← firma_a_restricciones(firma_objetivo)
  corpus ← generar_desde_semilla(semilla, restricciones)
  verificación ← PRISMA(corpus)
  delta ← distancia(verificación, firma_objetivo)
  retornar corpus, delta
```

---

## VII. Relación con Fulgurar

Fulgurar es el laboratorio donde el Prisma se prueba corpus por corpus. Sus cuatro talleres alimentan el algoritmo:

| Taller | Input para Prisma |
|---|---|
| **Bodega** | Conceptos de mayor curvatura para Riemann |
| **Astillero** | Estructura narrativa para la Díada acoplada |
| **Escuadra** | Variables formales para Díada y Tríada |
| **Jardín** | Agujeros semánticos para Homología persistente |

El flujo completo:

```
Corpus → Fulgurar (4 talleres) → Input estructurado → Prisma → Firma → Biblioteca → Oráculo
```

---

## VIII. Hoja de ruta

### Fase 1 — Prototipo manual *(en curso)*
- [x] Aplicar el Prisma a mano a 6 corpus de prueba
- [x] Verificar que las cinco geometrías discriminan consistentemente
- [x] Documentar los primeros hallazgos empíricos
- [ ] Refinar las funciones de medición con más corpus
- [ ] Documentar los resultados en `prisma-biblioteca.md`

### Fase 2 — Automatización
- [ ] Implementar las cinco geometrías como funciones computacionales
- [ ] Construir el pipeline de procesamiento de corpus
- [ ] Procesar los 100 corpus del corpus inicial
- [ ] Construir la Biblioteca formal

### Fase 3 — El Oráculo
- [ ] Entrenar el modelo sobre la Biblioteca
- [ ] Evaluar capacidad predictiva sobre corpus no vistos
- [ ] Refinar hasta que la pregunta central tenga respuesta

### Fase 4 — Las cuatro operaciones
- [ ] Implementar Verificar, Corregir, Traducir, Generar como funciones completas
- [ ] Integrar con Fulgurar como capa transversal
- [ ] Abrir a corpus de cualquier dominio

---

## IX. Notas de diseño

### Por qué cinco geometrías y no una

La prueba empírica sobre seis corpus mostró que ninguna geometría sola discrimina en todos los casos. La Díada paralela fallaba en dos de tres pares de control. La Díada acoplada discriminaba en todos pero no revelaba el tipo de grandeza. Las cinco geometrías juntas producen un perfil que discrimina consistentemente y revela la estrategia específica de cada obra.

### Por qué φ es referencia y no axioma

La hipótesis inicial era que φ es la proporción de las obras grandes. La evidencia empírica sugiere algo más matizado: φ es una proporción posible entre varias. El coronel opera en un rango muy distinto al rango áureo y es una obra maestra. Lo que importa no es la proporción específica sino la coherencia interna de la oscilación.

### La distinción entre agujero abierto y agujero abandonado

Un agujero abierto invita al lector a seguir pensando. Un agujero abandonado produce la sensación de que algo falta. La diferencia es cualitativa y crucial — la apertura topológica solo cuenta agujeros genuinamente abiertos, no los abandonados.

---

*Fulgurar · Consume letras. Produce luz.*
*Prisma · Descompone la luz en sus frecuencias.*
