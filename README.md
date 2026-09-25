# Complete — Landing Page

Modern, sticky landing page for **Complete**, a full-stack tech services company.

## What's included

- Dark-mode, tech-forward design
- Responsive (mobile + desktop)
- Clear value proposition and service grid
- Smooth scroll + sticky nav
- Single `index.html` — no build step

## Deploy to GitHub Pages

1. Create a new GitHub repository (e.g. `complete` or `complete-landing`).
2. Push this folder’s contents to the repo root (or a `/docs` folder).
3. In the repo: **Settings → Pages → Source**
   - Branch: `main` (or `master`)
   - Folder: `/ (root)` or `/docs`
4. Save. Your site will be live at:
   `https://<your-username>.github.io/<repo-name>/`

### Quick push example

```bash
cd complete-landing
git init
git add .
git commit -m "Initial Complete landing page"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
```

Then enable GitHub Pages as above.

## Customize

| What | Where |
|------|--------|
| Company email | Search `hello@complete.tech` |
| Domain / brand | Logo text & meta tags |
| Colors | CSS variables at top of `<style>` |
| Services copy | `.service-card` sections |

## Local preview

Just open `index.html` in a browser, or:

```bash
npx serve .
# or
python3 -m http.server 8000
```
