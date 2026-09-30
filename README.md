# Research Notebook

Public research notebook built with [Quarto](https://quarto.org) and published to GitHub Pages via GitHub Actions.

## Local preview
```bash
pip install -r requirements.txt
quarto preview
```

## Add an entry
Create `notebooks/YYYY-MM-DD-title.qmd`, commit, and push to `main` — the site rebuilds automatically.

## Citations
Export your Zotero library with Better BibTeX to `references.bib` (enable "Keep updated") and cite with `[@key]`.

## Custom domain
Settings → Pages → Custom domain, then add a CNAME DNS record pointing to `<user>.github.io`.
