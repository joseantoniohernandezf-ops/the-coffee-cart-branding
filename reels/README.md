# Reels — Estilo motion · The Coffee Cart
> Guía de estilo para videos y reels de Instagram.
> Coherente con el sistema de marca: elegante, limpio, aspiracional.

---

## Estructura de reel (formato estándar)

```
0:00 – 0:02  Hook visual     — primer frame que detiene el scroll
0:02 – 0:05  Intro           — contexto rápido o pregunta
0:05 – 0:18  Contenido       — pasos, tips o momento del evento
0:18 – 0:22  Cierre          — frase aspiracional o resultado
0:22 – 0:27  CTA + outro     — llamada a acción con logo
```

Total recomendado: **25–30 segundos** para máximo engagement.

---

## Tipos de reel definidos

### 1. Reel de servicio — "Así funciona The Coffee Cart"
**Objetivo:** Mostrar el servicio en acción en un evento real
**Hook:** Toma aérea o close-up de una bebida siendo preparada
**Estructura:**
- Hook visual (bebida, vapor, latte art)
- Texto: "Llevamos el café de especialidad a tu evento"
- B-roll: setup de la barra → preparación → entrega al invitado → reacción
- Cierre: logo + "Cotiza tu evento"

### 2. Reel de tips — "3 cosas que no sabías del café de especialidad"
**Objetivo:** Educar y posicionarse como expertos
**Hook:** Texto cinético con la pregunta o dato sorprendente
**Estructura:**
- Hook: pregunta o dato en pantalla
- Tip 1 con b-roll relacionado
- Tip 2 con b-roll relacionado
- Tip 3 con b-roll relacionado
- CTA: "Síguenos para más"

### 3. Reel de evento — "Así fue el café en [tipo de evento]"
**Objetivo:** Mostrar un caso real, generar confianza
**Hook:** El momento más visual del evento (brindis, copa llena, sonrisa)
**Estructura:**
- Hook: mejor toma del evento
- Contexto: tipo de evento, número de personas
- Momentos destacados en corte rápido
- Quote del cliente en pantalla (Lora Italic)
- CTA: "¿Cuándo es tu evento?"

---

## Animaciones signature

| Efecto | Uso | Timing |
|---|---|---|
| **Fade in suave** | Entrada de textos y logos | `0.4s ease-in` |
| **Stagger de letras** | Palabras clave en portada | `0.08s` entre letras |
| **Zoom lento (Ken Burns)** | B-roll de bebidas y setup | `6–8s` muy sutil |
| **Corte seco** | Entre pasos o tips | Instantáneo |
| **Whip pan** | Transición energética entre escenas | `0.25s` |
| **Slide up** | Entrada de subtítulos y labels | `0.3s ease-out` |

Regla: **máximo 2 tipos de animación por reel**. Más variedad se ve amateur.

---

## Transiciones recomendadas

- **Corte seco** — la principal. Limpia y profesional.
- **Fade a negro/crema** — para cambios de sección o separar el CTA
- **Whip pan** — solo en reels de energía alta (eventos con mucha gente)
- **Match cut** — cuando hay dos tomas del mismo objeto (ej: taza vacía → taza llena)

Evitar: glitch, zoom brusco, transiciones de plantilla de CapCut genéricas.

---

## Estilo de b-roll

### Ángulos recomendados
- **Close-up extremo** — granos de café, vapor, latte art, manos trabajando
- **Over the shoulder** — barista preparando la bebida
- **Toma lateral** — la barra completa con el ambiente del evento
- **POV del invitado** — recibiendo la bebida

### Filtros y color grading
```
Temperatura:  cálida (+15 a +25) — nunca fría ni azulada
Contraste:    medio-alto (+10 a +20)
Highlights:   ligeramente bajos (-10) para no quemar blancos
Shadows:      ligeramente altos (+5) para mantener detalle en oscuros
Saturación:   moderada (+5 a +10) — nunca sobreexagerada
Grano:        sutil (10–15%) para textura cinematográfica
```

### Paleta de color en video
Buscar tomas donde dominen los tonos de la paleta de marca:
- Cafés y marrones cálidos
- Blancos cremosos (vapor, tazas, manteles)
- Negros profundos (café espresso, equipo)
- Evitar fondos azules, verdes o morados que rompan la paleta

---

## Tipografía en motion

| Rol | Fuente | Animación |
|---|---|---|
| **Keyword de hook** | Avenir Black / Nunito 900 | Stagger de letras, fade in |
| **Títulos de sección** | Avenir ExtraBold / Nunito 800 | Slide up |
| **Frases aspiracionales** | Lora Italic | Fade in suave |
| **Labels y pasos** | Avenir Medium uppercase | Fade in con delay |
| **Quote de cliente** | Lora Italic | Fade in centrado |

---

## Cards y overlays en video

### Lower third (texto sobre video)
```
Fondo: rgba(13, 13, 13, 0.65) o rgba(92, 50, 32, 0.70)
Texto: #FFFFFF o #F5F2EB
Padding: 12px 20px
Border-left: 3px solid #9E7B65  ← detalle latte como acento
```

### Texto flotante sobre b-roll
- Siempre con sombra de texto: `text-shadow: 0 1px 4px rgba(13,13,13,0.6)`
- Nunca texto blanco puro sobre fondo claro sin overlay
- Si el fondo es muy variable, agregar un overlay oscuro al 40–50%

---

## Intro / Outro

### Intro (0.5s)
- Flash del logo en blanco sobre fondo café `#5C3220`
- Fade out rápido hacia el primer clip

### Outro (3s)
```
Fondo:    #F5F2EB (crema)
Logo:     centrado, negro tinta
Tagline:  "Café de especialidad para eventos"  ← Lora Italic debajo del logo
CTA:      "Cotiza tu evento →"  ← Avenir Bold, color café #5C3220
Handle:   @thecoffeecart  ← label pequeño, uppercase
```

---

## Stack recomendado

| Herramienta | Uso |
|---|---|
| **CapCut** | Edición rápida en móvil, reels del día a día |
| **Premiere Pro / DaVinci** | Reels más elaborados, color grading profesional |
| **Remotion** | Composiciones programáticas con el brand system (React) |
| **RunwayML / Seedance** | B-roll generado por IA cuando no hay tomas propias |
| **Descript** | Subtítulos automáticos on-brand |

---

## Tokens de motion

```css
/* Colores — The Coffee Cart */
--color-cafe:       #5C3220;
--color-crema:      #F5F2EB;
--color-tinta:      #0D0D0D;
--color-latte:      #9E7B65;
--color-blanco:     #FFFFFF;

/* Timing */
--duration-stagger: 0.08s;   /* entre letras/elementos */
--duration-fade:    0.4s;    /* fade in/out estándar */
--duration-whip:    0.25s;   /* corte rápido */
--duration-zoom:    7s;      /* Ken Burns sobre b-roll */
--duration-slide:   0.3s;    /* slide up de subtítulos */

/* Easings */
--ease-out: cubic-bezier(0.0, 0.0, 0.2, 1);
--ease-in-out: cubic-bezier(0.4, 0.0, 0.2, 1);
```

---

## Checklist antes de publicar

- [ ] ¿El primer frame detiene el scroll sin sonido?
- [ ] ¿Los colores respetan la paleta de marca?
- [ ] ¿El texto es legible en móvil (mínimo 32px equivalente)?
- [ ] ¿El logo aparece en el outro?
- [ ] ¿Hay CTA claro al final?
- [ ] ¿El audio es limpio o tiene música coherente con el estilo elegante?
- [ ] ¿Dura menos de 30 segundos?

---

*Última actualización: Abril 2026*
