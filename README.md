# Docs Hub (MkDocs Material)

A lightweight documentation hub to showcase your technical writing and knowledge, built with **MkDocs Material**.

## ✨ Features
- Clean Material theme with light/dark mode
- Organized navigation with Git, Linux, Docker, Python sections
- Rich Markdown extras: admonitions, tabs, task lists, code copy
- Ready for **GitHub Pages** or **Netlify** deployment

## 🚀 Quickstart
```bash
# 1) Install dependencies
pip install -r requirements.txt

# 2) Run locally
mkdocs serve

# 3) Build static site
mkdocs build

# 4) Deploy to GitHub Pages (one-time setup in Settings > Pages)
# Or use the provided GitHub Actions workflow for automatic deploys.
```

## 📦 Deploy Options

### GitHub Pages (via Actions)
- Push to `main` and the workflow at `.github/workflows/deploy.yml` builds and deploys to Pages.
- Ensure **Settings → Pages** is set to "Build and deployment: GitHub Actions".

### Netlify
- Connect the repo on Netlify.
- Build command: `mkdocs build`
- Publish directory: `site`
- (Optional) Use the provided `netlify.toml` for config.

## 🧩 Customize
- Edit `mkdocs.yml` for nav and theme.
- Put custom CSS in `docs/assets/styles/extra.css`.
- Add pages in `docs/guides/...`.

## 📝 License
MIT