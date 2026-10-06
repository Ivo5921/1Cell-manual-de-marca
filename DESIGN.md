# DESIGN.md — 1CELL Health

> Sistema de marca v1.0 · 2026
> Fuentes: 1cellhealth.com (inicio y About) + 14 fotos de producto reales.
> **Instagram no se pudo leer** (bloquea acceso automatizado). Todo lo de Instagram debe validarse a mano contra este documento.
> Los colores marcados **(medido)** salen de pixeles de las fotos de producto. Los marcados **(estimado)** son aproximaciones visuales. Confirmar contra el archivo fuente del logo antes de entregar a imprenta o desarrollo.

---

## 1. Esencia de marca

- **Nombre:** 1CELL HEALTH (logo: "1CELL" en negrita + "HEALTH" en versalitas con tracking amplio debajo)
- **Fundada:** 2026 · México y Estados Unidos
- **Tagline:** *Regeneration, engineered.*
- **Promesa:** Un solo estándar para medicina regenerativa. Biológicos trazables, cadena de frío 2–8 °C ininterrumpida, guía médica real.
- **Posicionamiento:** Clínico-premium. No es wellness de gurú ni suplemento de gimnasio. Es biotecnología con respaldo documental y acompañamiento médico.
- **Mensaje central:** *Producto + protocolo + guía médica = resultados confiables.* Nunca vendes solo un frasco.
- **Contrapunto declarado:** "No promises. Only evidence." Nada de autoconsumo sin supervisión.

### Pilares (usar tal cual en comunicación)
1. **Rigor científico** — decisiones basadas en datos verificables.
2. **Trazabilidad total** — cada vial con COA e historial por lote.
3. **Acompañamiento real** — equipo médico detrás de cada envío.
4. **Ética compasiva** — sin promesas médicas, solo evidencia y cuidado.

### Públicos
- **Profesional (licencia verificada):** células madre mesenquimales, exosomas, células NK y Muse. Acceso por solicitud.
- **Directo (consumidor):** péptidos, nutracéuticos, cosméticos. Compra directa con protocolo incluido.

---

## 2. Paleta de color

### Primarios
| Rol | Nombre | HEX | Origen | Uso |
|---|---|---|---|---|
| Marca | **1CELL Teal** | `#055C61` | medido (logo en frascos) | Logo, titulares clave, descriptores de producto, CTAs, acentos de datos |
| Fondo clínico | **Blanco** | `#FFFFFF` | web (theme-color) | Fondo base del sitio, tarjetas, espacios de respiro |
| Texto | **Carbón** | `#2B2B2D` | estimado (tipografía serif oscura de etiquetas) | Nombres de producto, cuerpo de texto |

### Neutros cálidos (fondos de fotografía y secciones)
| Nombre | HEX | Origen | Uso |
|---|---|---|---|
| **Arena clara** | `#F0E9DF` | medido | Fondo de secciones suaves, fotos de exosomas |
| **Arena media** | `#E2D5C8` | medido | Fondo de fotos de nutracéuticos, bloques de apoyo |
| **Piedra** | `#D4CEBB` | medido | Fondo de fotos de péptidos y viales |
| **Hueso (etiqueta)** | `#F0ECEB` | medido | Etiquetas blancas de exosomas y suplementos |

### Códigos de línea (color de etiqueta = categoría)
| Línea | Color de etiqueta | HEX | Origen |
|---|---|---|---|
| **Péptidos inyectables** (BPC-157, Ipamorelin, TB-500, GHK-Cu, Timosina Alfa-1) | Verde salvia | `#B5B9A5` | medido (rango #A5A896–#C7C9BA según luz) |
| **Terapias IV** (Glutathione, Myers' Cocktail, Vitamin C) | Beige arenoso/kraft | `#A99880` | medido (rango #A99880–#B6A58E) |
| **Exosomas** (Secretome, Eonia Derma Glow, Regen X Ultra) | Blanco hueso con patrón molecular | `#F0ECEB` | medido |
| **Nutracéuticos orales** (Collagen, Melatonin, Sublingual Factors, Mitochondrial Boost, Omega 3) | Blanco hueso con patrón molecular | `#F0ECEB` | medido |

### Acentos
| Nombre | HEX | Origen | Uso |
|---|---|---|---|
| **Dorado filete** | `#B8975A` | estimado | Única línea fina bajo el nombre en etiquetas de exosomas. Usar solo como filete, nunca como relleno |
| **Gris tapa metálica** | `#9A9A9C` | estimado | Tapas de aluminio de viales |
| **Gris envase** | `#4A4A4C` | estimado (el envase se ve #777476 con luz) | Frascos de cápsulas |
| **Azul IV** | `#9CC9D0` | estimado | Líquido y conector de las bolsas IV. Solo en fotografía, no como color de UI |

### Reglas de color
- El teal es el **único** color saturado. Todo lo demás es neutro cálido. Si una pieza tiene más de un color saturado, está mal.
- Fondos de foto siempre cálidos (arena/piedra), nunca blancos puros ni grises fríos.
- Contraste: texto teal sobre salvia o hueso pasa AA para tamaños grandes. En texto pequeño sobre salvia, usar carbón.

---

## 3. Tipografía

> No pude extraer los archivos CSS del sitio. Lo siguiente es lo que se ve en etiquetas y web; confirmar nombres exactos de fuente con quien desarrolló el sitio.

| Rol | Estilo observado | Sugerencia de fuente (equivalente) |
|---|---|---|
| **Logo "1CELL"** | Sans geométrica pesada, "1" con corte diagonal característico | Logo en vectores; no recrear con fuente |
| **"HEALTH" y metadatos** | Sans ligera, mayúsculas, tracking muy abierto (+200 a +300) | Inter / Söhne, peso 400, tracking +0.25em |
| **Nombres de producto** | Serif editorial de alto contraste, peso regular, tamaño grande | Canela, Tiempos Headline, Newsreader, Fraunces |
| **Descriptores** ("Premium Peptide", "Premium Exosome Therapy") | Sans pequeña, regular. En teal sobre fondo blanco; en blanco sobre salvia | Inter 400, 13–14 px |
| **Cuerpo web** | Sans limpia | Inter o equivalente, 16–18 px, interlineado 1.6 |
| **Datos** (≥95%, 2–8 °C, 24/7) | Cifras grandes destacadas, unidad pequeña al lado | Serif o sans pesada, unidad en peso ligero |

### Jerarquía en etiqueta (de arriba a abajo, siempre igual)
1. Logo 1CELL HEALTH
2. Filete fino
3. **Nombre del producto** (serif, protagonista)
4. Filete fino (en exosomas: dorado)
5. Descriptor de categoría (sans, pequeño)
6. Código de barras (solo en exosomas y nutracéuticos, vertical a la derecha)

### Reglas
- Un solo serif y una sola sans. Nada más.
- Los titulares de la web cierran con punto: *Regeneration, engineered.*
- Cursiva serif para énfasis dentro de titulares: *regenerative medicine.*
- Mayúsculas solo en "HEALTH", metadatos y etiquetas pequeñas.

---

## 4. Estilo visual

### Dirección
Farmacia de lujo + laboratorio limpio. Minimalismo clínico, cálido, silencioso. Se parece más a una marca de skincare médico premium que a una farmacéutica tradicional.

### Fotografía de producto (la que me pasaste)
- **Fondo:** liso, cálido, con degradado casi imperceptible y textura sutil de papel/yeso. Sin props, sin personas, sin manos.
- **Encuadre:** producto único centrado, vertical 3:4 (960×1280) o 3:4.2 (1086×1448). Aire amplio arriba y abajo.
- **Composición de grupo:** 4 frascos escalonados en profundidad, ligera diagonal, sin tocarse (ver imagen de péptidos).
- **Luz:** suave, lateral, sombra corta y blanda sobre la superficie. Reflejos controlados en vidrio. Sin dramatismo.
- **Material:** vidrio transparente, tapa de aluminio satinado, frasco gris mate para orales, bolsa IV transparente con líquido azul-turquesa.
- **Render:** fotorrealista, de alta definición, con apariencia de render 3D pulido. Mantener consistencia entre lotes de imágenes.
- **Etiquetas:** siempre cilíndricas, centradas, con margen interno generoso.

### Elementos gráficos
- **Patrón molecular:** red de nodos y líneas grises muy tenues en el costado derecho de las etiquetas blancas. Nunca competir con el texto.
- **Filetes finos:** líneas de 1 px que separan logo, nombre y descriptor.
- **Código de barras vertical:** dato técnico que refuerza la idea de trazabilidad. Mantener en exosomas y orales.
- **Ticker en web:** "Mesenchymal Stem Cells ✳ Exosomes ✳ NK Cells ✳ Muse Cells ✳ Peptides ✳ Longevity ✳" en banda corrida.
- **Chips de dato:** "4.2 °C · in range", "COA per batch", "≥ 95% Viability". Estilo monitor clínico.

### Web
- Fondo blanco, mucho espacio negativo, scroll narrativo.
- Secciones numeradas (01, 02, 03) para procesos.
- Fotografía de laboratorio, macro celular, caja de cadena de frío con logger digital, consulta médica.
- Tarjetas de producto con etiqueta "Pro" (requiere licencia) o "Direct" (compra directa).
- Franja superior: "Cold-chain shipped worldwide — free over $150".
- Aviso legal al pie en texto pequeño: declaraciones no evaluadas por agencia regulatoria, no es consejo médico.

### Lo que NO es el estilo
- Sin colores neón, gradientes fluorescentes ni estética "biohacker".
- Sin fotografía stock de gente sonriendo con batas.
- Sin antes y después.
- Sin iconografía de ADN genérica en exceso.
- Sin fondos blancos puros en fotos de producto.

---

## 5. Tono de voz

### Rasgos
| Rasgo | Cómo se ve |
|---|---|
| **Clínico, no frío** | Datos concretos con calidez humana ("a clinician beside you") |
| **Sobrio** | Frases cortas, afirmaciones verificables |
| **Seguro sin presumir** | Confianza basada en documentación, no en adjetivos |
| **Responsable** | Siempre menciona protocolo, supervisión médica y límites |
| **Premium sin pompa** | Pocas palabras, sin superlativos |

### Fórmulas de escritura
- **Estructura "no X, solo Y":** *No promises. Only evidence.* / *Not self-medication.*
- **Triadas:** *The product. A clinical protocol. A medical team.*
- **Ecuaciones:** *Product + protocol + medical guidance = results you can trust.*
- **Datos antes que adjetivos:** cifras (≥95%, 2–8 °C, 24/7, 100% COA) en lugar de "increíble" o "revolucionario".
- **Titulares con punto final.**
- **Voz activa, presente:** "We deliver", "Every lot ships with", "Out-of-range lots are rejected."

### Idioma
- Web bilingüe EN/ES (toggle). Inglés es el idioma base. Español debe sonar igual de sobrio, no traducción literal.
- **Inconsistencia detectada:** el frasco de Timosina Alfa-1 está en español mientras el resto de la línea está en inglés ("Premium Peptide"). Unificar o crear versión ES de todas las etiquetas.

---

## 6. Frases que SÍ usa la marca

Extraídas de la web:

- "Regeneration, engineered."
- "One standard. Every batch."
- "One standard for regenerative medicine."
- "No promises — only evidence."
- "No promises. Only evidence — and a clinician beside you."
- "We don't sell hope."
- "Per-batch evidence, no noise."
- "You never receive just a vial."
- "Advanced science, without the self-medication."
- "Product + protocol + medical guidance = results you can trust."
- "Traceable biology."
- "Unbroken cold chain."
- "Real medical guidance." / "Real accompaniment."
- "Never leaving 2–8 °C."
- "From culture to clinic."
- "Characterized, documented and sustainable."
- "New science, made safe to use."
- "Applied with a protocol, not self-prescribed."
- "Held to one standard."
- "Every lot traceable to its Certificate of Analysis."
- "Clinical-grade regenerative biologics."
- "Cold-chain shipped worldwide."
- "A medical team on hand, from the first dose to follow-up."
- "Compassionate ethics."
- "Scientific rigor."

### Vocabulario clave
COA (Certificate of Analysis), lote/batch, trazabilidad, cadena de frío, caracterizado, viabilidad, protocolo clínico, guía médica, biológicos, cGMP, citometría de flujo, estándar, evidencia.

---

## 7. Frases que NO usa la marca

> Esta lista sale de la lógica de posicionamiento ("sin promesas, solo evidencia") y de lo que el sitio evita. No es un listado que la marca haya publicado. Úsala como filtro.

**Promesas médicas y de resultado**
- "Cura", "cure", "reversa el envejecimiento", "milagro", "garantizado"
- "Resultados en X días", "100% efectivo", "elimina arrugas"
- "Rejuvenece 10 años"
- Cualquier claim terapéutico que no esté respaldado por COA o literatura

**Autoconsumo y ligereza**
- "Inyéctate tú mismo", "hazlo en casa", "sin necesidad de médico"
- "Biohack", "hackea tu cuerpo", "stack", "boost your gains"

**Hype y superlativos vacíos**
- "Revolucionario", "el mejor del mundo", "secreto", "fórmula mágica"
- "Increíble", "poderoso", "ultra-potente" (aunque un producto se llame *Regen X Ultra*, no usarlo en copy)
- Signos de exclamación

**Urgencia y presión comercial**
- "¡Última oportunidad!", "Solo hoy", "No te lo pierdas"
- "Compra ya"

**Tono**
- Jerga de gimnasio o influencer
- Emojis en comunicación clínica (en redes, con mucha mesura)
- Lenguaje pomposo o académico impenetrable
- Hablar de "fuente de la juventud" o similares

---

## 8. Reglas de uso del logo

- Versión principal: "1CELL" en teal `#055C61` + "HEALTH" en gris medio con tracking abierto.
- Sobre salvia: usar teal oscuro. Sobre fondo oscuro: versión blanca (no hay muestra, definir).
- Espacio libre mínimo: altura de la "C" alrededor del logo.
- Nunca: distorsionar, añadir sombras, cambiar el teal, poner sobre fotos con ruido.
- Wordmark en web: "*1*CELL" con el "1" en cursiva/destacado + "HEALTH" separado.

---

## 9. Sistema de empaque (resumen operativo)

| Línea | Envase | Etiqueta | Nombre | Descriptor |
|---|---|---|---|---|
| Péptidos | Vial de vidrio + tapa aluminio | Salvia, liso | Serif blanco + dosis ("IPAMORELIN • 5mg") | "Premium Peptide" |
| Terapias IV | Bolsa transparente con tubo teal | Beige arenoso, esquinas redondeadas | Serif blanco | "Premium IV Peptides" |
| Exosomas | Vial ancho + tapa aluminio | Blanco hueso, patrón molecular, filete dorado, código de barras | Serif carbón | "Premium Exosome Therapy" (teal) |
| Orales | Frasco gris mate, tapa estriada | Blanco hueso, patrón molecular, código de barras | Serif carbón | Descriptor funcional en teal ("Circadian rhythm regulator.") |

### Problemas que veo (te lo digo directo)
1. **"Premium IV Peptides" en Glutathione, Myers' Cocktail y Vitamin C es incorrecto.** Glutatión es un tripéptido, pero Myers' Cocktail y Vitamina C no son péptidos. Un cliente médico lo nota y daña la credibilidad que toda la marca construye sobre rigor. Cambiar a "Premium IV Therapy" o "Premium IV Nutrients".
2. **Los viales de péptidos no tienen código de barras** y los de exosomas sí. Si la trazabilidad es el pilar, todos los productos deberían llevar lote/código visible.
3. **Los nombres "Eonia Derma Glow" y "Regen X Ultra" suenan a cosmético masivo,** distinto del tono clínico del resto. Evaluar renombrar o alinear.
4. **Descriptores inconsistentes:** orales usan frase funcional ("Fast-acting sublingual formulation."), péptidos e IV usan solo categoría. Definir una regla única.
5. **Mezcla de idiomas en etiquetas** (Timosina en español, resto en inglés).
6. **Claim "Medical team 24/7"** en web: asegurar que se pueda cumplir operativamente. Si el horario real es Lun–Vie 9:00–18:00 CT (como dice el pie de página), hay contradicción.
7. **Checkout demo en producción:** el sitio dice "Demo checkout — no payment is taken". Si ya vendes, eso resta confianza.

---

## 10. Checklist antes de publicar cualquier pieza

- [ ] ¿Usa el teal `#055C61` como único color saturado?
- [ ] ¿Fondo cálido (arena/piedra) en foto de producto?
- [ ] ¿Serif para el nombre de producto, sans para todo lo demás?
- [ ] ¿Cero promesas médicas y cero signos de exclamación?
- [ ] ¿Menciona protocolo o guía médica donde corresponde?
- [ ] ¿Incluye aviso legal si hay claims o producto profesional?
- [ ] ¿Dato concreto en lugar de adjetivo?
- [ ] ¿Año 2026 en cualquier fecha o copyright?

---

## 11. Pendiente por validar

- Feed de Instagram (@1cellhealth): paleta de posts, formato de carruseles, caption tipo, hashtags, frecuencia, uso de reels y tono real en español. **No lo pude leer.** Si me pasas capturas del perfil y 6–9 posts, completo esta sección.
- Nombres exactos de tipografías (revisar CSS del sitio).
- Archivo vectorial del logo para confirmar el HEX exacto del teal.
- Versión del logo para fondos oscuros.
- Páginas Products, Standard, Process y FAQ no analizadas en detalle (solo inicio y About).
