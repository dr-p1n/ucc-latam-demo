# UCC LATAM — Concept Pitch Demo

A single-page concept site built for a partner/investor pitch (via Loom walkthrough) for **UCC (Ultimate Combat Challenge)**, Panama's oldest MMA promotion. The pitch: a revenue-share model — PPV per event plus a cut of streaming, ecommerce, and ad sales — with no upfront payment from UCC.

**Live demo:** _add your `*.pages.dev` URL here after deploying_

## What's in it

- **Inicio** — home/hero, next-event PPV banner, live ticker with sponsor odds badge
- **Streaming** — PPV/live viewing concept
- **Archivo** — a curated, Netflix/UFC-compilation-style fight archive (monthly picks, thematic rows: Top Nocauts, Sumisiones, Clásicos) with YouTube-embeddable video modals
- **Tienda** — ecommerce concept with filters (availability, price, offers, category) and a working cart
- **Podcast / Las Odds** — episode player plus a display-only "Tendencias en Vivo" panel (most popular picks, highest-payout picks) — informational only, no on-site wagering
- **Entrena con Nosotros** — gym schedule plus a "Únete a UCC" section for pro-fighter applications and free trial-class booking for amateurs

## Stack

Vanilla HTML/CSS/JS, single file, zero build step, zero dependencies (Google Fonts loaded via CDN link). Deployed as a static site.

## Local preview

Just open `index.html` in a browser — no server or build required.

## Deploying (Cloudflare Pages)

1. Push this repo to GitHub.
2. In the Cloudflare dashboard: **Workers & Pages → Create → Pages → Connect to Git**, select this repo.
3. Build settings: **Framework preset: None**, **Build command: (blank)**, **Build output directory: /**.
4. Deploy. Cloudflare assigns a `*.pages.dev` URL automatically; every push to `main` redeploys.

Alternative (CLI, no GitHub connection needed):

```bash
npx wrangler pages deploy .
```

## Notes

This is a concept/pitch artifact, not a production product — some images are placeholder/stand-in assets, and the fight archive video embeds use a neutral placeholder video ID until real footage is available.
