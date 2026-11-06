# Balkon-Bepflanzen.de

SEO-optimierter Ratgeber für Balkongärtnerei in Deutschland.

## Tech-Stack

- [Astro 7](https://astro.build) (Static Site Generation)
- Vanilla CSS (kein Tailwind, kein React)
- Content Collections (Markdown)
- `@astrojs/sitemap`
- Local fonts via Fontsource (Source Sans 3 + Source Serif 4)
- GitHub Pages Deployment

## Entwicklung

```bash
npm install
npm run dev
```

Build:

```bash
npm run build
npm run preview
```

## Struktur

```
src/
  components/   # Header, Footer, SEO, BlogCard, …
  content/blog/ # 12 Ratgeber-Artikel (Markdown)
  layouts/      # BaseLayout, BlogLayout
  pages/        # Routen
  styles/       # global.css
  utils/        # Blog-Helfer
public/         # robots.txt, Favicons, OG-Image
.github/workflows/deploy.yml
```

## Deployment (GitHub Pages)

1. Repo auf GitHub pushen
2. Settings → Pages → Source: **GitHub Actions**
3. Optional: Custom Domain `balkon-bepflanzen.de` eintragen
4. Bei Push auf `main` baut und deployed der Workflow automatisch

## Werbung

Kein AdSense oder anderes Werbenetzwerk eingebunden.


## Lizenz

Inhalt © Balkon-Bepflanzen.de – Alle Rechte vorbehalten.
