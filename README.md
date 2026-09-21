# Cindy Cui — Personal Website

A minimal, single-page personal website. Plain HTML + CSS, no build step, no cost to host.

## Preview locally

Open `index.html` in a browser, or serve it:

```bash
cd ~/workspace/personal-website
python3 -m http.server 8000
```

## Publish free on GitHub Pages

1. Create a new **public** repository on GitHub (e.g. `personal-website`, or `<username>.github.io` for a personal domain-style URL).
2. Push this folder to it:

```bash
cd ~/workspace/personal-website
git remote add origin https://github.com/<username>/<repo>.git
git branch -M main
git push -u origin main
```

3. In the repo on GitHub: **Settings → Pages → Deploy from a branch**, choose `main` / `(root)`, and save.
4. Your site will be live at `https://<username>.github.io/<repo>/` (or `https://<username>.github.io/` if you used the `<username>.github.io` repo name).

## To customize

- Edit `index.html` for content (experience, projects, contact links).
- Edit `styles.css` for colors and typography.
- Replace `resume.pdf` with an updated résumé.
- Update the GitHub link in the hero (currently points at `https://github.com/` as a placeholder).
