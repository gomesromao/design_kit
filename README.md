# Coconut VA — Design System

A single-page brand canvas for Coconut VA, modeled after the Claude design canvas: every brand element grouped into expandable rows you can click to inspect.

## Sections

- Foundations — brand & logos, iconography
- Type — display, headings, body & meta, eyebrow & stat
- Colors — navy & green core, talent halos, surfaces & pastels, semantic
- Spacing, radius & shadow
- Components — buttons, avatar stack, talent card, service cards, process steps, role chips, stat strip, CTA bar, pricing

## Local preview

Open `index.html` directly in a browser, or serve with any static server:

```bash
npx serve .
```

## Deploy (Vercel)

Zero-config. Connect this repo on https://vercel.com/new → Deploy.

Or via CLI:

```bash
npx vercel --prod
```

## Files

```
index.html              ← the canvas
tokens.css              ← design tokens (downloadable)
colors_and_type.css     ← same tokens, kept for preview file paths
assets/                 ← logos, icons, team & talent photos
preview/                ← per-element preview HTMLs (loaded as iframes)
vercel.json
```
