# КОРОВА SMP

Modern cinematic Minecraft SMP landing page built with React + Vite + TypeScript.

## Run

```bash
npm install
npm run dev
```

## Production build

```bash
npm run build
npm run preview
```

## Server configuration

Edit `src/config/server.ts` to change the server name, IP, port, version, online count and social links.

## Content

Rules live in `src/data/rules.ts` and FAQ entries live in `src/data/faq.ts`.

## Assets

All supplied visual assets are kept in `src/assets/` and used by the page. `reference.png` is the supplied composition reference and is intentionally not rendered as site content.

> Note: the provided asset package does not contain a standalone cow-logo file, so the navbar/footer mark uses a crop of the supplied `hero.webp` rather than generating a new image.
