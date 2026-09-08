# sandip_personal_website

Personal website, deployed via GitHub Pages.

## Structure

```
index.html          Home page
about.html           About page
projects.html        Projects listing
contact.html         Contact page
css/style.css        Site-wide styles (light/dark aware)
js/main.js           Small bit of JS (active nav highlighting)
assets/img/          Images
.nojekyll             Tells GitHub Pages to serve files as-is (no Jekyll processing)
```

Plain HTML/CSS/JS — no build step, no dependencies. Edit files directly and push.

## Local preview

Just open `index.html` in a browser, or serve it locally:

```sh
python3 -m http.server 8000
```

then visit http://localhost:8000

## Deploying

GitHub Pages is configured to serve from the `main` branch, root directory
(Settings → Pages → Source: Deploy from a branch → `main` / `/root`).

Once enabled, the site is live at:

- `https://<username>.github.io/` if this repo is named `<username>.github.io`
- `https://<username>.github.io/<repo-name>/` otherwise

## TODO

- [ ] Fill in the `<!-- TODO -->` placeholders in each page (bio, tagline, skills, projects, LinkedIn)
- [ ] Add a real photo/logo to `assets/img/`
- [ ] Double check the GitHub username used in nav/footer links
- [ ] Set a custom domain (optional) via Settings → Pages → Custom domain
