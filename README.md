# Agencia Aster — web one page

Sitio estático (HTML + CSS + JS, sin dependencias). Abrí `index.html` en el navegador o publicalo en cualquier hosting estático (Netlify, Vercel, GitHub Pages).

- **Tipografías:** Bricolage Grotesque (títulos en condensed / opsz 36, textos en regular) y Ms Madi (acentos), desde Google Fonts.
- **Paleta:** `#FFFFFF` · `#00E7FF` · `#00A3FF` · `#010978` · `#04044A` (variables en `styles.css`).
- **Estructura:** las 13 secciones del documento de arquitectura, cada una como módulo con `id` listo para pasar a `/servicios/...`, `/proyectos/...`, etc.

## WhatsApp
Todos los botones abren WhatsApp al +54 9 3873 64-4198 con un mensaje predeterminado. Para cambiarlo, editá `WHATSAPP_NUMBER` en `main.js`.

## Blog
- Listado: `blog/index.html`. Cada nota vive en su carpeta: `blog/nombre-de-la-nota/index.html`.
- Para sumar una nota: duplicá la carpeta de una nota existente, cambiá título, fecha, descripción y texto, y agregá su tarjeta en `blog/index.html` (y en el bloque "Blog" de `index.html` si querés que aparezca en la home).

## Pendiente de completar con contenido real
- Logos de marcas (franja de confianza), casos de proyectos con sus imágenes, fotos y nombres del equipo, testimonios autorizados.
- Los logos de `assets/` se recortaron de la pieza de marca; conviene reemplazarlos por los SVG originales.
