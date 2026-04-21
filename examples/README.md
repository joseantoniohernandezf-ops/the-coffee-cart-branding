# Ejemplos aplicados · The Coffee Cart

Ejemplos HTML/CSS del brand system en acción. Ábrelos directamente en el navegador para
ver cómo se aplica el sistema de marca con tus colores y tipografías reales.

## Archivos

* **`hero-cover.html`** — Portada tipo "apoyo Lora + KEYWORD + subtítulo" (pattern 01)
* **`cta-keyword.html`** — Slide final de cotización con Lora Italic (pattern 07)

## Cómo abrirlos

Arrastra cualquiera de los archivos `.html` al navegador, o desde terminal:

```bash
# Mac
open examples/hero-cover.html
open examples/cta-keyword.html

# Windows
start examples/hero-cover.html
start examples/cta-keyword.html
```

## Qué demuestran

* Uso de la paleta completa de The Coffee Cart (café, crema, latte, tinta)
* Tipografías: Nunito 900 como sustituto de Avenir Black + Lora Italic — cargadas desde Google Fonts
* Aspect ratio 4:5 correcto (en producción = 1080 × 1350px)
* Patrón C de marca como textura de fondo en el slide CTA (opacidad 6%)
* Variables CSS listas para copiar a otros slides

## Variables CSS del sistema

```css
:root {
  /* Colores */
  --color-cafe:   #5C3220;   /* principal */
  --color-crema:  #F5F2EB;   /* fondo alternativo */
  --color-latte:  #9E7B65;   /* acento cálido */
  --color-tinta:  #0D0D0D;   /* textos y fondos oscuros */
  --color-blanco: #FFFFFF;   /* blanco puro */

  /* Tipografías */
  --font-display: 'Avenir', 'Nunito', sans-serif;
  --font-serif:   'Lora', Georgia, serif;
  --font-body:    'Avenir', 'DM Sans', sans-serif;
}
```

## Fuentes premium (Avenir real)

Si tienes Adobe Creative Cloud, activa Avenir desde Adobe Fonts. Para usarla en HTML:

```css
/* Reemplazar en el @import de cada HTML */
@import url('https://use.typekit.net/[tu-kit-id].css');

:root {
  --font-display: 'avenir', sans-serif;
  --font-body:    'avenir', sans-serif;
}
```

## Próximos ejemplos por hacer

* `context.html` — Slide de contexto/problema (pattern 02)
* `numbered-point.html` — Punto numerado (pattern 03)
* `comparison.html` — Sin TCC vs Con TCC (pattern 04)
* `tip-highlight.html` — Tip destacado (pattern 05)
* `transition.html` — Frase aspiracional (pattern 06)

---

*The Coffee Cart · Brand System 2026*
