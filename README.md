# Prosper Magara – portfolio

Personal website of Prosper Magara, biomedical and electrical engineer and PhD candidate at the University of Cape Town.

Live site: https://prospermagara.com (also served at https://prosper02.github.io/prosper1/)

## Stack

Plain HTML, CSS and JavaScript, no build step. Hosted on GitHub Pages from the `main` branch.

- `index.html` – the single-page site
- `css/site.css` – styles, light and dark theme
- `js/main.js` – theme toggle, mobile menu, scroll spy, contact form
- `assets/` – CV and paper PDFs
- `images/` – profile photo and field gallery

## Edit and preview locally

Open `index.html` in a browser, or serve the folder:

```
python -m http.server 8080
```

then visit http://localhost:8080.

## Custom domain

1. Add a `CNAME` file to the repository root containing only the domain (for example `prospermagara.com`).
2. At the domain registrar, add four `A` records for the apex pointing at GitHub Pages
   (185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153) and a `CNAME` record
   for `www` pointing at `prosper02.github.io`.
3. In the repository's Settings → Pages, enter the domain and tick "Enforce HTTPS" once the
   certificate has been issued.
