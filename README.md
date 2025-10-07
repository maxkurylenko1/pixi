# Promo Campaign Playground · PixiJS + TypeScript

Small, focused demo for **PixiJS** promo-style mini games. It shows crisp **responsive scaling** (1280×720 letterbox, DPR-aware), a 4‑layer **parallax** background, a **nine‑slice** UI panel, and tiny **spritesheets** (coin + ship) with a couple of **particle** textures.

## Features

- Logical 1280×720 scene with letterboxing (no blur, no scrollbars)
- Nine-slice panel (96×96, 16px margins) for scalable HUD/UI
- Spritesheets: coin (8×64), ship (4×64) + simple particles
- Self-contained, procedurally generated art

## Quick Start

```bash
# Node 18+
pnpm i && pnpm dev   # or: npm i && npm run dev
```

Open in the browser; the scene adapts to the window while keeping 16:9.

## Assets & License

All images in `public/assets/` were generated for this demo and can be used as CC0/MIT in experiments. Code is MIT. If you add third‑party assets, verify their licenses and credit authors.
