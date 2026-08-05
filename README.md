# Javeria Jamil — UX Portfolio (BugSense Case Study)

A single-page portfolio site built from a real UX case study: research, prototyping, heuristic evaluation, and usability testing for the BugSense diagnostic app.

## What's in this folder

- `index.html` — the whole site (HTML + CSS, no build step needed)
- `assets/prototype-screens.png` — real screens from the Figma prototype
- `assets/usability-testing.png` — real photos from usability testing sessions

## Preview it locally first

Just double-click `index.html`, or open it in any browser — no server needed.

## Publish it on GitHub Pages (free, ~5 minutes)

1. **Create a new repository** on GitHub (e.g. `javeria-ux-portfolio`). Don't initialize it with a README — you already have these files.

2. **Open a terminal in this folder** (`site/`) and run:

   ```bash
   git init
   git add .
   git commit -m "Add UX portfolio site"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/javeria-ux-portfolio.git
   git push -u origin main
   ```

   Replace `YOUR-USERNAME` and the repo name with your actual GitHub username and the repo you created.

3. **Enable GitHub Pages:**
   - Go to your repository on GitHub → **Settings** → **Pages** (left sidebar)
   - Under "Build and deployment" → Source, select **Deploy from a branch**
   - Branch: `main`, folder: `/ (root)` → **Save**

4. **Wait about a minute**, then your site will be live at:

   ```
   https://YOUR-USERNAME.github.io/javeria-ux-portfolio/
   ```

   GitHub shows the exact URL at the top of the Pages settings once it's ready.

## Updating it later

Edit `index.html` directly, then:

```bash
git add .
git commit -m "Update portfolio"
git push
```

GitHub Pages redeploys automatically within a minute or two.
