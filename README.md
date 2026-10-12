# Bombers — One-page brochure site

This is a minimal, responsive single-page brochure site.

## Files
- `index.html` — main page
- `styles.css` — simple styles

## Local preview
Open `index.html` in your browser, or use a simple HTTP server:

```bash
# Python 3.x
python -m http.server 8000
# then open http://localhost:8000
```

## Git
Initialize and push to your remote (GitHub):

```bash
git init
git add .
git commit -m "Initial scaffold"
# create repo on GitHub and then:
git branch -M main
git remote add origin https://github.com/youruser/yourrepo.git
git push -u origin main
```

## Deploy
- **GitHub Pages:** push to `main` and enable Pages in repository Settings.
- **Netlify / Vercel:** connect your GitHub repo in their dashboard and deploy the `main` branch.

## Custom domain & HTTPS
Both GitHub Pages and Netlify provide automatic HTTPS for custom domains.

