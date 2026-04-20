# Brand System — Master document

> Plantilla de sistema de marca para creadores de contenido con IA.
> Este archivo es la fuente de verdad. Claude Design, Lovable, v0, Cursor y cualquier
> agente de IA deben leer este archivo primero para aplicar la identidad visual y verbal.

---

## 1. Identidad

**Marca:** [TU MARCA]
**Creador:** [TU NOMBRE / @tu-handle]
**Propuesta:** [Describe en una frase qué haces y para quién]
**Audiencia:** [A quién va dirigido tu contenido]
**Tono:** [Adjetivos de tu voz — ej: directo, práctico, anti-hype, humano]
**Voz:** [Cómo te diriges — singular/plural, tú/usted, tono formal/informal]

> Rellena los campos anteriores antes de pasar este doc a un agente de IA.
> Sin identidad concreta, el agente inventará una y no será la tuya.

---

## 2. Paleta de colores

Paleta de ejemplo. Adáptala en `tokens/colors.json`.

### Principales
| Nombre | Hex | Uso |
|--------|-----|-----|
| **Azul primario** | `#9BBDDC` | Color principal. Fondos de CTA, portadas, bloques destacados |
| **Amarillo acento** | `#E8C547` | Acento. Palabras clave en hooks |
| **Negro tinta** | `#1A1A1A` | Texto principal sobre fondos claros. NO es negro puro — tiene textura sutil |
| **Beige papel** | `#F5F0E8` | Fondo alternativo tipo "cuaderno viejo" |
| **Blanco roto** | `#FAF8F3` | Texto sobre azul y fondos oscuros |

### Secundarios
| Nombre | Hex | Uso |
|--------|-----|-----|
| **Azul drip** | `#6B9BC4` | Version más saturada del azul, para drips y subrayados spray |
| **Amarillo drip** | `#D4B53A` | Version más saturada del amarillo, para drips |
| **Washi tape** | `#D9CDB5` | Color del celo/washi tape que aparece pegando screenshots |
| **Gris papel** | `#A8A39A` | Sombras sutiles sobre papel |

### Reglas de uso
- Fondo **azul primario** → palabra clave en **amarillo acento** + resto en **blanco roto**
- Fondo **beige papel** → texto en **negro tinta** + destacados en **azul** o **amarillo**
- NUNCA usar negro puro `#000000`. NUNCA usar blanco puro `#FFFFFF`
- Subrayados siempre con efecto **drip paint** (ver `tokens/effects.md`)

---

## 3. Tipografía

Sistema de **4 fuentes** que se combinan en toda pieza:

### 1. Display Graffiti (spray/stencil)
- **Uso:** Palabras clave grandes en portadas y transiciones
- **Estilo:** Stencil grueso con efecto drip/pintura que gotea
- **Fuentes recomendadas (premium):** Bourton, Boucherie Block, Rust Bold
- **Alternativa free:** Rubik Mono One + efecto drip añadido

### 2. Serif Italic Elegante
- **Uso:** Palabras destacadas en cursiva
- **Estilo:** Serif alta con contraste, italic refinada
- **Fuentes recomendadas (premium):** Domaine Display Italic, Cormorant Italic
- **Alternativa free:** Playfair Display Italic (Google Fonts)

### 3. Sans Bold Condensed
- **Uso:** Títulos de sección, hooks, CTAs
- **Estilo:** Sans-serif ultra bold, condensed, impactante
- **Fuentes recomendadas (premium):** Druk Wide Bold, Bebas Neue Bold
- **Alternativa free:** Archivo Black o Anton (Google Fonts)

### 4. Handwritten Casual
- **Uso:** Anotaciones, subtítulos, tips, frases explicativas
- **Estilo:** Manuscrita natural, ligeramente irregular
- **Fuentes recomendadas:** Caveat Bold, Kalam, Shadows Into Light
- **Alternativa free:** Caveat (Google Fonts)

### Jerarquía tipográfica
```
H1 (hook palabra clave)  → Display Graffiti, 180-240pt, amarillo o azul
H1-alt (hook normal)     → Sans Bold Condensed, 100-140pt
H2 (script accent)       → Serif Italic, 80-100pt
H3 (subtítulo)           → Sans Bold Condensed, 40-56pt
Body                     → Sans regular (Inter / Manrope), 28-36pt
Annotation               → Handwritten Casual, 32-40pt
Caption                  → Handwritten Casual, 24-28pt
```

---

## 4. Efectos y texturas (signature)

Ver detalle completo en `tokens/effects.md`. Resumen:

1. **Fondo papel arrugado** — textura base presente en ~90% de slides
2. **Washi tape beige** (`#D9CDB5`) — pegando esquinas de screenshots con rotación sutil (±5deg)
3. **Spray paint drip** — underline animado/estático en palabras clave
4. **Flechas manuscritas** — anotaciones negras dibujadas a boli
5. **Sombra sutil** bajo mockups/cards (no dramática, solo papel sobre papel)
6. **Grano sutil** en fotos y fondos (aumenta sensación "analógica")

---

## 5. Estructura canónica de carrusel (10-11 slides)

Fórmula que funciona. Cualquier carrusel nuevo debe seguir esta estructura salvo excepción justificada.

```
Slide 1  — HOOK: mezcla de tipografías + talento recortado + palabra clave XXL
Slide 2  — CONTEXTO: "VETE A / ENTRA EN" + screenshot con washi tape
Slide 3  — PASO 1 (numerado "PASO 1" grande en graffiti)
Slide 4  — PASO 2
Slide 5  — PASO 3
Slide 6  — PASO 4 (opcional)
Slide 7  — COMPARATIVA: "MAL SISTEMA" vs "BUEN SISTEMA" (checkmarks)
Slide 8  — TIP destacado (elemento visual + flecha manuscrita)
Slide 9  — TRANSICIÓN: texto corto sobre fondo de color (sin screenshots)
Slide 10 — CTA: "COMENTA 'X'" (fondo color + keyword amarilla) + handle al pie
Slide 11 — Firma / cierre (opcional)
```

Detalle de cada tipo de slide en `patterns/`.

---

## 6. Formato técnico

- **Aspect ratio:** 4:5 vertical (1080 × 1350 px) para Instagram feed
- **Stories / Reels cover:** 9:16 (1080 × 1920 px)
- **Dots de carrusel:** visibles en la portada (mockup Instagram)
- **Exportar:** PNG o JPG quality 90 (balance peso/calidad)

---

## 7. Personaje (talent)

**Recomendado:** el creador aparece en la portada (slide 1) del carrusel, recortado sin fondo
(PNG transparente) y colocado EN FRENTE del texto grande (layering).

Poses sugeridas:
- Sentado en el suelo con objeto relacionado con el tema — pose relajada
- Frente al ordenador — pose trabajadora
- De pie talking head — pose directa
- Cuclillas — pose casual

> Las fotos del talento no se versionan en este repo (privacidad/tamaño).
> Mantenlas en un drive/Notion y enlázalas desde el agente de IA.

---

## 8. Voz y copy

El copy de tus piezas es lo más personal de tu marca y lo que más cuesta automatizar.

Recomendaciones para crear tu propia guía de voz:

- **Transcribe 30-60 reels/posts reales tuyos** y analiza patrones
- **Identifica tus muletillas** (las frases que repites sin darte cuenta)
- **Saca una lista de hooks que te funcionan** — cópialos como plantillas
- **Define tu estructura estándar** (ej: hook → contexto → 3-5 pasos → cierre → CTA)
- **Anota qué NO hacer** (evitar "Hola", "Hoy vamos a ver", etc.)

> Esta plantilla no incluye guía de voz — es muy personal y se genera a partir del análisis
> de tu contenido real. Si quieres hacer la tuya, guárdala en una carpeta `voz/` con:
> `tono.md`, `hooks.md`, `ctas.md`.

---

## 9. Qué NO hacer

- ❌ Negro puro `#000000` o blanco puro `#FFFFFF`
- ❌ Fuentes limpias tipo SF Pro / Helvetica sin mezcla de estilos
- ❌ Portadas sin personaje/talento visible
- ❌ Fondos planos sin textura de papel
- ❌ Una sola tipografía en portadas (deben ser 3-4 mezcladas)
- ❌ Tono corporativo, formal o de agencia
- ❌ Emojis decorativos gratis (solo si suman contexto)
- ❌ "Haz click en el enlace" tipo gurú de LinkedIn

---

## 10. Archivos del sistema

| Archivo | Contenido |
|---------|-----------|
| `tokens/colors.json` | Paleta en JSON parseable |
| `tokens/typography.json` | Fuentes + tamaños + pesos |
| `tokens/effects.md` | Drip, washi, grano, sombras (con specs CSS) |
| `tokens/fonts.css` | CSS listo para importar con variables y clases |
| `patterns/*.md` | Plantillas de cada tipo de slide |
| `examples/*.html` | Ejemplos HTML/CSS aplicando el sistema |
| `assets/logos/` | Tus logos vectoriales |
| `assets/texturas/` | PNGs de papel, spray, washi |
| `fonts/` | Archivos .woff2 / .ttf |

---

*Última actualización: 2026-04-20*
