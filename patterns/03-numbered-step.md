# Pattern 03 — Paso numerado (PASO 1, PASO 2, PASO 3, PASO 4)

Los slides centrales del carrusel. Se repiten con la misma estructura cambiando número y contenido.

## Fórmula

```
[Fondo]            Beige papel (#F5F0E8) + textura arrugada
[Número]           "PASO 1" en graffiti azul gigante arriba-izquierda
[Título]           Frase acción en sans bold condensed negro
[Visual]           Screenshot / mockup de lo que hay que hacer (con washi tape)
[Anotaciones]      Handwritten + flechas explicando detalles
```

## Estructura visual

```
┌─────────────────────────────────┐
│                                 │
│  [PASO 1] ← graffiti azul XXL   │
│                                 │
│  [TÍTULO EN SANS BOLD NEGRO]    │  ← acción concreta del paso
│  [subtítulo casual entre parén] │  ← "(al final te digo cómo...)"
│                                 │
│    ┌──────────────────────┐     │
│    │                      │     │
│    │   SCREENSHOT / UI    │  ← washi tape
│    │                      │     │
│    └──────────────────────┘     │
│        ↓  ↓  ↓                  │  ← flechas manuscritas
│   [anotación] [anotación]       │  ← handwritten explicando campos
│                                 │
└─────────────────────────────────┘
```

## Specs

| Elemento | Detalle |
|----------|---------|
| Ratio | 4:5 |
| Fondo | Beige papel `#F5F0E8` + textura |
| "PASO N" | Display graffiti **azul primario** `#9BBDDC`, 140-180pt, con efecto drip al pie |
| Título de paso | Sans bold condensed negro, 44-56pt, mayúsculas |
| Subtítulo casual | Handwritten casual 28-32pt negro entre paréntesis |
| Screenshot/UI | Centrado, 70-80% ancho, sombra sutil, washi tapes |
| Flechas | Manuscritas negras apuntando a elementos |
| Anotaciones | Handwritten 32-40pt negro |

## Claves del estilo

1. **Número grande** siempre en graffiti azul con drip
2. **Ajustar a mano la interfaz** con flechas curvas y círculos
3. **Texto explicativo en handwritten** (no en sans limpia)
4. **Washi tapes en las esquinas** del screenshot

## Variantes típicas

- **PASO 1**: setup / "RELLENA TU INFO" / "PREPARA X"
- **PASO 2**: research / "ANALIZA LO QUE FUNCIONA"
- **PASO 3**: acción / "CREA" / "GENERA"
- **PASO 4**: finalización / "EDITA / PUBLICA"

## Prompt para IA

> Slide 4:5. Fondo beige papel #F5F0E8 con textura arrugada. Arriba-izquierda la etiqueta "PASO 1" en tipografía graffiti stencil XXL color azul #9BBDDC con efecto drip/pintura goteando debajo. Justo debajo, el título de la acción en sans bold condensed mayúsculas negro 50pt. Si hay subtítulo, en handwritten Caveat entre paréntesis. En el centro del slide, un screenshot limpio de la interfaz con 2-3 washi tapes beige en las esquinas y rotación sutil. A la derecha o debajo del screenshot, flechas curvas dibujadas a mano que apuntan a elementos concretos del screenshot, con anotaciones handwritten explicando qué es cada campo.
