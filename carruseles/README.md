# Carruseles · The Coffee Cart

Carpeta para guardar los carruseles publicados y las referencias que te inspiran.
Mientras más llenes esta carpeta con carruseles reales y sus métricas, mejor contexto
tendrá la IA para replicar lo que SÍ funciona para tu marca.

---

## Estructura

```
carruseles/
├── top-performers/            ← los tuyos que mejor funcionaron
│   └── AAAA-MM-tema/
│       ├── slides/
│       │   ├── 01.png
│       │   ├── 02.png
│       │   └── ...
│       └── meta.md            ← métricas + copy + aprendizajes
│
├── referencias-externas/      ← carruseles de otras marcas que te inspiran
│   └── @cuenta/
│       ├── captura.png
│       └── meta.md            ← por qué te gusta, qué replicar
│
└── plantillas/                ← archivos de Canva o Figma reutilizables
    ├── portada-hook.png       ← captura del template
    └── cta-cotiza.png
```

---

## Cómo documentar un carrusel publicado

1. Crear carpeta con formato `AAAA-MM-tema` dentro de `top-performers/`
   - Ejemplo: `2026-05-que-incluye-tcc`
2. Guardar los slides en `slides/` numerados: `01.png`, `02.png`...
3. Crear un archivo `meta.md` con esta plantilla:

```markdown
# [Tema del carrusel]

**Fecha publicación:** 2026-XX-XX
**URL Instagram:** https://www.instagram.com/p/XXX
**Tipo:** servicio / tips / evento / comparativa

## Métricas (llenar 7 días después de publicar)
- **Alcance:** X personas
- **Likes:** X
- **Comentarios:** X
- **Guardados:** X
- **Compartidos:** X
- **Visitas al perfil:** X

## Copy del caption
[Texto completo que pusiste en el post]

## Hook del slide 1
[Frase exacta de la portada]

## Por qué funcionó (o no)
-
-
-

## Qué replicaría en el próximo
-
-
```

---

## Tipos de carrusel a publicar

Basado en los contenidos definidos en `DESIGN.md`:

| # | Tipo | Frecuencia sugerida | Status |
|---|---|---|---|
| 1 | Mostrar el servicio | 1 vez al mes | ⬜ pendiente |
| 2 | Tips de café de especialidad | 2 veces al mes | ⬜ pendiente |
| 3 | Caso de evento real | Cuando tengas material | ⬜ pendiente |
| 4 | Comparativa Sin TCC vs Con TCC | 1 vez al mes | ⬜ pendiente |

> Actualiza el Status a ✅ cuando tengas al menos 1 publicado de cada tipo.

---

## Referencias externas — qué documentar

Cuando veas un carrusel de otra marca o negocio de café/eventos que te llame la atención,
guárdalo aquí con una nota de por qué te gustó. Esto ayuda a la IA a entender tu gusto
visual más allá de los tokens.

Plantilla de `meta.md` para referencias:

```markdown
# [Nombre o descripción del carrusel]

**Cuenta:** @cuenta
**URL:** https://www.instagram.com/p/XXX
**Fecha que lo encontré:** 2026-XX-XX

## Por qué me gusta
-
-

## Qué elementos quiero replicar
-
-

## Qué NO quiero replicar (no va con TCC)
-
```

---

## Cómo usar esta carpeta con la IA

Cuando quieras que yo (Claude) te genere un nuevo carrusel, compárteme:
1. El `meta.md` de tu mejor carrusel publicado
2. El tipo de carrusel que quieres hacer ahora
3. Cualquier referencia externa que te haya gustado

Con eso puedo generar copy y estructura mucho más alineada a lo que ya te funciona.

---

## Checklist antes de publicar cada carrusel

- [ ] ¿El slide 1 detiene el scroll en 1 segundo?
- [ ] ¿Los colores respetan la paleta? (café, crema, latte, tinta)
- [ ] ¿Avenir Black / Nunito para keywords, Lora Italic para frases de apoyo?
- [ ] ¿Hay CTA claro en el último slide?
- [ ] ¿El caption del post tiene gancho + contexto + CTA?
- [ ] ¿Tiene hashtags relevantes? (#caféespecialidad #barramovil #eventosmonterrey)

---

*The Coffee Cart · Brand System 2026*
