# Kunal Kapil — Portfolio

Static site: `index.html` + `assets/`. No build step.

## Deploy on Vercel
1. Push this folder to a GitHub repo (see below).
2. vercel.com → **Add New… → Project** → import the repo.
3. Framework preset: **Other**. Build command: *(empty)*. Output directory: *(empty / root)*.
4. Deploy. Add a custom domain under **Settings → Domains** if you have one.

## Deploy on GitHub Pages
1. Create a new public repo on github.com (e.g. `kunal-kapil-portfolio`).
2. Push this folder (or use **Add file → Upload files** and drag in `index.html`, `assets/`, `.nojekyll`).
3. Repo **Settings → Pages** → Source: **Deploy from a branch** → Branch: `main` / `/ (root)` → Save.
4. Site goes live at `https://<username>.github.io/kunal-kapil-portfolio/` in a minute or two.

## After you have the final URL
In `index.html`, change `<meta property="og:image" content="assets/kunal.png">`
to the full address, e.g. `https://your-domain.com/assets/kunal.png`, so link previews show the image.

## Notes
- `assets/xray-textures.js` is only downloaded when the page is opened straight from disk (file://); hosted, it's never requested.
