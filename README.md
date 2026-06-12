# AguaCima

Landing page de **AguaCima** — transporte de agua potable a operaciones mineras de
alta montaña en Mendoza y San Juan, Argentina.

Sitio estático de una sola página (`index.html`): hero con foto, ticker de cobertura,
servicios, flota, clientes, formulario de cotización y botón de WhatsApp. Incluye un
panel de Tweaks (temas claros/oscuros, acento, tipografía) que se activa desde el
entorno de diseño.

## Estructura
- `index.html` — la página completa
- `images/` — fotografías (hero + flota)
- `tweaks-panel.jsx` — panel de personalización (React, cargado vía CDN)

## Ver localmente
Abrí `index.html` con doble clic, o serví la carpeta:

```
npx http-server . -p 8080
```

## Publicar
Listo para Vercel, Netlify o GitHub Pages (servir la raíz del repo).
