# Lasa Dermatología — landing page

Propuesta de landing page para Lasa Dermatología (San Isidro), hecha con [Astro](https://astro.build).

## Comandos

| Comando           | Acción                                      |
| ------------------ | -------------------------------------------- |
| `npm install`       | Instala dependencias                         |
| `npm run dev`       | Corre el servidor local en `localhost:4321`  |
| `npm run build`     | Genera el sitio de producción en `./dist/`   |
| `npm run preview`   | Previsualiza el build antes de deployar      |

## Estructura

```
src/
├── components/   # Header, Hero, Treatments, Feature, Approach, Location, Footer
├── layouts/      # Layout.astro (head, fuentes, script de reveal)
├── pages/        # index.astro
└── styles/       # global.css (tokens de color, tipografía, componentes)
```

## Deploy

El sitio es 100% estático (`output: "static"`), así que se puede deployar directo en Vercel, Netlify, Cloudflare Pages o GitHub Pages sin configuración adicional — solo conectar el repo y usar `npm run build` como build command y `dist/` como output.
