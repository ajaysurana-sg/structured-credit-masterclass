# Structured Credit Masterclass

An interactive 36-slide masterclass on structured credit, securitisation, and capital relief — from digital SME origination to synthetic risk transfer, with the Indian regulatory lens.

By **Ajay Surana** — Co-founder, [Augury Insights](https://www.auguryinsights.com) · CRO, Infrarisk (an [Aurionpro](https://www.aurionpro.com) Company).

## Features

- 36 self-contained slides with interactive widgets (Waterfall Tycoon, Macro Shock simulator)
- 21 inline citations with hover tooltips and source links
- ⌘K / Ctrl+K full-text search across all slides
- Speaker notes mode (press `S`)
- Deep-linkable slides via URL hash (`#slide-22`)
- Print-friendly (Cmd/Ctrl+P → PDF handout)

## Stack

Single-file static HTML. No build step.

- Tailwind CSS (Play CDN)
- Alpine.js — reactive state
- KaTeX — math rendering
- Tippy.js + Popper — tooltips
- Google Fonts: Inter + Fraunces

## Deploy

```bash
git add .
git commit -m "deploy"
git push
```

Vercel auto-deploys on push to `main`.

## Keyboard shortcuts

| Key | Action |
|-----|--------|
| `→` / `Space` | Next slide |
| `←` | Previous slide |
| `Home` / `End` | First / last slide |
| `⌘K` / `Ctrl+K` | Search |
| `S` | Toggle speaker notes |
| `Esc` | Close overlays |

## License

© Augury Insights × Aurionpro. All rights reserved.
