# DESIGN.md — The Coffee Cart
> Archivo maestro del sistema de marca. Si solo puedes leer un archivo, que sea este.
> Úsalo como contexto para Claude, v0, Lovable, Cursor o cualquier agente de IA.

---

## Identidad de marca

| Campo | Valor |
|---|---|
| **Nombre** | The Coffee Cart |
| **Servicio** | Café de especialidad para eventos |
| **Estilo** | Elegante · Limpio · Profesional |
| **Voz** | Dinámica y aspiracional |
| **Idioma** | Español |
| **Audiencia** | Empresas, parejas, organizadores de eventos |

### Tono de voz
- Dinámico y aspiracional: habla de elevar experiencias, no solo de vender café
- Directo y confiado: frases cortas, sin rodeos
- Cálido pero profesional: nunca frío ni corporativo
- Ejemplos de framing: "Eleva tu evento", "Cada sorbo importa", "El detalle que marca la diferencia"

---

## Paleta de colores

| Nombre | Hex | Uso |
|---|---|---|
| **Blanco puro** | `#FFFFFF` | Fondos principales, espacios en blanco |
| **Crema** | `#F5F2EB` | Fondo alternativo tipo "papel", slides de descanso |
| **Latte** | `#9E7B65` | Acento cálido, detalles secundarios |
| **Café** | `#5C3220` | Color principal de marca, bloques destacados |
| **Negro tinta** | `#0D0D0D` | Textos, logos, bordes |

### Reglas de uso
- Nunca usar `#000000` ni `#FFFFFF` puros — siempre los tonos de la paleta
- Combinación principal: fondo Crema `#F5F2EB` + texto Negro tinta `#0D0D0D`
- Combinación de acento: fondo Café `#5C3220` + texto Blanco `#FFFFFF`
- El color Latte `#9E7B65` solo como detalle, nunca como fondo de texto largo

---

## Tipografía

| Rol | Fuente | Peso | Uso |
|---|---|---|---|
| **Display / Headlines** | Avenir | Black / Heavy | Títulos grandes, palabras clave XXL |
| **Serif elegante** | Lora | Italic | Subtítulos, citas, frases aspiracionales |
| **Body** | Avenir | Regular / Medium | Cuerpo de texto, descripciones |

### Sustitutos Google Fonts (100% free)
- Avenir → **Nunito** o **DM Sans** (Bold para display)
- Lora → **Lora** (disponible directamente en Google Fonts)

### Jerarquía tipográfica
1. **Keyword XXL** — Avenir Black, muy grande, 1-3 palabras máximo
2. **Headline** — Avenir Heavy, título del slide
3. **Subheadline** — Lora Italic, frase de apoyo
4. **Body** — Avenir Regular, texto explicativo
5. **Label / Tag** — Avenir Medium uppercase, etiquetas pequeñas

---

## Patrones de marca

Dos patrones disponibles para usar como fondos o bordes decorativos:

1. **Patrón C** — La letra "C" de Coffee repetida en tiling. Usar en blanco sobre negro o negro sobre crema. Ideal para bordes de slide o fondo de CTA.
2. **Patrón granos** — Granos de café en outline repetidos. Más orgánico. Ideal para slides de tips o contexto.

Regla: los patrones siempre en baja opacidad (10–20%) cuando son fondo de texto.

---

## Estructura de carrusel (10 slides)

```
1.  Hook / portada        — Palabra clave XXL + propuesta de valor
2.  Contexto / problema   — ¿Por qué el café importa en tu evento?
3.  Paso / punto 1        — Primer beneficio o elemento del servicio
4.  Paso / punto 2        — Segundo beneficio o elemento
5.  Paso / punto 3        — Tercer beneficio o elemento
6.  Paso / punto 4        — Cuarto beneficio (opcional)
7.  Comparativa           — Sin The Coffee Cart vs Con The Coffee Cart
8.  Tip destacado         — Dato de café de especialidad o consejo
9.  Transición            — Solo texto sobre color sólido (frase aspiracional)
10. CTA                   — "¿Listo para elevar tu evento?" + llamada a acción
```

---

## Tipos de carrusel definidos

### 1. Carrusel de servicio
**Objetivo:** Mostrar qué ofrecemos y cómo funciona
**Hook ejemplo:** "Tu evento merece más que café de máquina"
**Estructura:** Hook → Qué es TCC → Cómo funciona (3 pasos) → Qué incluye → CTA

### 2. Carrusel de testimonio
**Objetivo:** Mostrar casos reales de eventos
**Hook ejemplo:** "Así fue el café en [tipo de evento]"
**Estructura:** Hook → Contexto del evento → Momento destacado → Reacción/resultado → Quote del cliente → CTA

### 3. Carrusel de tips
**Objetivo:** Educar sobre café de especialidad, posicionarnos como expertos
**Hook ejemplo:** "3 cosas que no sabías del café de especialidad"
**Estructura:** Hook → Tip 1 → Tip 2 → Tip 3 → Por qué importa en eventos → CTA

---

## Voz y copy — Banco de frases

### Headlines de portada
- "Eleva tu evento con café de especialidad"
- "El detalle que tus invitados van a recordar"
- "No es solo café. Es experiencia."
- "Tu evento merece más"
- "Café de especialidad. En tu evento."

### CTAs
- "Cotiza tu evento →"
- "Escríbenos y armamos tu propuesta"
- "¿Cuándo es tu evento? Hablemos."
- "DM para disponibilidad"

### Frases de apoyo (Lora Italic)
- "Cada sorbo importa"
- "Donde el buen café hace la diferencia"
- "Especialidad, en cada taza"

---

## Instrucciones para agentes de IA

Cuando generes contenido para The Coffee Cart:
1. Lee este archivo primero
2. Usa siempre la paleta de colores definida — nunca colores fuera de ella
3. La tipografía display es Avenir Black (o Nunito Bold como fallback)
4. El tono es aspiracional y dinámico, nunca pasivo
5. Los textos van en español
6. Estructura los carruseles siguiendo los patrones definidos arriba
7. El nombre siempre como "The Coffee Cart" — nunca abreviado

---

*Última actualización: Abril 2026*
