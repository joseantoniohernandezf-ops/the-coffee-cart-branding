# Pattern 04 — Comparativa "MAL SISTEMA vs BUEN SISTEMA"

Slide de contraste. Muestra el problema y la solución. Patrón muy efectivo para didactizar.

## Fórmula

```
[Fondo]          Beige papel + textura
[Bloque 1]       "MAL SISTEMA" + cruz + ejemplo malo
[Bloque 2]       "BUEN SISTEMA" + check + lista de elementos buenos
```

## Estructura visual

```
┌─────────────────────────────────┐
│ MAL SISTEMA                     │  ← sans bold condensed negro
│ ✗ [frase del problema]          │  ← cruz a mano + texto
│   ┌────────────────┐            │
│   │ screenshot mal │ ← washi    │
│   └────────────────┘            │
│                                 │
│ BUEN SISTEMA                    │  ← sans bold condensed negro
│ ✓ [frase solución]              │  ← check a mano + texto
│   ↓                             │
│     • [punto 1]                 │  ← lista con bullets azules
│     • [punto 2]                 │
│     • [punto 3]                 │
│     • [punto 4]                 │
│     • [punto 5]                 │
└─────────────────────────────────┘
```

## Specs

| Elemento | Detalle |
|----------|---------|
| Ratio | 4:5 |
| Fondo | Beige papel `#F5F0E8` + textura |
| Headers "MAL/BUEN SISTEMA" | Sans bold condensed 60-72pt negro |
| Cruz ✗ | PNG sticker manuscrito azul primario |
| Check ✓ | PNG sticker manuscrito azul primario |
| Frase problema | Handwritten 36pt negro |
| Bullets | Sans bold condensed 36-44pt negro, con círculos azules |
| Separación bloques | 80-120px vertical |

## Claves del estilo

- **Cruz y check a mano** (no Unicode), azul primario
- **Bullets circulares azul primario** (no rayas ni guiones)
- **Handwritten** para las frases explicativas del problema
- **Sans bold condensed** para los items de la lista (más formal y legible)

## Ejemplo estructural

```
MAL SISTEMA
✗ [descripción del antipatrón en 1-2 líneas]
  [screenshot de un ejemplo mal hecho]

BUEN SISTEMA
✓ [descripción del patrón correcto en 1-2 líneas]
  ↓
    • [característica 1]
    • [característica 2]
    • [característica 3]
    • [característica 4]
    • [característica 5]
```

## Prompt para IA

> Slide 4:5. Fondo beige papel #F5F0E8 con textura arrugada. Divide el slide en dos bloques verticales. Bloque superior "MAL SISTEMA" en sans bold condensed negro grande, con una cruz dibujada a mano en azul #9BBDDC al lado, y una frase manuscrita estilo Caveat describiendo el problema. Debajo, un screenshot con washi tape mostrando un ejemplo del problema. Bloque inferior "BUEN SISTEMA" en sans bold condensed negro, check dibujado a mano azul, frase manuscrita de solución, y una lista de 5 bullets circulares azul primario con texto sans bold condensed negro 40pt.
