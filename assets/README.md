# Assets · The Coffee Cart

Todos los recursos visuales del sistema de marca. Estructura lista — añade tus archivos
conforme los vayas produciendo o consiguiendo.

---

## Estructura

```
assets/
├── logos/               ← versiones del logo en distintos formatos y colores
│   ├── logo-negro.svg               ← logo principal sobre fondos claros
│   ├── logo-blanco.svg              ← logo sobre fondos oscuros (café, tinta)
│   ├── logo-crema.svg               ← logo sobre fondos oscuros con tono cálido
│   ├── logo-isotipo.svg             ← solo el símbolo, sin texto
│   ├── logo-horizontal.svg          ← versión horizontal si existe
│   └── logo-negro.png               ← PNG para Canva / herramientas que no leen SVG
│
├── fotografias/         ← fotos reales de eventos y producto
│   ├── bebidas/                     ← close-ups de espresso, latte art, cold brew
│   ├── setup/                       ← la barra montada en distintos eventos
│   ├── barista/                     ← el barista trabajando, ángulos recomendados
│   ├── eventos/                     ← fotos del ambiente del evento (invitados, venue)
│   └── detalles/                    ← granos, vapor, manos, texturas de café
│
├── patrones/            ← patrones SVG del sistema de marca
│   ├── patron-c.svg                 ← letra C repetida en tiling
│   ├── patron-granos.svg            ← granos de café en outline repetidos
│   ├── patron-c-preview.png         ← preview del patrón C para referencia rápida
│   └── patron-granos-preview.png    ← preview del patrón granos
│
├── overlays/            ← capas de color para aplicar sobre fotografías
│   ├── overlay-cafe-55.png          ← rgba(92,50,32,0.55) para fotos de evento
│   ├── overlay-tinta-60.png         ← rgba(13,13,13,0.60) para fotos oscuras
│   └── overlay-crema-75.png         ← rgba(245,242,235,0.75) para fotos muy oscuras
│
└── mockups/             ← frames para presentar slides
    ├── instagram-carrusel-dots.png  ← dots de carrusel PNG transparente
    ├── iphone-frame.png             ← frame de iPhone para presentaciones
    └── instagram-post-frame.png     ← marco limpio de post de Instagram
```

---

## Logos — prioridad inmediata

Estos son los archivos más importantes. Si solo tienes el PDF del brand book,
exporta desde ahí las versiones que necesitas:

| Versión | Cuándo usar |
|---|---|
| `logo-negro.svg` | Sobre fondo crema `#F5F2EB` o blanco |
| `logo-blanco.svg` | Sobre fondo café `#5C3220` o negro tinta `#0D0D0D` |
| `logo-crema.svg` | Versión cálida para slides oscuros |
| `logo-isotipo.svg` | Stories, avatares, sellos pequeños |

> Tu brand book ya tiene las variaciones. Expórtalas desde el PDF o pídele al diseñador
> los archivos SVG originales.

---

## Fotografías — guía de tomas

Para que tus fotos sean coherentes con la marca desde el principio:

### Prioridad alta (conseguir lo antes posible)
- **Close-up de latte art** — fondo neutro, luz natural lateral
- **Barista de perfil preparando espresso** — profundidad de campo
- **La barra completa en un evento** — toma lateral, setup completo
- **Manos recibiendo una taza** — POV del invitado

### Ajustes de edición coherentes con la marca
```
Temperatura:   cálida (+15 a +20) — nunca fría ni azulada
Contraste:     +10 a +15
Highlights:    -10 (sin quemar blancos)
Shadows:       +5 (mantener detalle en oscuros)
Saturación:    +5 a +10 — nunca exagerada
```

### Filtros de Lightroom recomendados
Cualquier preset de tonos cálidos y terrosos. Evitar filtros fríos, azulados o con
exceso de verde. La foto debe sentirse como la paleta: café, crema, cálido.

---

## Patrones SVG — cómo usarlos

Los dos patrones de marca (`patron-c.svg` y `patron-granos.svg`) siempre se usan
en opacidad baja como textura de fondo, nunca como elemento protagonista.

| Patrón | Opacidad recomendada | Mejor sobre |
|---|---|---|
| Patrón C | 6–10% | Fondo negro tinta (slide CTA) |
| Patrón granos | 10–15% | Fondo crema (slides de tips) |

Si no tienes los SVG, puedes crearlos en Canva con la letra "C" en tipografía de la marca
repetida en un fondo, o con la ilustración de granos de café del brand book.

---

## Overlays — cómo aplicarlos en Canva

Para poner texto sobre una foto y que sea legible:

1. Sube la foto al slide
2. Agrega un rectángulo encima del tamaño del slide completo
3. Color del rectángulo: elige el overlay según el caso
4. Opacidad del rectángulo: ajusta entre 45–65%
5. Pon el texto encima del rectángulo

| Overlay | Usar cuando |
|---|---|
| Café `#5C3220` al 55% | Foto de evento o ambiente, texto blanco encima |
| Tinta `#0D0D0D` al 60% | Cualquier foto oscura, texto crema encima |
| Crema `#F5F2EB` al 75% | Foto muy oscura donde quieres texto tinta encima |

---

## Formato y naming convention

- **Logos**: SVG preferente + PNG como respaldo
- **Fotografías**: JPG, mínimo 1080×1350px (4:5), máximo 5MB por archivo
- **Patrones**: SVG para escalar sin pérdida + PNG de preview
- **Overlays**: PNG con transparencia
- **Mockups**: PNG con transparencia, 1080×1350px

Naming: `{categoria}-{descripcion}-{variante}.{ext}`
Todo en minúsculas, sin espacios, separado por guiones. Ejemplo: `foto-barista-perfil-01.jpg`

---

## Fuentes para conseguir assets gratuitos

| Tipo | Fuente |
|---|---|
| Mockup de iPhone / Instagram | [Mockup World](https://www.mockupworld.co) — gratis |
| Fotos de café de stock | [Unsplash](https://unsplash.com/s/photos/coffee) — buscar "specialty coffee" |
| Fotos de eventos de stock | [Pexels](https://www.pexels.com) — búsqueda: "coffee event" |
| Granos de café PNG | [Freepik](https://www.freepik.com) — buscar "coffee beans png" |
| Patrones SVG personalizados | Crear en Canva o Figma con elementos del brand book |

> Siempre preferir fotos propias sobre stock. El stock puede usarse mientras
> no tengas material propio, pero reemplazarlo en cuanto tengas sesión fotográfica.

---

*The Coffee Cart · Brand System 2026*
