# effects.md — The Coffee Cart
> Efectos visuales, sombras, bordes y tratamientos de imagen.
> Mantener siempre coherencia con el estilo: elegante, limpio, profesional.

---

## Sombras

```css
/* Sombra suave — tarjetas, slides, elementos flotantes */
--shadow-soft: 0 2px 12px rgba(13, 13, 13, 0.08);

/* Sombra media — elementos destacados, CTAs */
--shadow-medium: 0 4px 24px rgba(92, 50, 32, 0.15);

/* Sombra fuerte — modales, overlays, portadas */
--shadow-strong: 0 8px 40px rgba(13, 13, 13, 0.25);

/* Sombra de texto — sobre fondos con imagen o patrón */
--shadow-text: 0 1px 4px rgba(13, 13, 13, 0.4);
```

Regla: nunca sombras de colores brillantes. Siempre derivadas del negro tinta `#0D0D0D` o del café `#5C3220`.

---

## Bordes y líneas

```css
/* Borde fino elegante — separadores, frames */
--border-thin: 1px solid #0D0D0D;

/* Borde medio — tarjetas, contenedores */
--border-medium: 2px solid #0D0D0D;

/* Borde de acento — elementos destacados */
--border-accent: 2px solid #5C3220;

/* Borde latte — detalles sutiles */
--border-subtle: 1px solid #9E7B65;

/* Radio de esquinas — The Coffee Cart es limpio, sin bordes muy redondeados */
--radius-sm: 4px;
--radius-md: 8px;
--radius-full: 9999px; /* solo para pills / badges */
```

Regla: preferir esquinas ligeramente redondeadas (`4-8px`) o completamente rectas. Nunca `border-radius` exagerado que se vea genérico.

---

## Opacidades

```css
/* Patrones de fondo — siempre en baja opacidad */
--opacity-pattern: 0.10;   /* Patrón C o granos como fondo de slide */
--opacity-overlay: 0.50;   /* Overlay oscuro sobre fotografías */
--opacity-subtle: 0.20;    /* Elementos decorativos secundarios */
--opacity-disabled: 0.40;  /* Estados deshabilitados */
```

---

## Tratamiento de imágenes / fotografías

### Overlay para fotos de eventos
Cuando uses fotos reales de eventos como fondo de slide, aplica un overlay:
- **Overlay café**: `background: rgba(92, 50, 32, 0.55)` + texto blanco encima
- **Overlay negro**: `background: rgba(13, 13, 13, 0.60)` + texto crema encima
- **Overlay crema**: `background: rgba(245, 242, 235, 0.75)` + texto tinta encima (para fotos muy oscuras)

### Filtros de imagen
```css
/* Tono cálido — aplicar a fotos de café o bebidas */
filter: sepia(15%) contrast(105%) brightness(98%);

/* Blanco y negro elegante — para fotos de ambiente o venue */
filter: grayscale(100%) contrast(110%);
```

---

## Efectos de patrón

### Patrón C (letra de Coffee)
```css
/* Como borde superior/inferior de slide */
.pattern-c-border {
  background-image: url('../assets/patrones/patron-c.svg');
  background-size: auto 48px;
  background-repeat: repeat-x;
  height: 48px;
  opacity: var(--opacity-pattern);
}

/* Como fondo completo de slide CTA */
.pattern-c-full {
  background-image: url('../assets/patrones/patron-c.svg');
  background-size: 80px auto;
  background-repeat: repeat;
  opacity: var(--opacity-pattern);
}
```

### Patrón granos de café
```css
/* Como fondo de slides de tips o educación */
.pattern-beans {
  background-image: url('../assets/patrones/patron-granos.svg');
  background-size: 100px auto;
  background-repeat: repeat;
  opacity: var(--opacity-pattern);
}
```

---

## Espaciado para slides de carrusel

```css
/* Instagram carrusel — 1080x1080px */
--slide-size: 1080px;
--slide-padding: 80px;          /* Margen interior generoso */
--slide-padding-tight: 56px;    /* Para slides con más contenido */
--element-gap: 24px;            /* Separación entre elementos */
--element-gap-lg: 40px;         /* Separación entre bloques */
```

---

## Reglas generales de estilo

1. **Menos es más** — si un elemento no aporta, no va
2. **Respiración** — siempre dejar espacio en blanco generoso, al menos `--slide-padding` por cada lado
3. **Sin gradientes complejos** — máximo un gradiente suave entre dos colores de la paleta, nunca arcoíris ni multicolor
4. **Sin efectos de glassmorphism ni neón** — no van con el estilo elegante de la marca
5. **Máximo 1 efecto de sombra visible por slide** — no apilar sombras
6. **Patrones siempre en opacidad baja** — son textura, no protagonistas

---

*Última actualización: Abril 2026*
