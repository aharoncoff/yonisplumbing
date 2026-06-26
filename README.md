# Yoni's Plumbing Static Website

A small static website for yonisplumbing.com. It has no backend, no build step, and no external dependencies.

## Files

- `index.html` — page content and SEO metadata
- `styles.css` — responsive styling
- `script.js` — current year in footer
- `favicon.svg` — browser icon
- `assets/` — ad image and optimized image sizes

## Deploy on Cloudflare Pages

1. Put these files in a GitHub repository, or upload the folder directly through Cloudflare Pages.
2. In Cloudflare, go to **Workers & Pages** → **Create** → **Pages**.
3. Select the repo or direct upload.
4. Build settings:
   - Framework preset: `None`
   - Build command: leave blank
   - Build output directory: `/` if uploading this folder as the project root
5. Add the custom domain `yonisplumbing.com` in the Pages project settings.
6. Make sure DNS points to Cloudflare and that the Pages custom domain is active.

## Editing

Change phone numbers, service area, and text directly in `index.html`.
