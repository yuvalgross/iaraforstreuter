# Iara Forstreuter — Multidisciplinary Designer

A clean, modern portfolio website showcasing design work across system design, UX/UI, industrial design, and visual arts.

## Files Structure

```
.
├── index.html                    # Main portfolio page
├── leibniz-packaging.png         # Project image asset
├── vercel.json                   # Vercel deployment config
└── README.md                     # This file
```

## Features

- **Responsive Design** — Mobile-first, works on all screen sizes
- **Performance** — Static HTML, ~50KB total size, instant load
- **SEO Ready** — Clean semantic HTML
- **No Build Step** — Deploy directly to Vercel

## Deployment to Vercel

### Option 1: Deploy from Git (Recommended)

1. Push this folder to a GitHub repository
2. Go to [vercel.com](https://vercel.com)
3. Click "Add New..." → "Project"
4. Import your GitHub repository
5. Vercel auto-detects settings from `vercel.json`
6. Click "Deploy"

**Your site will be live in seconds** with a `.vercel.app` domain or your custom domain.

### Option 2: Deploy from CLI

```bash
npm install -g vercel
vercel
```

Follow the prompts. Your site deploys instantly.

### Option 3: Drag & Drop Deploy

1. Go to [vercel.com/new](https://vercel.com/new)
2. Drag and drop this folder
3. Done

## Custom Domain

In Vercel Dashboard:
1. Go to your project → Settings → Domains
2. Add your custom domain (e.g., `iaraforstreuter.com`)
3. Update DNS at your domain registrar

## Updating Content

Edit `index.html` directly:
- Update project descriptions, images, links
- Change contact email
- Modify colors or typography

Push changes to GitHub → Vercel auto-redeploys.

## Project Assets

**Images:** Place all project images in the root folder (same level as `index.html`). Reference them in HTML like:
```html
<div style="background-image: url('your-image.png');">
```

**Currently included:**
- `leibniz-packaging.png` — Leibniz Packaging project

## Performance

- **Static site** — No database, no API calls
- **Fast load** — Pure HTML/CSS, minimal JavaScript
- **CDN global** — Vercel serves from 300+ locations worldwide
- **SSL/HTTPS** — Automatic with Vercel

## Contact

For questions about this portfolio, reach out to the designer directly.
