# LATAM X — Landing Page (test)

A simple static "coming soon" landing page for LATAM X, a curated marketplace
concept connecting Latin American designers, artisans, and artists with
European consumers.

This is a **static site** — plain HTML + Tailwind CDN, no build step, no
backend. The contact form on the page is a visual demo only (it doesn't
send or store anything).

## Run it locally

No install needed — just serve the folder:

```bash
python3 -m http.server 8765
```

Then open http://localhost:8765

## Deploy to Vercel

### Option A — Import from GitHub (recommended)
1. Go to [vercel.com/new](https://vercel.com/new)
2. Import this repository: `ricardosegoviat/latam-x-landing-test`
3. Leave all settings as default (Framework Preset: **Other**, no build
   command, no install command) and click **Deploy**.
4. Vercel will auto-deploy again on every push to `main`.

### Option B — Vercel CLI
```bash
npx vercel login
npx vercel --prod
```

## Project structure

```
.
├── index.html    # the entire site — hero + demo contact form
├── vercel.json   # deployment config (clean URLs)
└── README.md
```
