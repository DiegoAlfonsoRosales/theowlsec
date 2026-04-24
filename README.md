# The Owl Sector — Sitio estático

Sitio web estático listo para **GitHub Pages**.

## Cómo publicar en GitHub Pages

1. Crea un repositorio en GitHub (público).
2. Sube **todos los archivos de esta carpeta** (`index.html`, `assets/`, etc.) a la rama `main`.
3. En el repositorio, ve a **Settings → Pages**.
4. En **Source** selecciona: `Deploy from a branch`.
5. Branch: `main` / Folder: `/ (root)`. Guarda.
6. En unos segundos tu sitio estará en `https://<tu-usuario>.github.io/<tu-repo>/`.

## Archivos

- `index.html` — Inicio
- `sobre-nosotros.html` — Sobre nosotros
- `servicios.html` — Servicios
- `portafolio.html` — Portafolio (con filtros)
- `contacto.html` — Contacto (formulario + WhatsApp)
- `styles.css` — Estilos (modo claro/oscuro)
- `assets/` — Imágenes y logo
- `.nojekyll` — Evita que Jekyll procese los archivos

No requiere build, ni Node, ni servidor. 100% estático.
