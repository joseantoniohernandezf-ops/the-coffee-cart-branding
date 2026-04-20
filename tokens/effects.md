# Efectos y texturas — Sistema visual

Estos efectos son el sello de la identidad visual. Sin ellos, el contenido pierde el look "zine / collage hecho a mano".

---

## 1. Fondo papel arrugado

**Qué es:** Textura base que aparece en ~90% de slides. Da sensación de cuaderno viejo / zine / hecho a mano.

**Cómo aplicar:**
- Textura sutil de papel crema con pliegues y marcas de uso
- NO muy marcada (no debe competir con el contenido)
- Overlay con opacidad 40-60% sobre el color de fondo

**CSS aproximado:**
```css
background-image:
  url('../assets/texturas/papel-arrugado.png'),
  linear-gradient(#F5F0E8, #F5F0E8);
background-blend-mode: multiply;
background-size: cover;
```

**Variantes:**
- `papel-arrugado-claro.png` → para fondos beige
- `papel-arrugado-azul.png` → para fondos azul (misma textura tintada)

---

## 2. Washi tape beige

**Qué es:** Celo/cinta adhesiva beige que "pega" elementos (screenshots, imágenes) a la página. Truco visual de zine/collage.

**Specs:**
- Color: `#D9CDB5` (washi-tape)
- Ancho: 80-120px
- Largo: 140-200px
- Rotación: ±5-15deg aleatoria
- Opacidad: 95% (sutil transparencia)
- Posición: esquinas superiores e inferiores del elemento

**Reglas:**
- Usar en screenshots de interfaces, mockups, imágenes cuadradas
- NO usar en todas las piezas (2-3 washi tapes por slide máximo)
- Alternar rotación (uno a +8deg, otro a -5deg) para que parezca puesto a mano

**CSS aproximado:**
```css
.washi-tape {
  position: absolute;
  width: 100px;
  height: 160px;
  background: #D9CDB5;
  opacity: 0.95;
  transform: rotate(8deg);
  box-shadow: 0 2px 4px rgba(0,0,0,0.08);
}
```

---

## 3. Spray paint drip (efecto gotea)

**Qué es:** Subrayado con efecto de pintura que gotea. Aparece en palabras clave.

**Cómo aplicar:**
- Color: azul-drip (`#6B9BC4`) o amarillo-drip (`#D4B53A`)
- Forma: barra con goteos irregulares hacia abajo (3-5 drips)
- Altura barra: 8-14px
- Altura drips: 20-40px
- Posición: debajo de la palabra subrayada
- Textura: rugosidad de spray (no liso)

**Recursos:**
- `assets/stickers/drip-azul.png` — drip azul listo para usar
- `assets/stickers/drip-amarillo.png` — drip amarillo
- Alternativa: SVG inline con path customizado

**Cuándo usar:**
- En palabras clave del hook
- En palabras de énfasis dentro de frases
- Máximo 1-2 drips por slide (no saturar)

---

## 4. Flechas y anotaciones manuscritas

**Qué es:** Flechas dibujadas a boli/rotulador negro, círculos, subrayados irregulares. Simulan anotaciones hechas a mano.

**Estilo:**
- Trazo: 3-5px grosor, ligeramente irregular
- Color: negro tinta (`#1A1A1A`)
- NO perfecto: evitar rectas con regla, curvas CAD

**Tipos:**
- **Flecha curva** — apunta a elementos de interfaz o screenshots
- **Círculo a mano** — rodea algo importante
- **Subrayado irregular** — marca frases clave
- **Check a mano ✓** — listas de "BUEN SISTEMA"
- **Cruz a mano ✗** — listas de "MAL SISTEMA"

**Recursos:**
- `assets/stickers/flecha-curva-*.png` — set de 8-10 flechas con direcciones distintas
- `assets/stickers/circulo-mano.png`
- `assets/stickers/check-mano.png`
- `assets/stickers/cruz-mano.png`

---

## 5. Grano sutil (film grain)

**Qué es:** Textura de grano fotográfico sutil sobre fotos e imágenes. Aumenta sensación analógica.

**Specs:**
- Opacidad: 8-15%
- Blend mode: `multiply` o `overlay`
- Aplicar solo a fotos reales (no a ilustraciones planas)

**CSS:**
```css
.photo-with-grain::after {
  content: '';
  position: absolute;
  inset: 0;
  background-image: url('../assets/texturas/grain.png');
  opacity: 0.12;
  mix-blend-mode: multiply;
  pointer-events: none;
}
```

---

## 6. Sombras (sutiles, no dramáticas)

**Regla:** sombras muy sutiles, solo para separar elementos en layering. Nunca drop shadows dramáticos.

**Specs:**
- Screenshots/cards: `box-shadow: 0 4px 12px rgba(26, 26, 26, 0.08)`
- Texto sobre imagen (muy sutil): `text-shadow: 0 1px 2px rgba(0,0,0,0.1)`
- Talento recortado sobre fondo: sombra bajo sus pies `0 8px 20px rgba(0,0,0,0.15)` (elipsis blur)

---

## 7. Layering de portadas (regla clave)

Las portadas tienen 3 capas:

```
CAPA 3 (frente)   → Talento recortado (PNG sin fondo)
CAPA 2 (medio)    → Texto grande amarillo/negro (palabra clave)
CAPA 1 (fondo)    → Fondo de color + textura papel
```

El talento debe estar **delante del texto**, parcialmente tapándolo. Esto da profundidad y es el "look" firma.

---

## Resumen operativo

| Efecto | Frecuencia | Impacto |
|--------|-----------|---------|
| Papel arrugado | Siempre | Alta |
| Washi tape | En slides con screenshots | Alta |
| Drip paint | 1-2 por slide clave | Media |
| Flechas manuscritas | En slides explicativos | Media |
| Grano | En fotos | Baja (sutil) |
| Sombras | En mockups y talento | Baja (sutil) |
| Layering | Portadas | Crítica |
