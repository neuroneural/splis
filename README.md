# Sergey M. Plis

A small, buildless personal page at <https://splis.net/>.

## Edit and preview

Edit `index.html` for the biography and profile links, or `styles.css` for the layout. The portrait is in `assets/sergey-plis.jpg`.

Run `python3 -m http.server 8000` from this directory, then open <http://localhost:8000>.

## Publish

GitHub Pages serves the root of the `main` branch. Commit and push changes to publish them. `.nojekyll` keeps the site fully static; no dependencies or build step are required.

The custom domain is `splis.net`, declared in `CNAME` and in the repository's Pages settings. Apex DNS must point to GitHub Pages (`185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`); `www` should be a CNAME to `neuroneural.github.io`. HTTPS should be enforced after GitHub issues the certificate.
