# Yume Manga — single-page manga bookstore

A responsive, Japanese-inspired manga storefront built with plain HTML, CSS and JavaScript.

## Run it

1. Extract `yume-manga-store.zip`.
2. Open `index.html` in a modern browser. No build step or package installation is required. The cover images are embedded in the HTML, so they still display if your file viewer does not resolve the `assets` folder.
3. For the most reliable local testing, run a small static server from this folder:

   ```bash
   python -m http.server 8000
   ```

   Then visit `http://localhost:8000`.

## Included

- Responsive home page, genre shortcuts, searchable/sortable catalogue and manga cover gallery.
- Cover artwork for all eight books, based on the reference images supplied for this project.
- Floating sakura petals, scroll progress, parallax hero, reveal-on-scroll and a moving cover rail.
- Shopping cart with quantity controls and browser-local cart persistence.
- Demo registration/login, newsletter and checkout interactions.
- Creator credit in the footer.

## Image preview

- `cover-preview.jpg` shows all eight manga covers included in the site.
- `assets/covers/` contains the original JPG cover files.
- The main `index.html` also embeds all cover images so local previews do not depend on relative image paths.

## Demo limitations

This is a front-end demo. Registration and cart data are stored in this browser only. Checkout does not process payments or place a real order; there is no server, inventory system, email verification, or payment gateway. Do not use a real password. Google Fonts are loaded online; system fallbacks are used if unavailable.

## Project structure

- `index.html` — complete website source (HTML, CSS and JavaScript).
- `assets/covers/` — local manga cover images used by the catalogue and scrolling gallery.
