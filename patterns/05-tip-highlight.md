# Pattern 05 — Tip destacado

Slide corto con un consejo práctico y un visual de apoyo (grid de imágenes, ejemplo).

## Fórmula

```
[Fondo]        Beige papel + textura
[Visual]       Grid 3x3 de imágenes (o imagen grande de ejemplo)
[Etiqueta TIP] "TIP" en serif italic grande
[Flecha]       Flecha manuscrita apuntando al consejo
[Consejo]      Handwritten + clave entre palabras
```

## Estructura visual

```
┌─────────────────────────────────┐
│                                 │
│   ┌──┬──┬──┐                    │
│   │  │  │  │                    │  ← grid 3x3 de imágenes
│   ├──┼──┼──┤     ← washi tape   │    (ejemplo del output)
│   │  │  │  │                    │
│   ├──┼──┼──┤                    │
│   │  │  │  │                    │
│   └──┴──┴──┘                    │
│                                 │
│  [TIP] serif italic →           │  ← "TIP →"
│                                 │
│  [handwritten: consejo clave]   │  ← consejo en 1-2 líneas
│                                 │
└─────────────────────────────────┘
```

## Specs

| Elemento | Detalle |
|----------|---------|
| Ratio | 4:5 |
| Fondo | Beige papel `#F5F0E8` + textura |
| Grid / imagen | Centrado, 70-80% ancho, washi tapes |
| "TIP" | Serif italic bold (Playfair Italic) 80-100pt negro |
| Flecha arrow | Unicode → o PNG sticker manuscrito |
| Consejo | Handwritten 32-40pt negro, palabras clave en cursiva o negrita |

## Variantes

- **Tip sobre prompt** → imagen de un prompt + consejo
- **Tip sobre formato** → grid de imágenes + consejo sobre aspect ratio
- **Tip sobre herramienta** → screenshot + consejo sobre setting

## Prompt para IA

> Slide 4:5. Fondo beige papel con textura. En el centro-superior una imagen grande o grid de 9 imágenes en formato 3x3, pegada con 2 washi tapes beige, ligera rotación. Debajo del grid, la palabra "TIP" en serif italic grande (Playfair) negro, seguida de una flecha manuscrita. Debajo, el consejo completo en handwritten Caveat 36pt negro, con 1-2 palabras clave en cursiva para resaltar.
