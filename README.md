# EZRV Solutions — Site Map Presentation

A single-page, client-facing presentation of the proposed information architecture
for the redesigned [ezrvsolutions.com](https://ezrvsolutions.com), built for the
recently rebranded EZRV Solutions and presented by Edington Studio.

Plain HTML/CSS, no build step, no framework — open `index.html` directly or serve
it with any static file server.

```
index.html   Everything: markup, styles, content
```

## What's in here

- **Cover** — Edington Studio title treatment (cream/blue, Big Shoulders Display + Inter),
  framing the deliverable before the client gets into EZRV's own brand system.
- **EZRV-branded site map** — header, hero, legend, and scope stats, using EZRV's
  official brand guidelines: Electric Blue `#0083FC`, Deep Navy `#0E213D`, Bebas Neue
  headlines, Space Mono labels, topographic-line texture on dark sections.
- **Sections 01–02 (Home, Products)** — fully built out from the approved sitemap plan.
- **Sections 03–09** — placeholders (clearly marked "Awaiting Content") until the rest
  of the sitemap plan is dropped in; they use the same card system so they'll match
  once filled in.
- **Customer Journeys** — Discover → Purchase → Support, the three paths the whole
  map is organized around.
- **UX Notes** — the reasoning behind a few structural decisions, for a non-technical
  client audience.

## Local preview

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Deploy

Static file, zero config. GitHub Pages, Netlify, or Vercel all work by pointing at
the repo root with no build command.

## Design system notes

- Colors, type, and voice come from EZRV Solutions' official brand guidelines.
- The Edington Studio cover uses colors sampled from edington.co (`--ed-blue`,
  `--ed-cream` in `index.html`) — swap those variables if the studio's palette changes.
- Both brand systems are CSS custom properties at the top of the `<style>` block,
  so either can be retuned without touching markup.
