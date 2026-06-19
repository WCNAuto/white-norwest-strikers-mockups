# Norwest Strikers — Concept Pages

Static HTML mockups for the Norwest Strikers Hockey Club website (WCN project).

## Pages
- `index.html` — landing page listing all concepts
- `nws-homepage-mockup.html` — Homepage Concept A
- `nws-homepage-mockup_1.html` — Homepage Concept B
- `nws-homepage-style2.html` — Homepage Style 2
- `nws-homepage-style3.html` — Homepage Style 3
- `nws-mobile-style1.html` — Mobile Style 1
- `nws-mobile-style2.html` — Mobile Style 2
- `nws-shop.html` — Club Shop

Every page now has a fixed top-right hamburger menu (works on desktop and mobile)
that opens a full-screen overlay linking to all 7 pages, with the current page
highlighted.

## How to push this to GitHub and get a live URL

1. Create a new repo on GitHub (e.g. under your account or a White/WCN org),
   name it something like `norwest-strikers-concepts`. Leave it empty (no README/license).

2. From this folder, run:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Norwest Strikers concept pages with global nav"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```

3. Enable GitHub Pages:
   - Go to the repo → **Settings → Pages**
   - Under "Build and deployment", set **Source** to `Deploy from a branch`
   - Branch: `main`, folder: `/ (root)` → Save

4. After a minute, your live URL will be:
   ```
   https://<your-username>.github.io/<repo-name>/
   ```
   (This is the same pattern automatorr.com uses — a GitHub Pages static site,
   just with a custom domain attached. You can add a custom domain later under
   Settings → Pages → Custom domain if White wants e.g. concepts.white.agency.)

5. Share that URL with Inderjit.
