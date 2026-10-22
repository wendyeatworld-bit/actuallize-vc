# actualize.vc

Homepage for Actualize, a seed fund. One static file, no build step.

## Files
- `index.html` — the whole site (styles inline)
- `CNAME` — tells GitHub Pages to serve at actualize.vc
- `.nojekyll` — skip Jekyll processing

## Deploy on GitHub Pages
1. Push this repo to GitHub (public or private on a paid plan).
2. Repo → Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
3. Under "Custom domain" enter `actualize.vc` and tick "Enforce HTTPS" once the certificate is issued.

## DNS (at your registrar)
- `A` records for `@` → 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
- `CNAME` for `www` → `<your-github-username>.github.io`

## Editing
Change the text in `index.html` and push. Pages redeploys in about a minute.
