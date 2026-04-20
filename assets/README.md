# Assets

Todos los recursos visuales del sistema de marca. Esta plantilla viene con la estructura vacía —
añade tus propios archivos.

## Estructura

```
assets/
├── logos/               ← tus logos vectoriales (SVG preferente)
│   ├── logo-white.svg
│   ├── logo-black.svg
│   ├── logo-iso.svg
│   └── brand-guidelines.pdf
│
├── texturas/            ← overlays y fondos
│   ├── papel-arrugado-beige.png         (2000x2500)
│   ├── papel-arrugado-azul.png          (tinted al color primario)
│   ├── grain.png                        (film grain overlay)
│   └── papel-arrugado-transparent.png   (solo textura, aplicar sobre cualquier color)
│
├── stickers/            ← elementos pegados a mano
│   ├── washi-tape-beige-01.png
│   ├── washi-tape-beige-02.png
│   ├── washi-tape-beige-03.png          (varios ángulos de rotación)
│   ├── drip-azul.png
│   ├── drip-amarillo.png
│   ├── flecha-curva-01.png
│   ├── flecha-curva-02.png
│   ├── flecha-recta-01.png
│   ├── circulo-mano.png
│   ├── check-mano.png
│   └── cruz-mano.png
│
└── mockups/             ← screenshots limpios de plataformas
    ├── chatgpt-interface.png
    ├── instagram-post-frame.png
    └── instagram-carousel-dots.png
```

## Formato

- **Logos**: SVG (vectorial)
- **Texturas**: PNG con transparencia, 2000x2500px mínimo, 300dpi
- **Stickers**: PNG con transparencia, tamaños variables
- **Mockups**: PNG limpio, sin datos personales, sin branding de otros

## Naming convention

- `{categoria}-{descripcion}-{variante}.{ext}`
- Todo en minúsculas, sin espacios, separado por guiones
- Variantes numeradas: `-01`, `-02`...

## Fuentes para conseguir assets

- **Texturas papel**: Craft Supply Co, Creative Market (buscar "crumpled paper")
- **Grano fotográfico**: RGRA Film Grain, FilmSupply
- **Washi tape**: Creative Market o crear en Figma con rectángulos + ruido
- **Flechas manuscritas**: Freepik (buscar "hand drawn arrows")
- **Stickers handwritten**: crear en Procreate/iPad + exportar PNG
