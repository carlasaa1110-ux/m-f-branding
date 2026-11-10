# DESIGN.md — MSF 360 · Juan Madrigal

> Guía de marca para crear cualquier pieza (web, reels, carruseles, anuncios, emails) con coherencia.
> Fuentes analizadas: msf360.com (estilos reales extraídos del navegador, nov 2026) + perfil de Instagram @juanmadrigalmsf (bio, foto y feed).

---

## 1. Esencia de marca

| | |
|---|---|
| **Marca** | MSF 360º (también "Madrigal 360") |
| **Cara visible** | Juan Madrigal — asesor / bróker hipotecario en Madrid |
| **Qué hace** | Compara bancos, negocia la hipoteca por el cliente y simplifica todo el proceso hasta la firma |
| **Promesa** | Cobertura de 360º: te acompaño de principio a fin |
| **Prueba** | +10 años de experiencia, convenios con multitud de entidades |
| **Diferencial** | Formación + experiencia + relación con bancos = condiciones que el cliente no conseguiría solo |
| **Público** | Compradores de vivienda (especialmente jóvenes y parejas, primera vivienda), segunda mano, obra nueva, autopromotores, quien quiere mejorar o amortizar su hipoteca |
| **Valores** | Profesionalidad, compromiso, confianza, disponibilidad total |

**Concepto clave:** el "360º" — visión completa, acompañamiento total, sin cabos sueltos.

---

## 2. Colores

### Paleta principal (extraída de la web)

| Rol | Nombre | HEX | Uso |
|---|---|---|---|
| **Primario** | Verde MSF | `#007565` | Logo, botones, barra superior, enlaces del menú, fondos de tarjetas, acentos |
| **Secundario** | Verde agua | `#66C9B8` | Bloques de color de apoyo, fondos suaves, degradados con el primario |
| **Texto títulos** | Gris carbón | `#333333` | H1, H2, H5 |
| **Texto cuerpo** | Gris medio | `#666666` | Párrafos, menú, textos largos |
| **Texto secundario** | Gris claro | `#999999` | Notas, metadatos |
| **Negro marca** | Negro | `#000000` | Wordmark "MSF" del logo |
| **Fondo oscuro** | Casi negro | `#121212` | Secciones oscuras (bloque "Soluciones hipotecarias") |
| **Footer** | Gris pizarra | `#606060` | Pie de página |
| **Fondo base** | Blanco | `#FFFFFF` | Fondo general |
| **Fondo suave** | Gris niebla | `#F4F4F4` | Acordeones FAQ, tarjetas |
| **Campos** | Gris input | `#EEEEEE` | Inputs de formulario |
| **Bordes** | Gris línea | `#DEDFE0` | Separadores |

### Tokens

```css
:root {
  --msf-primary:      #007565;
  --msf-secondary:    #66C9B8;
  --msf-black:        #000000;
  --msf-dark:         #121212;
  --msf-heading:      #333333;
  --msf-body:         #666666;
  --msf-muted:        #999999;
  --msf-footer:       #606060;
  --msf-bg:           #FFFFFF;
  --msf-bg-soft:      #F4F4F4;
  --msf-input:        #EEEEEE;
  --msf-border:       #DEDFE0;
}
```

### Reglas de color
- El verde `#007565` es **el** color de marca: un solo acento por pieza, nunca compitiendo con otro color saturado.
- Proporción orientativa: 70 % blanco/neutros · 20 % grises de texto · 10 % verde.
- Texto blanco sobre `#007565` ✔ (buen contraste). Texto blanco sobre `#66C9B8` ✘ (contraste bajo): usar `#121212` o `#333333` encima.
- En Instagram el verde aún no aparece: es la gran oportunidad para unir web y redes (ver §6).
- No usar el verde lima `#61A229` que aparece en la web: pertenece al plugin de cookies, no a la marca.

---

## 3. Tipografías

| Rol | Fuente | Peso | Tamaño web | Notas |
|---|---|---|---|---|
| **Títulos** (H1–H5) | **Montserrat** | 500 (Medium) · 600 en títulos de tarjeta | H1 59px · H2 50px · H5 31px · H4 18px | Interlineado ≈ 1.0, sin mayúsculas forzadas |
| **Cuerpo** | **Duru Sans** | 500 | 18px / interlineado 1.8 (32px) | Menú 14px peso 600 |
| **Botones** | Montserrat | 500 | 20px | Texto en sentence case |
| **Fallback** | Helvetica, Arial, sans-serif | — | — | |

Ambas en Google Fonts.

**En redes (feed de Instagram):** títulos en sans-serif neo-grotesca blanca (tipo Helvetica/Inter), grande, centrada, en sentence case. Para unificar con la web, se recomienda pasar esos títulos a **Montserrat SemiBold/Bold**.

---

## 4. Componentes web

- **Botón primario:** fondo `#007565`, texto `#FFFFFF`, radio `10px`, sin borde, Montserrat 500 20px. Textos: "Cuenta con nosotros", "Contacta con nosotros", "Enviar".
- **Barra superior:** fondo `#007565`, texto blanco 12px (teléfono + email).
- **Header:** blanco, logo a la izquierda, menú en gris con el activo en verde.
- **Tarjetas de producto:** icono + título Montserrat 600 blanco + descripción corta (1 frase).
- **FAQ:** acordeones sobre `#F4F4F4`, preguntas en primera persona del cliente ("¿Cómo sé qué hipoteca es la mejor para mí?").
- **Fotografía web:** arquitectura moderna de cristal en contrapicado, oficinas, gente de negocio; luz fría y limpia.
- **Tema:** WordPress + Divi.

---

## 5. Logo

- Wordmark **"MSF"** en negro + **"360º"** y pictograma en verde `#007565`; versión negativa (blanco) para fondos oscuros.
- Zona de respeto mínima: altura de la "M" alrededor.
- No recolorear, no deformar, no poner sobre fotos con mucho ruido sin una capa oscura.

---

## 6. Estilo visual en Instagram (@juanmadrigalmsf)

### Lo que ya funciona
- **Juan siempre en cámara**: es la marca. Plano medio, mirada a cámara o de perfil escribiendo.
- **Pizarra blanca con cifras manuscritas** (180.000 €, 3,4 %, 2,9 %, × 360 meses, "¿?") en rotulador azul: icono visual propio y muy reconocible → transmite "te hago los números".
- **Vestuario:** camisa blanca/rosa palo con microcuadro (contenido de pizarra) · traje azul marino o gris oscuro con chaleco y camisa rosa claro (formato "Modo Jake", foto de perfil). Elegante pero cercano.
- **Localizaciones:** despacho/pizarra con luz natural, exteriores de Madrid (calle residencial, parque con banco de madera), salón de casa.
- **Paleta fotográfica real:** azul marino, blanco, rosa palo, piel cálida, verdes naturales, beige.
- **Portadas de reel:** título grande blanco centrado en 2–3 líneas, sentence case, con sombra suave; encima una etiqueta tipo **píldora con contorno blanco** que indica la serie.

### Series de contenido (etiquetas)
| Etiqueta | Formato | Ejemplos |
|---|---|---|
| **Casos ficticios** | Juan explica en la pizarra un caso concreto con números | "Aval público para jóvenes", "Comprar en pareja sin estar casados", "Te tocan 20.000 € ¿amortizas?" |
| **Modo Jake** | Narrativa con personaje recurrente, Jake, que vive situaciones hipotecarias | "A Jake le suben la cuota", "El banco dice que no a Jake" |
| *(Temas)* | Titular en MAYÚSCULAS bold, más opinión/tendencia | "COMPRAR CASA POR PRESIÓN SOCIAL", "HIPOTECAS VERDES" |

### Reglas de portada
1. Una idea por portada, máx. 6–7 palabras.
2. Sentence case por defecto; MAYÚSCULAS solo para temas de opinión.
3. Siempre la etiqueta de serie arriba del título.
4. Cara de Juan en el tercio superior; título en el tercio inferior.
5. **Mejora recomendada:** incorporar el verde `#007565` en la píldora de serie (relleno verde, texto blanco) y Montserrat en los títulos → el feed y la web se leerán como una sola marca.

### Perfil
- Foto: Juan de pie en calle residencial de Madrid, traje azul con chaleco, sonrisa contenida. Profesional y accesible.
- Bio actual: «Consigue la mejor hipoteca. / Comparo bancos, negocio por ti y simplifico todo el proceso. / +10 años de experiencia…» + enlace a formulario Tally.

---

## 7. Tono de voz

**Personalidad:** asesor experto que te habla como un amigo que sabe de números. Seguro, claro, tranquilizador, nada vendedor de humo.

| Somos | No somos |
|---|---|
| Claros y directos | Técnicos o burocráticos |
| Cercanos (tuteo siempre) | Coleguillas o chabacanos |
| Expertos que lo demuestran con números | Gurús que prometen milagros |
| Tranquilizadores ("sin sorpresas") | Alarmistas |
| Orientados al cliente ("para ti", "a tu perfil") | Centrados en nosotros |

**Reglas de escritura**
- **Tuteo** siempre: "te ayudamos", "tu perfil", "tu hipoteca".
- **Voz:** en Instagram, primera persona del singular (Juan: "comparo", "negocio por ti"). En la web, primera del plural ("nuestro equipo"). Mantener esta lógica: persona en redes, empresa en web.
- Frases cortas. Un beneficio por frase.
- Formular dudas tal y como las piensa el cliente ("¿Realmente podéis conseguir…?").
- Explicar con **casos y números concretos**, no con teoría.
- Matiz honesto: "cada caso es diferente", "no existe una hipoteca perfecta para todo el mundo".

---

## 8. Frases y expresiones que uso

**Promesa / propuesta de valor**
- "Consigue la mejor hipoteca."
- "Comparo bancos, negocio por ti y simplifico todo el proceso."
- "Financiación 100 % con las mejores condiciones."
- "La hipoteca que mejor se adapte a ti."
- "Cobertura de 360º."
- "Te acompañamos durante todo el proceso… hasta la firma."
- "Sin que tengas que negociar banco por banco."
- "Para que sepas cuánto vas a pagar cada mes sin sorpresas."

**Confianza**
- "+10 años de experiencia."
- "Convenios con multitud de entidades bancarias."
- "Economistas, asesores financieros y gestores de riesgos homologados."
- "Profesionalidad, compromiso, confianza y disponibilidad total."
- "Estudio sin compromiso."

**Honestidad / matiz**
- "Cada caso es diferente."
- "No existe una hipoteca perfecta para todo el mundo."
- "Cuanto antes estudiemos tu caso, más opciones tendrás."
- "Tomar decisiones con seguridad."

**Llamadas a la acción**
- "Cuenta con nosotros." · "Contacta con nosotros." · "Ponte en contacto con nosotros."

**Fórmulas de redes**
- "Casos ficticios" · "Modo Jake" · "A Jake le…" · "Te tocan X € ¿amortizas?"

**Vocabulario propio:** bróker hipotecario, asesoría hipotecaria, intermediación de crédito, tu perfil, capacidad de pago, euríbor, subrogación, amortizar, autopromoción, aval público, cuota.

---

## 9. Frases que NUNCA uso

*(Deducidas del posicionamiento: honesto, experto y cercano. Revísalas y ajústalas a tu criterio.)*

- ❌ Promesas absolutas: "Hipoteca garantizada", "Te aprobamos seguro", "100 % de éxito".
- ❌ Urgencia falsa: "¡Solo hoy!", "Últimas plazas", "Corre antes de que suba el euríbor".
- ❌ Lenguaje de chollo: "Hipotecas baratísimas", "El mejor precio del mercado", "Gratis total".
- ❌ Atacar a los bancos: "Los bancos te engañan", "Los bancos son el enemigo" (negociamos con ellos, no contra ellos).
- ❌ Jerga sin explicar: "TAE vinculada con diferencial sobre índice de referencia…" sin traducirla.
- ❌ Tono frío/corporativo: "Estimado cliente", "Rogamos contacte con nuestro departamento".
- ❌ Usted: siempre tú.
- ❌ Asesoramiento de inversión con nombre y apellidos ("compra ya", "invierte en X"): siempre "depende de tu caso".
- ❌ Exceso de emojis, anglicismos innecesarios o jerga juvenil forzada.

---

## 10. Checklist antes de publicar

- [ ] ¿Sale Juan o su pizarra?
- [ ] ¿Hay un número o caso concreto?
- [ ] ¿Etiqueta de serie arriba y título de ≤7 palabras?
- [ ] ¿Verde `#007565` como único acento?
- [ ] ¿Montserrat en títulos / Duru Sans en textos largos?
- [ ] ¿Tuteo y frases cortas?
- [ ] ¿Ninguna promesa absoluta?
- [ ] ¿CTA clara (enlace de la bio / "Cuenta con nosotros")?

---

## 11. Incidencias detectadas en la web

- **Textos de "Hipoteca variable" y "Hipoteca mixta" intercambiados:** el de variable describe una mixta (fijo los primeros años, variable después) y el de mixta describe una variable (sigue al euríbor). Conviene corregirlo.
- La web habla de "equipo" y "nosotros"; Instagram de "yo". Está bien, pero la web podría reforzar la figura de Juan (foto, nombre, "+10 años") para que quien llega desde redes reconozca a la misma persona.
- La fotografía de la web (edificios de cristal, stock de oficina) es más fría que la de Instagram (Juan, luz natural, Madrid). Sustituir el stock por fotos de Juan unificaría la marca.
