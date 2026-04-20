# Carruseles — Tus referencias reales

Carpeta pensada para guardar los carruseles que ya has publicado y los que te inspiran.
Ayuda a la IA a tener contexto visual de lo que SÍ te funciona.

## Estructura sugerida

```
carruseles/
├── top-performers/            ← los tuyos que mejor funcionaron
│   └── AAAA-MM-tema/
│       ├── slides/
│       │   ├── 01.png
│       │   ├── 02.png
│       │   └── ...
│       ├── meta.md            ← métricas + copy + aprendizajes
│       └── notion-link.md     ← si hay más info en Notion (opcional)
│
├── referencias-externas/      ← carruseles de otros que te inspiran
│   └── @creator/
│       ├── 2026-03-tema.png
│       └── meta.md            ← por qué te gusta, qué replicar
│
└── plantillas-figma/          ← .fig descargables (cuando existan)
    ├── portada-hook.fig
    ├── paso-numerado.fig
    └── cta-keyword.fig
```

## Cómo añadir un carrusel top-performer

1. Crear carpeta `AAAA-MM-tema` (ej: `2026-03-ejemplo-viral`)
2. Volcar los slides en `slides/` numerados (01.png, 02.png…)
3. Crear `meta.md` con esta plantilla:

```markdown
# [Tema del carrusel]

**Fecha publicación:** 2026-XX-XX
**URL Instagram:** https://www.instagram.com/p/XXX
**Alcance:** X views
**Likes:** X
**Comentarios:** X (keyword: "X")
**Guardados:** X
**Compartidos:** X

## Copy del post
[Texto completo del caption]

## Hook utilizado
[Frase exacta del slide 1]

## Por qué funcionó
- Razón 1
- Razón 2
- Razón 3

## Qué replicaría / mejoraría
- ...
```

## Por qué importa tener referencias

Los agentes de IA (Claude Design, Lovable, v0) generan MUCHO mejor cuando tienen
ejemplos visuales de lo que SÍ te funciona. Con 5-10 top performers bien documentados,
ya pueden replicar tu estilo con fidelidad.
