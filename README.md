# Brand System Template — Creadores de contenido con IA

> Plantilla abierta de sistema de marca para creadores, diseñadores y agentes de IA.
> Copia este repo, adapta los tokens a tu marca, y tendrás una fuente única de verdad
> que Claude Design, Lovable, v0, Cursor y cualquier agente puede leer para generar
> contenido on-brand automáticamente.

---

## Qué es esto

Un **sistema de marca modular** pensado para carruseles de Instagram tipo zine / collage
(estilo "cuaderno con washi tape, spray drip y fuentes mezcladas"). Pensado para:

- **Agentes de IA** (Claude Design, Lovable, v0, Cursor) — leen los tokens y patterns y generan piezas consistentes
- **Diseñadores freelance** — entran al proyecto y pillan el tono en 10 minutos
- **Creadores** que quieren dejar de tener la marca solo en su cabeza

El documento maestro es **[`DESIGN.md`](./DESIGN.md)**. Si alguien solo puede leer un archivo, que sea ese.

---

## Cómo usarlo

### 1. Clona / usa como template

```bash
git clone <este-repo> mi-brand-system
cd mi-brand-system
```

O haz click en **"Use this template"** en GitHub.

### 2. Adapta los tokens

Edita:

- `tokens/colors.json` — cambia los hex a tu paleta
- `tokens/typography.json` — cambia las fuentes
- `tokens/effects.md` — ajusta lo que no encaje con tu estilo

### 3. Personaliza los patterns

Los patterns (`patterns/01…07`) son plantillas de slide. Úsalos como base, edita
los textos y estructura a tu gusto.

### 4. Conéctalo a un agente de IA

- **Claude Design**: conecta el repo en el onboarding. El agente leerá automáticamente `DESIGN.md`, `tokens/*`, `patterns/*`.
- **Otro agente (v0, Lovable, etc.)**: pásale el contenido de `DESIGN.md` en el prompt. Con eso basta.

---

## Estructura

```
brand-system-template/
├── DESIGN.md                          ← MASTER (leer primero)
├── README.md                          ← este archivo
│
├── tokens/                            ← design tokens
│   ├── colors.json
│   ├── typography.json
│   ├── effects.md
│   └── fonts.css                      ← CSS listo para web
│
├── fonts/                             ← archivos de fuente (.woff2 / .ttf)
│   └── README.md
│
├── patterns/                          ← 7 plantillas de slide
│   ├── 01-hook-cover.md
│   ├── 02-enter-platform.md
│   ├── 03-numbered-step.md
│   ├── 04-comparison-bad-good.md
│   ├── 05-tip-highlight.md
│   ├── 06-transition.md
│   └── 07-cta-keyword.md
│
├── carruseles/
│   └── README.md                      ← estructura para guardar tus top-performers
│
├── assets/
│   ├── logos/                         ← tus logos vectoriales
│   ├── texturas/                      ← papel, grano, spray
│   ├── stickers/                      ← flechas, drips, washi tape
│   └── mockups/                       ← frames limpios de plataformas
│
├── examples/                          ← HTML/CSS demos
│   ├── hero-cover.html
│   └── cta-keyword.html
│
└── reels/
    └── README.md                      ← estilo motion (pendiente de documentar)
```

---

## Quick reference — Paleta de ejemplo

Esta plantilla viene con una paleta azul+amarillo como punto de partida. Cámbiala por la tuya.

| Color | Hex | Uso |
|-------|-----|-----|
| Azul primario | `#9BBDDC` | Fondos CTA, portadas, bloques destacados |
| Amarillo acento | `#E8C547` | Palabras clave, énfasis |
| Negro tinta | `#1A1A1A` | Texto sobre fondos claros |
| Beige papel | `#F5F0E8` | Fondo alternativo tipo "cuaderno" |
| Blanco roto | `#FAF8F3` | Texto sobre fondos oscuros |

> Regla: **nunca `#000000` ni `#FFFFFF` puros**. Siempre un pelín cálidos.

---

## Quick reference — Tipografías (Google Fonts, 100% free)

| Rol | Fuente free | Alternativa premium |
|-----|-------------|---------------------|
| Display graffiti | Rubik Mono One | Bourton / Boucherie |
| Serif italic | Playfair Display Italic | Domaine Display Italic |
| Sans bold condensed | Archivo Black / Anton | Druk Wide Bold |
| Handwritten | Caveat Bold | — |
| Body | Inter | Manrope / DM Sans |

Todo listo en `tokens/fonts.css` — importa ese archivo y tira.

---

## Quick reference — Estructura de carrusel (10-11 slides)

```
1.  Hook / portada (palabra clave XXL + talento recortado)
2.  Contexto ("Vete a / Entra en" + screenshot)
3.  Paso 1
4.  Paso 2
5.  Paso 3
6.  Paso 4 (opcional)
7.  Comparativa (Mal sistema vs Buen sistema)
8.  Tip destacado
9.  Transición (solo texto sobre color)
10. CTA (keyword entre comillas)
11. Firma / cierre (opcional)
```

Detalle de cada tipo en `patterns/`.

---

## Licencia

MIT — úsalo, modifícalo, compártelo.

Si te ha servido, menciona al repo original. No es obligatorio, pero se agradece.

---

*Última actualización: 2026-04-20*
