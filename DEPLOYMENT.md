# Vercel Deployment Guide

## Your Portfolio is Ready! 🚀

All files needed for Vercel deployment are in `/vercel-portfolio/`:

```
vercel-portfolio/
├── index.html                    ← Main portfolio (rename from iara-portfolio.html)
├── leibniz-packaging.png         ← Project image asset
├── vercel.json                   ← Vercel config (auto-deployment settings)
├── package.json                  ← Project metadata
├── .gitignore                    ← Git ignore rules
└── README.md                     ← Deployment instructions
```

---

## Step-by-Step Deployment

### 1. Push to GitHub

```bash
cd vercel-portfolio
git init
git add .
git commit -m "Initial commit: Iara portfolio for Vercel deployment"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/iaraforstreuter.git
git push -u origin main
```

### 2. Deploy to Vercel

**Via Dashboard (Easiest):**
1. Go to [vercel.com](https://vercel.com)
2. Sign in with GitHub
3. Click "Add New..." → "Project"
4. Select your `iaraforstreuter` repository
5. Click "Import"
6. Vercel reads `vercel.json` automatically
7. Click "Deploy"
8. **Done!** Your site is live in ~30 seconds

**Via CLI (Alternative):**
```bash
npm install -g vercel
cd vercel-portfolio
vercel
```

### 3. Add Custom Domain (Optional)

In Vercel Dashboard:
1. Open your project
2. Go to Settings → Domains
3. Add `iaraforstreuter.com` (or your domain)
4. Update DNS at your registrar (instructions provided by Vercel)

---

## What Happens Automatically

✅ `vercel.json` configures:
- Static file serving (no build step needed)
- Caching headers for performance
- Clean URLs (no `.html` extension)
- Global CDN deployment

✅ Every time you push to GitHub:
- Vercel detects changes
- Auto-redeploys your site
- Zero downtime

---

## Update Your Site

Edit `index.html` to:
- Change text/descriptions
- Update contact email
- Add new projects (add images to root folder)
- Modify colors/fonts

Then:
```bash
git add index.html
git commit -m "Update portfolio content"
git push
```

Vercel redeploys automatically.

---

## Current File Sizes

- `index.html` — 23 KB
- `leibniz-packaging.png` — 472 KB
- **Total** — ~500 KB (lightning fast)

---

## Troubleshooting

**Site shows 404?**
- Check that `index.html` is at the root level
- Vercel settings: root directory should be `.` (current folder)

**Image not showing?**
- Verify `leibniz-packaging.png` is in same folder as `index.html`
- Check image path in HTML matches filename exactly

**Need to change anything?**
- Edit files locally
- Push to GitHub
- Vercel auto-redeploys

---

**Ready to deploy? Go to [vercel.com](https://vercel.com) and import your GitHub repo!**
