# Deploy to Vercel in 3 Steps

## Your Live Domain
**https://iaraforstreuter.vercel.app**

---

## Step 1: Push to GitHub

```bash
cd vercel-portfolio
git init
git add .
git commit -m "Iara portfolio ready for Vercel"
git remote add origin https://github.com/YOUR_USERNAME/iaraforstreuter.git
git push -u origin main
```

## Step 2: Deploy on Vercel

1. Go to [vercel.com](https://vercel.com)
2. Click "Add New..." → "Project"
3. Select your GitHub `iaraforstreuter` repo
4. Click "Import"
5. Click "Deploy"

**That's it!** Your site is live at **iaraforstreuter.vercel.app** in 30 seconds.

---

## Step 3: (Optional) Add Custom Domain

In Vercel Dashboard:
1. Open your project
2. Go to Settings → Domains
3. Add `iaraforstreuter.com`
4. Update DNS at your registrar
5. Done!

---

## What's Deployed

✅ `index.html` — Your portfolio (23 KB)
✅ `leibniz-packaging.png` — Project image (472 KB)
✅ `vercel.json` — Auto-deployment config
✅ Global CDN, SSL/HTTPS, auto-redeploy on git push

---

## After Deploy

- **Update site**: Edit `index.html` → push to GitHub → auto-redeploy
- **Add images**: Place in root folder alongside `index.html`
- **No build step needed** — Vercel serves your static files directly

---

**Ready? Your site is waiting at iaraforstreuter.vercel.app!**
