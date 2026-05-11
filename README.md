# apps.cetin.info

Static site listing apps built by Ahmet Çetin. Deployed via GitHub Pages at <https://apps.cetin.info>.

## Structure

- `index.html` — apps listing home
- `clipsmith/` — Clipsmith landing page (macOS clipboard utility)
- `assets/` — app icons and screenshots
- `styles.css`, `script.js` — shared site assets

## Local preview

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000/>.

## Deploy

Push to `main`; GitHub Pages serves from root. `CNAME` configures the custom domain. `.nojekyll` disables Jekyll processing.
