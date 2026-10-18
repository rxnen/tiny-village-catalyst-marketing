# Tiny Village Catalyst — marketing site

A standalone marketing page for **Tiny Village Catalyst**, a free, open-source guide that
helps communities turn their motivation into an executable tiny-village plan through siting,
permitting, budgeting, and community-organizing assistance. A project of
[Tiny Village Spirit](https://tinyvillagespirit.com).

## Running locally

It's a static site — no build step. Serve the folder with any static file server:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Structure

- `index.html` — the full page: sticky nav, a recolored [MapLibre](https://maplibre.org/)
  hero map, the problem/what-it-does sections, a scroll-pinned "Follow our blueprint"
  stepper, audience, about, and a get-involved band.
- `brand.css` — the Tiny Village Spirit brand kit (color tokens + component classes),
  with the page's olive-green overrides applied in `index.html`.
- `assets/` — `catalyst-logo.svg`, `favicon.svg`, and photography.

## Photos

`assets/how-1.jpg` and `assets/village-photo.jpg` are in place. Four blueprint photos —
`how-2.png`, `how-3.jpg`, `how-4.jpg`, `how-5.jpg` — are referenced by `index.html` but not
yet committed; until they're added, those slots render a styled placeholder. Drop the files
into `assets/` to complete the page.

## License

Code released under CC BY-NC 4.0.
