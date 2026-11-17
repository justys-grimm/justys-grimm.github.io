# Resume — Justys Grimm

Single-page resume site, served with GitHub Pages.

## Editing
All content lives in the `RESUME` object near the top of the `<script>` in `index.html`.
Reorder or hide sections with `RESUME.layout`.

## Deploy
Pushes to `main` publish automatically (Settings → Pages → Deploy from branch → `main` / root).

## Custom domain (later)
1. Add a `CNAME` file containing the domain (e.g. `example.com`).
2. At the registrar, point the apex domain to GitHub Pages A records
   (185.199.108.153, .109.153, .110.153, .111.153) and/or a `www` CNAME to `<user>.github.io`.
3. Settings → Pages → enable **Enforce HTTPS**.
