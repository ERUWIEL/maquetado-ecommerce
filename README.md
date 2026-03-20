# Maquetado eCommerce

Esta carpeta contiene una maqueta de un sitio web (Nexus Games).

## Estructura recomendada

- `index.html` - Página principal.
- `pages/` - Resto de páginas del sitio (carrito, catálogo, perfil, administración, etc.).
- `assets/` - Recursos estáticos (CSS, imágenes).
  - `assets/css/` - Todas las hojas de estilo.
  - `assets/images/` - Imágenes usadas en el sitio.

### Notas
- Las páginas en `pages/` usan rutas relativas para cargar estilos desde `assets/css/`.
- El contenido dentro de `public/` es una versión alternativa/legacy del sitio.
