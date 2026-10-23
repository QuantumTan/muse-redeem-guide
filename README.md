# How to redeem a Muse invite code

A single-page, static blog guide. No framework, no build step, no trackers.

## Files
- `index.html` — the whole site (inline CSS/JS), with SEO meta, Open Graph /
  Twitter cards, and HowTo + FAQ structured data (JSON-LD)
- `robots.txt` — allows all crawlers, points to the sitemap
- `sitemap.xml` — the single page, for search engines
- `og-image.png` — 1200×630 social/search preview image
- `favicon.svg` — site icon
- `vercel.json` — static deployment config

## Getting indexed
SEO tags make the page *eligible* to rank; they do not guarantee a position.
To speed up discovery: verify the site in Google Search Console, submit
`sitemap.xml`, and use URL Inspection → Request Indexing for the homepage.
Indexing a brand-new site typically takes days to weeks, and rankings
depend on search demand and competition, not on tags alone.

## Deploy to Vercel via GitHub
1. Push this folder as a GitHub repository.
2. In Vercel: New Project → Import the GitHub repository.
3. Framework preset: Other. Build command: none. Output directory: `.`
4. Deploy. Every later push to `main` redeploys automatically.

## Editorial notes
- Reward amount is intentionally not stated as a guarantee — Muse's
  redemption screen supplies the offer terms for each account.
- Redemption paths: mobile `Settings → Redeem token` (first 48 hours);
  web `Settings → General → Usage → Redeem invite code` on muse.ai.
- Availability stated as US and Canada, per Muse's published information.
