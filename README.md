# Myk — coming soon

A single-file static "coming soon" teaser for **Myk** (`mykfit.no`), a new Norwegian
clothing brand. *Myk* is Norwegian for **soft** — "Soft by design."

## Stack

- One self-contained `index.html` — all CSS and JS inline, no build step.
- Image-free background (CSS gradients + SVG grain) so the page renders standalone.
- Hosted on **GitHub Pages** from the `main` branch, served at the custom domain
  in `CNAME` (`mykfit.no`).

## Local preview

Just open the file:

```sh
open index.html
```

Or serve it:

```sh
python3 -m http.server 8000   # then visit http://localhost:8000
```

## Deploy

Pushing to `main` publishes automatically via GitHub Pages. The `CNAME` file
points the site at `mykfit.no`; DNS for the domain is configured separately at
the registrar.
