# Pattern 02 — Contexto / "Vete a / Entra en"

Segundo slide del carrusel. Lleva al usuario a la herramienta o pantalla donde empieza la acción.

## Fórmula

```
[Fondo]           Beige papel (#F5F0E8) + textura arrugada
[Headline]        "VETE A" / "ENTRA EN" en graffiti azul arriba-izquierda
[Screenshot]      Captura de la plataforma con washi tape en las esquinas
[Etiqueta]        Nombre de la plataforma en serif italic + flecha manuscrita apuntando
[Subtítulo]       Handwritten en negro explicando qué hacer
```

## Estructura visual

```
┌─────────────────────────────────┐
│ [GRAFFITI AZUL]                 │  ← "VETE A" / "ENTRA EN"
│                                 │
│    ┌───────────────┐            │
│    │  SCREENSHOT   │ ← washi    │
│    │   [plataforma]│   tape     │
│    │               │   en       │
│    │               │   esquinas │
│    └───────────────┘            │
│           ↓                     │  ← flecha manuscrita
│      [PLATAFORMA]               │  ← serif italic (nombre tool)
│                                 │
│  [handwritten]                  │  ← "ve a [acción]"
│                                 │
└─────────────────────────────────┘
```

## Specs

| Elemento | Detalle |
|----------|---------|
| Ratio | 4:5 (1080 × 1350 px) |
| Fondo | Beige papel `#F5F0E8` + papel arrugado |
| Headline "VETE A" | Display graffiti azul primario, 100-140pt |
| Screenshot | Ancho 70-80% del slide, centrado. Sombra sutil |
| Washi tape | 2-3 piezas en esquinas del screenshot, rotación ±8deg |
| Nombre plataforma | Serif italic negro/azul, 56-80pt |
| Flecha manuscrita | PNG sticker curvada, apunta de "VETE A" al screenshot |
| Subtítulo handwritten | Caveat 32-40pt negro |

## Ejemplos de headline

- **"ENTRA en [PLATAFORMA]"**
- **"VETE A [PLATAFORMA]"**
- **"ABRE [PLATAFORMA]"**
- **"BÚSCATE [PLATAFORMA]"**

## Prompt para IA

> Slide vertical 4:5. Fondo beige papel #F5F0E8 con textura arrugada. Arriba a la izquierda, la frase "VETE A" o "ENTRA EN" en tipografía graffiti stencil grande azul #9BBDDC con efecto drip. En el centro un screenshot limpio de [PLATAFORMA] con 2-3 washi tapes beige pegándolo en las esquinas, ligeramente rotados. Debajo, el nombre de la plataforma en serif italic (tipo Playfair) y una flecha curva dibujada a mano apuntando desde el texto al screenshot. Pie de slide con anotación handwritten estilo Caveat explicando la acción siguiente.
