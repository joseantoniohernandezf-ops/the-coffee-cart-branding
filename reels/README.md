# Reels — Estilo motion

*Pendiente de documentar.*

## Qué debería ir aquí

Una vez tengas un estilo motion consistente, documenta aquí:

- [ ] Tipografías y animaciones signature (kinetic typography, fade in, stagger)
- [ ] Transiciones típicas (glitch, zoom, corte seco, whip pan)
- [ ] Estilo de b-roll (colores, filtros, grano)
- [ ] Estructura de tutoriales (hook → intro → pasos → outro → CTA)
- [ ] Cards / overlays con el brand system aplicado
- [ ] Intro/outro templates

## Stack recomendado

- **Remotion** — para composiciones programáticas (React)
- **CapCut / Premiere** — para edición rápida
- **Seedance / RunwayML** — para b-roll generado por IA

## Tokens reutilizables en motion

```css
/* Mismas variables que tokens/fonts.css */
--color-azul-primario: #9BBDDC;
--color-amarillo-acento: #E8C547;
--color-negro-tinta: #1A1A1A;

/* Timing recomendado */
--duration-stagger: 0.08s;  /* entre letras/elementos */
--duration-fade: 0.4s;       /* fade in/out standard */
--duration-whip: 0.25s;      /* corte rápido */
```
