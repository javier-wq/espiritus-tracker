# Mis Espíritus — Tracker de colección (Fortnite)

Página web para llevar el control de la colección de espíritus: cuáles tienes y cuáles están maxeados.

- **`espiritus/index.html`** — la página (estática, sin dependencias).
- **`espiritus/img/`** — los 117 sprites recortados de la plantilla.
- **`Plantilla.png`** — imagen original de la que se recortaron.

El progreso se guarda en `localStorage` del navegador, con botones de exportar/importar respaldo.

## Deploy

- **Netlify**: el `netlify.toml` ya apunta a la carpeta `espiritus/` como directorio de publicación — solo conecta este repo.
- **GitHub Pages**: activar Pages sirviendo la raíz y entrar a `/espiritus/`.
