# PairsKee Global website preview

Standalone responsive website prototype built with HTML, CSS and vanilla JavaScript.

## Run locally
Open `index.html` in a browser, or run a local static server from this directory (for example `python -m http.server 8080`).

## Deploy
This project includes `vercel.json` SPA rewrites and can be deployed as a static site on Vercel or any static host.

## Important launch notes
- Contact and product-information forms currently open a pre-filled email to `jenny.ouyang@pairskee.com`; connect a secure form endpoint/CRM before production.
- Video Library uses sample YouTube embeds. Replace with approved PairsKee YouTube URLs before launch.
- Main product, conveyor, loading-operation and warehouse-sortation visuals have been replaced with image assets linked from the live PairsKee Global website. These are remote image URLs (not downloaded into the project), so they require the source website to remain accessible. Confirm image-use rights with PairsKee before public launch. The current public site exposes a limited set of clearly identifiable product and deployment images; several categories therefore reuse relevant PairsKee equipment imagery rather than showing unverified stock photography.
- Technical figures are presented as indicative and should be confirmed against current product datasheets before publication.
- Product pages are structured from the current public PairsKee product families; detailed SKU-specific specifications and brochures can be added when supplied.


## Image sourcing

The image references in `app.js` point to the public PairsKee Global WordPress media library. They were selected from the live homepage, telescopic belt conveyor product page and case-study content. If you want a fully self-contained deployment, provide the approved original media library or enable direct asset downloads so these remote images can be copied into `assets/images` and optimized locally.
