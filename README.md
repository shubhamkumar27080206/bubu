# Sorry, Nidhi 💛

A small, interactive apology page. Pure HTML/CSS/JS, no build step.

## Deploy on GitHub Pages (free)

1. Create a new public repo on GitHub, e.g. `sorry-nidhi`.
2. Upload `index.html` and `README.md` (or push with git):
   ```bash
   git init
   git add .
   git commit -m "A sorry, made with love"
   git branch -M main
   git remote add origin https://github.com/<your-username>/sorry-nidhi.git
   git push -u origin main
   ```
3. In the repo go to **Settings → Pages**, set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`, then **Save**.
4. After about a minute your site is live at `https://<your-username>.github.io/sorry-nidhi/`.

## Other free hosts
- **Netlify Drop**: drag the folder onto app.netlify.com/drop
- **Vercel / Cloudflare Pages**: import the repo, no settings needed

## Add your photos
1. Create an `images/` folder next to `index.html`.
2. Drop your photos in it (JPG/PNG, ideally under 1 MB each; square-ish crops look best), named `1.jpg`, `2.jpg`, and so on.
3. In the `CONFIG` block, edit the `photos` list (path plus a caption) and optionally set `heroPhoto: "images/hero.jpg"` for the round photo on the first screen.
4. Photos that are missing show a friendly "your photo goes here" placeholder, so nothing breaks.

## Customize the text
Open `index.html` and edit the `CONFIG` block at the top of the script: names, the typed message, headings (`text`), the six apology cards, the coupons and the funny lines. Replace the "A Memory" card with a real memory of yours for extra impact.
