# Fonts

Archivos de fuente del sistema. Organizar por rol.

## Estructura esperada

```
fonts/
├── display-graffiti/
│   ├── Bourton-Base.woff2
│   ├── Bourton-Drip.woff2
│   └── LICENSE.txt
├── serif-italic/
│   ├── PlayfairDisplay-Italic.woff2
│   └── PlayfairDisplay-BoldItalic.woff2
├── sans-condensed/
│   ├── DrukWide-Bold.woff2
│   └── ArchivoBlack-Regular.woff2     ← alternativa free
├── handwritten/
│   ├── Caveat-Bold.woff2
│   └── Caveat-Regular.woff2
└── body/
    ├── Inter-Regular.woff2
    ├── Inter-Medium.woff2
    └── Inter-Bold.woff2
```

## Recomendaciones de compra

Fuentes premium que vale la pena comprar:
- **Bourton** (display graffiti) — Set & Sequence
- **Druk Wide** (condensed pesada) — Commercial Type
- **Domaine Display** (serif elegante) — Klim Type Foundry

## Fuentes free equivalentes

Si no hay presupuesto, estas sustituyen bien:
- Graffiti → **Rubik Mono One** (Google Fonts) + efecto drip aplicado con SVG
- Serif italic → **Playfair Display Italic** (Google Fonts) — IDÉNTICA calidad
- Sans condensed → **Archivo Black** o **Anton** (Google Fonts)
- Handwritten → **Caveat** (Google Fonts) — perfecta

## Licencias

Guardar LICENSE.txt junto a cada fuente. Respetar derechos de uso según cada foundry.

> **Importante:** si subes este repo a GitHub como público, NO subas fuentes premium
> (Bourton, Druk Wide, Domaine). Usa `.gitignore` para excluirlas. Solo se pueden
> versionar fuentes con licencia de redistribución libre (Google Fonts / SIL OFL).

## Cargar en web / app

```css
@font-face {
  font-family: 'Bourton';
  src: url('./fonts/display-graffiti/Bourton-Base.woff2') format('woff2');
  font-weight: 900;
  font-style: normal;
  font-display: swap;
}
```
