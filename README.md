# cartlet-site

Marketing site + privacy policy for [Cartlet](https://play.google.com/store/apps/details?id=app.cartlet.android).

Pure static HTML/CSS — no build step.

- `/` — landing page (`index.html`)
- `/privacy/` — privacy policy
- `styles.css` — shared design system (matches the app's visual language)
- `*.png` — icon + screenshots, served from the site root

## Local preview

```sh
python3 -m http.server 8000
# visit http://localhost:8000
```

## Deploy

Vercel watches `main`. Push and it ships.
