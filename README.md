# usaindiacfo.com — site walkthrough

Automated walkthrough, sitemap, and responsive-design showcase of **usaindiacfo.com**.

## What's inside

| File / folder | What it is |
|---|---|
| `index.html` | Combined report — embed videos, stats, sitemap, performance |
| `walkthrough.webm` | Full-site tour video with an overlay banner (page / URL / action / viewport) |
| `sitemap.html` · `sitemap.json` | Route graph with titles, H1s, meta descriptions, link counts, load times |
| `screenshots/{light,dark}/{mobile,tablet,laptop,desktop}/` | Full-page PNGs — 16 routes × 2 themes × 4 viewports |
| `responsive/responsive.html` | Gallery page — every route across all four viewports |
| `responsive/responsive-showcase.webm` | Live viewport-resize video for key routes |
| `meta.json` | Run metadata — mode (dev/prod), base URL, timestamp |

## View

Open `index.html` directly in any modern browser, or host the folder as a static site:

- **GitHub Pages**: push this repo, then enable Pages → Source: `main` branch, `/ (root)`
- **Any static host**: serve the folder — everything uses relative paths

## Regenerate

This repo publishes the output only. Source for the generator lives in the
main [`usaindiacfo.com`](https://github.com/bngadvisors/usaindiacfo.com)
repo at `scripts/site-walkthrough/`. Run `npm run walkthrough` there, then
copy the contents of `scripts/site-walkthrough/output/` into this repo and
push.
