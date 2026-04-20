# Pattern 06 — Transición (texto corto sobre color)

Slide de transición entre la parte teórica y la práctica. Casi siempre es solo texto sobre fondo de color.

## Fórmula

```
[Fondo]           Azul primario sólido + textura papel
[Texto mixto]     Mezcla de sans bold + palabra clave amarilla XXL
```

## Estructura visual

```
┌─────────────────────────────────┐
│                                 │
│                                 │
│    [CONECTOR]    [VERBO]        │  ← sans bold condensed blanco
│        [CONECTOR]               │
│                                 │
│         [KEYWORD]               │  ← sans bold condensed XXL amarillo
│                                 │
│                                 │
│                                 │
└─────────────────────────────────┘
```

## Specs

| Elemento | Detalle |
|----------|---------|
| Ratio | 4:5 |
| Fondo | Azul primario `#9BBDDC` sólido + textura papel |
| Texto contexto | Sans bold condensed blanco roto 80-100pt, distribuido |
| Palabra clave | Sans bold condensed **amarillo acento** 240-300pt, centrada |
| Disposición | Palabras sueltas separadas con aire, no compactas |

## Ejemplos estructurales

- **"AHORA VAMOS A DARLE [X]"** ([X] en amarillo XXL)
- **"DEBES HACER [ESTO]"** ([ESTO] en amarillo XXL)
- **"COMENTA [KEYWORD]"** ([KEYWORD] en amarillo XXL)

## Claves

- **Casi zero elementos** — solo texto sobre fondo
- **Mucho aire** alrededor del texto
- **Palabra clave domina** visualmente (80% del tamaño)
- **Textura de papel** siempre presente (no fondo plano)

## Prompt para IA

> Slide 4:5. Fondo azul primario #9BBDDC sólido con textura sutil de papel arrugado superpuesta. Texto principal dispuesto en varias líneas: primero palabras en blanco roto en sans bold condensed 100pt, luego la palabra clave central en amarillo mostaza #E8C547 sans bold condensed ULTRA gigante (250pt o más), dominando el slide. Mucho aire alrededor del texto, composición minimalista. Sin imágenes ni screenshots.
