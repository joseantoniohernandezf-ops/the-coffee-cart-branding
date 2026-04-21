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

## Logos — archivos disponibles

> 📁 **Google Drive — Logos:**
> [Ver carpeta de logos](https://drive.google.com/drive/folders/1fHcwmsU2AiVv0FbrLZ7a-rH6e4kT9brY)
>
> Los logos **no se suben a este repo** — se mantienen en Drive y se referencian desde aquí.
> Para usar en Canva: descarga directamente desde el link de Drive.

### Archivos actuales en Drive

| Archivo | Modo | Transparencia | Uso |
|---|---|---|---|
| `logo con fondo.png` | RGBA | ✅ Sí | Logo con fondo transparente, versión principal |

### Versiones que hacen falta

| Versión | Cuándo usar | Cómo obtenerla |
|---|---|---|
| `logo-negro.png` | Sobre fondo crema `#F5F2EB` o blanco | Exportar desde Illustrator con fondo transparente |
| `logo-blanco.png` | Sobre fondo café `#5C3220` o tinta `#0D0D0D` | Cambiar color a blanco en Illustrator y exportar |
| `logo-isotipo.png` | Stories, avatares, sellos pequeños | Recortar solo el símbolo y exportar |

> Pendiente: exportar versión blanca del logo para usarla en slides oscuros (CTA, transición).
> Con Canva puedes cambiar el color del logo a blanco si lo importas como PNG transparente.

---

## Fotografías — banco de imágenes

> 📁 **Google Drive — Fotos profesionales:**
> [Ver carpeta completa](https://drive.google.com/drive/folders/1D0D-W4UO9lbH_bXfCcv-FpXJaPV9qZe1)
>
> Las fotos **no se suben a este repo** — son archivos de 8–20MB y GitHub no está
> pensado para eso. Se mantienen en Drive y se referencian desde aquí.
> Para usar con IA: comparte el link de la subcarpeta al pedir un carrusel.

### Subcarpetas en Drive

| Carpeta | Contenido | Link |
|---|---|---|
| `bebidas/` | Close-ups de bebidas siendo preparadas | — |
| `barista/` | El equipo trabajando, mandiles, máquina | — |
| `setup/` | La barra completa montada en eventos | — |
| `eventos/` | Ambiente, invitados, venue | — |

> Actualiza los links de cada subcarpeta conforme las vayas creando en Drive.

### Fotos destacadas ya catalogadas

| Archivo | Descripción | Mejor uso |
|---|---|---|
| ASG01472 | Matcha siendo vertido en vaso con logo, luz exterior cálida | Portada de carrusel / hook |
| ASG01525 | Iced latte siendo vertido, vaso con logo, fondo desenfocado | Portada o tip de bebida |
| ASG01719 | POV mano sosteniendo iced latte, lente esférico creativo | Hook aspiracional |
| ASG01425 | 3 baristas con mandil sonriendo en el evento | Slide de equipo / servicio |
| ASG01557 | Baristas trabajando en la máquina espresso | Slide de proceso |

### Guía de tomas (para próximas sesiones)

### Ajustes de edición coherentes con la marca
```
Temperatura:   cálida (+15 a +20) — nunca fría ni azulada
Contraste:     +10 a +15
Highlights:    -10 (sin quemar blancos)
Shadows:       +5 (mantener detalle en oscuros)
Saturación:    +5 a +10 — nunca exagerada
```

Para próximas sesiones, priorizar: close-up de latte art, barista de perfil preparando espresso, la barra completa montada, y manos recibiendo una taza.

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
