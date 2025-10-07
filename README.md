# Pixi Playground

A small **PixiJS + TypeScript** showcase for promo-style mini games: responsive scene (letterboxing, DPR-aware), nine-slice UI, simple loader, and a few spritesheets (coins, character, ship) + tilemap.

## Features
- Crisp scaling that preserves a logical playfield
- Loader with progress using `@pixi/assets`
- Spritesheets: coins (5f), character (full directional set), particles
- Tilemap for quick level experiments

## Quick Start
```bash
# Node 18+
pnpm i && pnpm dev   # or: npm i && npm run dev
```
Open the local URL; the scene adapts to the window while keeping 16:9.

## Notes
- Assets are small and self-contained. Replace `/public/assets/*` with your own if needed.
- The code prefers clarity over size so it’s easy to extend (add scenes, UI, effects).
