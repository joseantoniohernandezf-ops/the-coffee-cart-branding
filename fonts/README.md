# Fonts · The Coffee Cart

Archivos de fuente del sistema de marca. Organizados por rol tipográfico.

## Estructura esperada

```
fonts/
├── display/
│   ├── Avenir-Heavy.woff2
│   ├── Avenir-Black.woff2
│   └── LICENSE.txt
├── serif-italic/
│   ├── Lora-Italic.woff2
│   ├── Lora-MediumItalic.woff2
│   └── LICENSE.txt           ← SIL OFL — libre para redistribuir
└── body/
    ├── Avenir-Regular.woff2
    ├── Avenir-Medium.woff2
    └── LICENSE.txt
```

---

## Fuentes de la marca

### Avenir — Display y Body
- **Rol:** Títulos, keywords XXL, cuerpo de texto
- **Pesos usados:** Heavy (800), Black (900), Regular (400), Medium (500)
- **Tipo de licencia:** Comercial — Linotype / Monotype
- **Dónde conseguirla:** [fonts.adobe.com](https://fonts.adobe.com/fonts/avenir) (incluida en Adobe Fonts con suscripción CC) o compra directa en Myfonts.com
- **Nota:** Si tienes Adobe Creative Cloud, ya la tienes disponible sin costo adicional.

### Lora — Serif Italic
- **Rol:** Subtítulos, frases aspiracionales, apoyo de headline
- **Pesos usados:** Regular Italic (400i), Medium Italic (500i)
- **Tipo de licencia:** SIL OFL — **100% libre, se puede subir al repo**
- **Dónde conseguirla:** [fonts.google.com/specimen/Lora](https://fonts.google.com/specimen/Lora) — descarga gratuita
- **Nota:** Siempre usar en *italic* — nunca en regular. Es parte del carácter visual de la marca.

---

## Alternativas gratuitas (si no tienes Avenir)

Avenir es una fuente premium. Si no tienes acceso, estas sustituyen muy bien:

| Rol original | Alternativa free | Dónde |
|---|---|---|
| Avenir Black (display) | **Nunito ExtraBold / Black** | Google Fonts |
| Avenir Heavy (títulos) | **DM Sans Bold** | Google Fonts |
| Avenir Regular (body) | **DM Sans Regular** | Google Fonts |
| Lora Italic | **Lora Italic** | Google Fonts (idéntica) |

> Nunito Black es la alternativa más cercana a Avenir Black en proporciones y espíritu. Para carruseles de Instagram la diferencia es mínima.

---

## Cargar en web / app

### Con Adobe Fonts (Avenir real)
```html
<!-- Agregar en el <head> del HTML -->
<link rel="stylesheet" href="https://use.typekit.net/[tu-kit-id].css">
```

### Con Google Fonts (alternativas free)
```html
<!-- Nunito + Lora — pegar en el <head> -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Lora:ital,wght@1,400;1,500&family=Nunito:wght@800;900&family=DM+Sans:opsz,wght@9..40,400;9..40,500&display=swap" rel="stylesheet">
```

### Con archivos locales (.woff2)
```css
/* Display — Avenir Black */
@font-face {
  font-family: 'Avenir';
  src: url('./fonts/display/Avenir-Black.woff2') format('woff2');
  font-weight: 900;
  font-style: normal;
  font-display: swap;
}

/* Display — Avenir Heavy */
@font-face {
  font-family: 'Avenir';
  src: url('./fonts/display/Avenir-Heavy.woff2') format('woff2');
  font-weight: 800;
  font-style: normal;
  font-display: swap;
}

/* Serif — Lora Italic */
@font-face {
  font-family: 'Lora';
  src: url('./fonts/serif-italic/Lora-Italic.woff2') format('woff2');
  font-weight: 400;
  font-style: italic;
  font-display: swap;
}

/* Body — Avenir Regular */
@font-face {
  font-family: 'Avenir';
  src: url('./fonts/body/Avenir-Regular.woff2') format('woff2');
  font-weight: 400;
  font-style: normal;
  font-display: swap;
}
```

---

## Uso en Canva / herramientas de diseño

### Si usas Canva Pro
- Avenir está disponible directamente en Canva como "Avenir Next"
- Lora está disponible en Canva como fuente de texto

### Si usas Canva gratis
- Usa **Nunito** como sustituto de Avenir (búscala en el selector de fuentes)
- Lora está disponible en Canva gratis

### Si usas Figma / Adobe Illustrator
- Activa Avenir desde Adobe Fonts en tu panel de aplicaciones CC
- Lora: descárgala de Google Fonts e instálala en tu sistema

---

## Licencias y GitHub

| Fuente | Licencia | ¿Se puede subir al repo? |
|---|---|---|
| Avenir | Comercial Linotype | ❌ NO — no redistribuir |
| Lora | SIL OFL 1.1 | ✅ SÍ — libre redistribución |
| Nunito | SIL OFL 1.1 | ✅ SÍ — libre redistribución |
| DM Sans | SIL OFL 1.1 | ✅ SÍ — libre redistribución |

> **Importante:** Los archivos `.woff2` de Avenir NO deben subirse a este repo si es público. Están en `.gitignore`. Solo sube las fuentes con licencia SIL OFL. Para usar Avenir en tus diseños, actívala desde Adobe Fonts o instálala localmente.

---

## Checklist de instalación

- [ ] Avenir activada en Adobe Fonts (o Nunito instalada como alternativa)
- [ ] Lora descargada de Google Fonts e instalada en el sistema
- [ ] `tokens/fonts.css` actualizado con las rutas correctas
- [ ] Probado en al menos un slide que los textos se renderizan correctamente

---

*The Coffee Cart · Brand System 2026*
