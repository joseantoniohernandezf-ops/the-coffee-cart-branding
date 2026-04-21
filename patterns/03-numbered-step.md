# Pattern 03 — Punto numerado (PUNTO 1, PUNTO 2, PUNTO 3...)

Los slides centrales del carrusel. Se repiten con la misma estructura cambiando número y contenido.

## Fórmula

```
[Fondo]            Crema (#F5F2EB) o Blanco (#FFFFFF)
[Número]           "01" o "PUNTO 1" en Avenir Black gigante, color latte o café
[Título]           Beneficio o elemento del servicio en Avenir Black negro
[Visual]           Foto del momento o elemento descrito
[Apoyo]            Lora Italic con frase complementaria
```

## Estructura visual

```
┌─────────────────────────────────┐
│                                 │
│  [01] ← Avenir Black latte XXL  │  ← número grande arriba-izquierda
│                                 │
│  [TÍTULO DEL PUNTO EN NEGRO]    │  ← beneficio o elemento, 2-3 palabras
│  [Lora Italic de apoyo]         │  ← frase que amplía el título
│                                 │
│    ┌──────────────────────┐     │
│    │                      │     │
│    │   FOTO / VISUAL      │     │  ← imagen del momento descrito
│    │                      │     │
│    └──────────────────────┘     │
│                                 │
│   [Avenir Regular descripción]  │  ← 1-2 líneas explicando el punto
│                                 │
└─────────────────────────────────┘
```

## Specs

| Elemento | Detalle |
|---|---|
| Ratio | 4:5 |
| Fondo | Crema `#F5F2EB` o Blanco `#FFFFFF` |
| Número "01" | Avenir Black / Nunito 900, 120-160pt, latte `#9E7B65` |
| Título del punto | Avenir Black, 44-56pt, negro tinta `#0D0D0D`, mayúsculas |
| Lora Italic | 26-32pt, café `#5C3220` |
| Foto | 65-75% ancho, centrada |
| Descripción | Avenir Regular 20-24pt, negro tinta |

## Ejemplos por tipo de carrusel

### Carrusel de servicio — ¿Qué incluye The Coffee Cart?
* **PUNTO 01** — BARISTA CERTIFICADO / *"que conoce cada bebida"*
* **PUNTO 02** — EQUIPO PROFESIONAL / *"llevamos todo, tú no cargas nada"*
* **PUNTO 03** — CAFÉ DE ORIGEN / *"granos seleccionados, no mezclas genéricas"*
* **PUNTO 04** — MENÚ PERSONALIZADO / *"diseñamos el menú para tu evento"*

### Carrusel de tips — Café de especialidad 101
* **PUNTO 01** — EL ORIGEN IMPORTA / *"no todo el café sabe igual"*
* **PUNTO 02** — LA EXTRACCIÓN / *"espresso, pour over, cold brew — cada uno cuenta"*
* **PUNTO 03** — LA TEMPERATURA / *"el café malo siempre está quemado"*

### Carrusel de evento — Cómo funciona contratarnos
* **PASO 01** — NOS CONTACTAS / *"cuéntanos de tu evento"*
* **PASO 02** — DISEÑAMOS TU MENÚ / *"adaptado a tus invitados"*
* **PASO 03** — LLEGAMOS Y MONTAMOS / *"nosotros nos encargamos de todo"*

## Reglas

1. **Número siempre en latte `#9E7B65`** — nunca en negro, se confunde con el título
2. **Título siempre en mayúsculas** y Avenir Black
3. **Lora Italic siempre en minúsculas** y color café
4. **Foto coherente con el punto** — si el punto es "barista", foto de barista
5. **Máximo 2 líneas de descripción** — si necesitas más, divide en dos slides

## Prompt para Claude / IA

> Slide 4:5. Fondo crema #F5F2EB. Arriba-izquierda el número "01" en Avenir Black / Nunito 900 latte #9E7B65 ultra grande 140pt. Justo debajo, el título del punto en Avenir Black mayúsculas negro tinta 50pt en 1-2 líneas. Debajo del título, una frase corta en Lora Italic café #5C3220 30pt. En el centro, una foto limpia del elemento descrito ocupando 70% del ancho. Al pie, 1-2 líneas de descripción en Avenir Regular negro tinta 22pt. Estilo elegante, limpio, mucho espacio en blanco.

---

*The Coffee Cart · Brand System 2026*
