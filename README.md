# Drain Cleaning Santa Clarita CA

Professional drain cleaning, hydro jetting, sewer camera inspection, and related services website built with Astro and deployed on Cloudflare Pages / Workers.

**Live site:** https://draincleaningsantaclaritaca.com

## Features

- Fully responsive, mobile-friendly design
- Service pages: Drain Cleaning, Clog Removal, Sewer Line Service, Preventive Maintenance, Camera Inspection
- Service Areas page with embedded Google Map
- Contact page with form and map pinpointing 25800 Turquesa Dr, Santa Clarita, CA 91355
- SEO-ready (sitemap via @astrojs/sitemap, robots.txt, meta tags, canonical URLs)
- Cloudflare adapter for Pages / Workers deployment
- Updated color scheme (teal primary + orange accent)

## Commands

| Command | Action |
| --- | --- |
| `npm install` | Install dependencies |
| `npm run dev` | Start local dev server |
| `npm run build` | Build production site to `./dist/` |
| `npm run deploy` | Deploy to Cloudflare |
| `npm run preview` | Preview production build locally |

## Deploy to Cloudflare Pages

1. Connect the repository to Cloudflare Pages (or use Wrangler).
2. **Build command:** `npm run build`
3. **Build output directory:** `dist`
4. Framework preset: Astro (or None).
5. Node.js version: 22 or higher recommended.

Alternatively with Wrangler:

```bash
npm run build
npm run deploy
```

## Customize

- Update phone, email, and address in `src/consts.ts`
- Replace Formspree form ID in `src/pages/contact.astro` with your own endpoint
- Colors and styling are in `src/styles/global.css`

## Location

25800 Turquesa Dr  
Santa Clarita, CA 91355  
USA
