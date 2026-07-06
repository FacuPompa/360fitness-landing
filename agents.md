# Agents Handoff - 360 Fitness San Luis

## Proyecto

Landing demo estática para **360 Fitness San Luis**, gimnasio / entrenamiento funcional local en San Luis, Argentina.

Objetivo principal: generar consultas por WhatsApp.

## Archivos del sitio

- `index.html`: estructura, SEO, schema, contenido y enlaces.
- `styles.css`: diseño responsive, tipografía, footer, cards, galería y estados visuales.
- `script.js`: menú mobile, FAQ, reveal effects y año dinámico.
- `assets/`: logo, favicon e imágenes locales del sitio.
- `robots.txt` y `sitemap.xml`: marcadores SEO con `https://example.com/` hasta tener dominio real.

## Datos comerciales confirmados

- Nombre: 360 Fitness San Luis
- Rubro: gimnasio / entrenamiento funcional
- Dirección visible: **Maipú 1180, San Luis, Argentina**
- Nota: aunque algunas fuentes indiquen otra numeración, usar siempre `Maipú 1180` en el sitio.
- WhatsApp: `+54 9 266 493-7171`
- WhatsApp link base: `https://wa.me/5492664937171`
- Instagram: `https://www.instagram.com/360fitnesssl/`
- Horario general: `07:00 a 23:00`
- Oferta conocida: entrenamientos personalizados, grupales y funcional.

## Planes de créditos

Mantener la aclaración: valores de referencia enero-marzo; no son precios vigentes garantizados.

- 8 créditos: transferencia ref. `$26.250`; efectivo ref. `$25.000`
- 12 créditos: transferencia ref. `$31.500`; efectivo ref. `$30.000`
- Personalizado / grupos: a consultar

Cada plan debe conservar CTA de consulta por WhatsApp.

## Estilo visual

- Fitness urbano, local, sobrio y vendible.
- Fondo oscuro, acento lima usado con criterio, secciones claras solo donde ayudan a ordenar.
- Tipografía actual: Google Fonts `Manrope`, pesos `400`, `500`, `600`, `700`.
- Evitar pesos `800`, `900` o `950`.
- No usar estética futurista, formas abstractas, logos orbitando ni textos de demo visibles.
- Mantener sensación de gimnasio real/local: entrenamiento funcional, fuerza, grupos, seguimiento cercano.

## Imágenes

Las imágenes deben vivir en `assets/`, sin incrustar medios pesados dentro de HTML o CSS.

Hero actual:

- `assets/hero-clase-funcional.jpg`

Galería actual:

- `assets/galeria-entrenamiento-funcional.jpg`
- `assets/galeria-espacio-entrenamiento.jpg`
- `assets/galeria-seguimiento.jpg`
- `assets/galeria-cuerdas-funcional.jpg`

Logo / favicon:

- `assets/logo-360-fitness.png`
- `assets/logo-360-fitness-centered.png` para nav y footer
- `assets/favicon.png`
- `assets/icon-whatsapp.svg` y `assets/icon-instagram.svg` desde Simple Icons, usados en el footer.

## Footer

Debe mantener:

- Logo / nombre
- Frase corta
- CTA chico a cupos
- Dirección
- Horario general
- Links internos
- Copyright
- Iconos de WhatsApp e Instagram, no texto visible "WhatsApp" / "Instagram" en la columna de contacto.

## SEO

Si se publica con dominio real, reemplazar `https://example.com/` en:

- canonical
- Open Graph URL / image
- Twitter image
- JSON-LD `url` / `image`
- `robots.txt`
- `sitemap.xml`

Mantener JSON-LD válido y no inventar ratings, coordenadas, precios vigentes ni horarios por clase.

## Restricciones

- Sin React.
- Sin Tailwind.
- Sin frameworks.
- Sin dependencias JavaScript.
- No cambiar la lógica de `script.js` salvo pedido explícito.
- No romper WhatsApp ni Instagram.
- No prometer precios vigentes.
- Mantener UTF-8.

## Skills usadas

- `radar-local`: prospección inicial del negocio local.
- `vidriera-web`: construcción y refinamiento de la landing estática.

Skills opcionales para futuras pasadas:

- `info-local`: enriquecer datos públicos si se necesita validar información del negocio.
- `referencias-web`: buscar referencias visuales antes de una nueva dirección estética.

## Checks recomendados

```powershell
node --check .\script.js
rg -n "font-weight" .\styles.css
```

Verificar también:

- Todas las imágenes referenciadas existen en `assets/`.
- Los enlaces internos apuntan a IDs existentes.
- WhatsApp usa `https://wa.me/5492664937171`.
- El footer muestra iconos sociales y no texto visible de Instagram / WhatsApp en la columna de contacto.
