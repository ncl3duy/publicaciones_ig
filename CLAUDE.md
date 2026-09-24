# Reglas del repo publicaciones_ig (NCL3D)

- Repo **público**: solo plantillas y publicaciones listas para importar a Canva. Nada privado.
- Cada plantilla/publicación es una página HTML en `plantillas/` (o `publicaciones/`) con un `<div data-document-role="page">` por placa. Se importa a Canva con el conector (`import-design-from-url`) usando la URL de jsDelivr fijada a un commit: `https://cdn.jsdelivr.net/gh/ncl3duy/publicaciones_ig@<commit>/ruta.html`.
- No usar PDF para Canva: genera recuadros no editables.
- Para que Canva importe bien: nada de `display: inline-block` con fondo y rotación en palabras resaltadas (usar solo color de texto); fotos y logo desde `assets/` por jsDelivr.
- Los diseños importados van a la carpeta de Canva "NCL3D Plantillas"; las versiones reemplazadas, a "Para borrar (versiones viejas)".
- Las fuentes de las plantillas (`.dc.html`) y la marca viven en el repo privado `rebranding_instagram`.
- Textos en español rioplatense (voseo).
