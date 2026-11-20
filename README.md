# Crunchy Pizza

One-page website for Crunchy Pizza, Sahiwal. Single self-contained `index.html` (no build step).

## Features
- Hero, full menu (tabs), combo deals, signature specials, delivery, service areas, testimonials, pricing, FAQ
- Multi-item order builder that sends the order to WhatsApp (0322-1699267)
- Black and amber theme taken from the printed menu, responsive for desktop and mobile

## Run locally
Open `index.html` in a browser, or serve the folder:

    python3 -m http.server 8000

## Project layout
- `index.html` – the whole site (HTML, CSS, JS, embedded logo)
- `assets/` – original menu images used as the source for prices and items

## Editing content
- Menu items and prices: the `MENU` and `DEALS` objects in the `<script>` at the bottom of `index.html`
- Order catalogue (`CAT`) is built from the same data
- Phone / WhatsApp number: search for `03221699267` and `923221699267`

## To do
- Replace placeholder testimonials, FAQ answers and service area names with real ones
