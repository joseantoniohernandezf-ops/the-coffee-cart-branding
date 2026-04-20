# Pattern 01 — Hook / Portada

El slide más importante. Si no engancha en 1 segundo, no hay carrusel.

## Fórmula

```
[Fondo]         Azul primario (#9BBDDC) + textura papel arrugado
[Capa texto]    3-4 tipografías mezcladas, palabra clave XXL en amarillo o negro
[Capa talento]  Talento recortado (PNG) EN FRENTE del texto (layering)
[Dots]          Mockup de dots de carrusel en la parte inferior
```

## Estructura visual

```
┌─────────────────────────────────┐
│                                 │
│   [serif italic blanco]         │  ← "Ha llegado" / "Los" / "Cómo creo"
│                                 │
│   [PALABRA CLAVE XXL AMARILLA]  │  ← la palabra central del hook
│   [PALABRA CLAVE XXL AMARILLA]  │     en sans bold condensed
│                                 │
│        [TALENTO RECORTADO]  ←──────  tapa parcialmente el texto
│                                 │
│   [sans blanco pequeño]         │  ← subtítulo corto que promete valor
│                                 │
│    ● ● ● ● ○ ○ ○ ○              │  ← dots de carrusel
└─────────────────────────────────┘
```

## Specs técnicas

| Elemento | Detalle |
|----------|---------|
| Ratio | 4:5 (1080 × 1350 px) |
| Fondo | Azul primario `#9BBDDC` + papel arrugado overlay |
| Script italic | Playfair Display Italic 80-100pt, blanco roto `#FAF8F3` |
| Keyword XXL | Sans Bold Condensed (Archivo Black / Druk Wide) 180-240pt, amarillo `#E8C547` |
| Talento | PNG recortado, h = 60-75% del slide, posición derecha/centro |
| Subtítulo | Sans 28-36pt, blanco roto `#FAF8F3` |
| Dots | Mini círculos blancos (5-8), 12-16px diámetro, abajo centrado |

## Variantes

### Variante A — Script + Keyword (la más común)
```
Script italic:  [frase introductoria corta 2-3 palabras]
Keyword XXL:    [PALABRA CLAVE 1-2 PALABRAS]
Sub:            [promesa corta]
```

### Variante B — Provocación + Amarillo
```
Keyword XXL:    [FRASE PROVOCADORA]
Sub:            [por qué / explicación corta]
Extra:          mockups con washi tape + flecha "→"
```

### Variante C — Mix tipografías en línea
```
Script cursiva: [conector]
Keyword mix:    [FRASE con palabras en azul + negro + azul alternados]
Sub:            [teaser que invita a deslizar >>>]
```

## Reglas obligatorias

1. **Talento siempre aparece** en la portada (recortado PNG)
2. **Mezclar 3-4 tipografías** (nunca una sola)
3. **Una palabra clave grande** en amarillo o negro, NO todo el título grande
4. **Texto detrás del talento** (layering) → siempre
5. **Dots de carrusel** visibles abajo

## Qué evitar

- ❌ Portada minimalista con mucho blanco
- ❌ Título en una sola fuente
- ❌ Talento sin layering (delante sobre fondo plano)
- ❌ Foto stock en lugar del talento real
- ❌ Sin textura de papel

## Prompt para Claude Design / IA

> Portada de carrusel vertical 4:5 para Instagram. Fondo azul claro #9BBDDC con textura de papel arrugado. Título mezclando 3 tipografías: una frase corta en script italic blanco arriba, luego la palabra clave en sans bold condensed ultra gigante en amarillo mostaza #E8C547 ocupando 60% del ancho, y subtítulo pequeño en sans blanco debajo. Talento recortado en PNG sin fondo colocado EN FRENTE del texto, tapándolo parcialmente, pose sentado o de pie. Dots de carrusel al pie.
