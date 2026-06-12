# timknutsen.github.io

Personal website for Tim Martin Knutsen, served via GitHub Pages at
<https://timknutsen.github.io/>.

It is a plain static site: no framework, no build step, no Jekyll, npm, or
server-side dependencies. Just hand-written HTML, CSS, and static assets.

## Structure

```
.
├── index.html         # The page: intro, work, projects, publications, thesis, links
├── styles.css         # All styling
├── publications.json  # Machine-readable publication metadata
├── 404.html           # Simple not-found page for GitHub Pages
├── assets/            # Images (e.g. the portrait)
└── .nojekyll          # Tells GitHub Pages to skip Jekyll processing
```

The visible publication list lives in `index.html` so the page works with
JavaScript disabled. `publications.json` mirrors that list in a structured
form for anyone who wants to consume it programmatically.

## Local preview

No tooling required — open `index.html` directly, or serve the folder so that
relative paths and `404.html` behave like they do on Pages:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000/
```

## Deployment

GitHub Pages builds from the default branch automatically (see
`.github/`). Pushing to `main` publishes the site.
