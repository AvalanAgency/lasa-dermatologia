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

El sitio es 100% estático (`output: "static"`) y se publica solo vía GitHub Actions a GitHub Pages en cada push a `main` (ver `.github/workflows/deploy.yml`). También se puede deployar directo en Vercel, Netlify o Cloudflare Pages sin configuración adicional.

## Fotos

Las imágenes en `public/images/` son fotos de stock con licencia libre (Unsplash License, uso comercial permitido sin atribución) usadas como placeholder de muestra — para el sitio final del cliente hay que reemplazarlas por fotos reales del consultorio, del equipo y de pacientes con su consentimiento:

- `hero-portrait.jpg` — [unsplash.com/photos/1763539818420-165e69b7489b](https://unsplash.com/photos/1763539818420-165e69b7489b)
- `spa-treatment.jpg` — [unsplash.com/photos/1761718209708-9ab9ba1c7252](https://unsplash.com/photos/1761718209708-9ab9ba1c7252)
- `clinic-interior.jpg` — [unsplash.com/photos/1781513144825-aa1e284c5950](https://unsplash.com/photos/1781513144825-aa1e284c5950)
- `serum-hands.jpg` — [unsplash.com/photos/1552256031-811fa8f0a7b1](https://unsplash.com/photos/1552256031-811fa8f0a7b1)
- `cream-apply.jpg` — [unsplash.com/photos/1693004927824-f2623bbedc8b](https://unsplash.com/photos/1693004927824-f2623bbedc8b)
