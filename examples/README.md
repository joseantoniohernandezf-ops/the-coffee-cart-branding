# Ejemplos aplicados

Ejemplos HTML/CSS del brand system en acción. Ábrelos en el navegador para ver cómo se aplica el sistema.

## Archivos

- **`hero-cover.html`** — Portada tipo "conector + KEYWORD + subtítulo" (pattern 01)
- **`cta-keyword.html`** — Slide final "COMENTA [KEYWORD]" (pattern 07)

## Cómo abrirlos

```bash
# Desde la raíz del repo:
open examples/hero-cover.html
open examples/cta-keyword.html
```

O arrastra el archivo al navegador.

## Qué demuestran

- Uso de `tokens/fonts.css` con variables CSS
- Google Fonts (Archivo Black, Playfair Display Italic, Caveat) — 100% free
- Aspect ratio 4:5 correcto (1080 × 1350)
- Layering: placeholder de talento delante del texto
- Paleta completa aplicada

## Fuentes premium (opcional)

Si compras Bourton + Druk Wide, en `tokens/fonts.css`:

```css
--font-display-graffiti: 'Bourton', sans-serif;
--font-sans-condensed: 'Druk Wide', sans-serif;
```

Y añades los `@font-face` con los archivos reales en `fonts/`.

## Próximos ejemplos por hacer

- [ ] `numbered-step.html` (pattern 03)
- [ ] `comparison-bad-good.html` (pattern 04)
- [ ] `tip-highlight.html` (pattern 05)
- [ ] `transition.html` (pattern 06)
- [ ] `enter-platform.html` (pattern 02)
