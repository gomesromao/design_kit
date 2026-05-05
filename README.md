# Coconut VA — Design System

A single-page brand canvas for Coconut VA, modeled after the Claude design canvas: every brand element grouped into expandable rows you can click to inspect.

## Sections

- Foundations — brand & logos, iconography
- Type — display, headings, body & meta, eyebrow & stat
- Colors — navy & green core, talent halos, surfaces & pastels, semantic
- Spacing, radius & shadow
- Components — buttons, avatar stack, talent card, service cards, process steps, role chips, stat strip, CTA bar, pricing

## Local preview

Open `public/index.html` directly in a browser, or serve with any static server:

```bash
npx serve public
```

## Deploy (Vercel)

Already configured. Vercel auto-detects `public/` as the static output. The `vercel.json` at the repo root handles clean URLs.

```bash
npx vercel --prod
```

Or connect this repo on https://vercel.com/new and click Deploy.

## Files

```
public/
  index.html              ← the canvas
  tokens.css              ← design tokens (downloadable)
  colors_and_type.css     ← same tokens, kept for preview file paths
  assets/                 ← logos, icons, team & talent photos
  preview/                ← per-element preview HTMLs (loaded as iframes)
vercel.json
```
