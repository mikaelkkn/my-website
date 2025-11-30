# My Website

Personal website built with Astro and deployed to GitHub Pages.

## 🚀 Project Structure

```
├── public/          # Static assets (CNAME, images, etc)
├── src/
│   ├── components/  # Reusable Astro components
│   ├── layouts/     # Page layouts
│   └── pages/       # File-based routing (each .astro = a page)
├── astro.config.mjs # Astro configuration
└── package.json     # Dependencies and scripts
```

## 🧞 Commands

| Command                | Action                                      |
| :--------------------- | :------------------------------------------ |
| `npm install`          | Install dependencies                        |
| `npm run dev`          | Start dev server at `localhost:4321`        |
| `npm run build`        | Build production site to `./dist/`          |
| `npm run preview`      | Preview build locally before deploying      |

## 🌐 Deployment

The site automatically deploys to GitHub Pages when you push to the `main` branch via GitHub Actions.

## 🎨 Adding Pages

Create `.astro` files in `src/pages/`:
- `src/pages/about.astro` → `site.com/about`
- `src/pages/blog/post.astro` → `site.com/blog/post`
