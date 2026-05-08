# Illy Zussman Real
Updated for Cloudflare Git deployment.
Static artist link page for **איליי זוסמן ריאל / Illy Zussman Real**.

## Public URL

Recommended canonical URL:

https://zeuschef.co.il/illy/

## Files

- `index.html` - main link-in-bio page
- `gallery.html` - photo gallery
- `assets/` - images and media assets
- `robots.txt` - crawler instructions
- `sitemap.xml` - basic sitemap
- `_redirects` - redirect `/illy` to `/illy/` where supported

## Cloudflare Pages settings

Use this repo as a static Cloudflare Pages project.

Recommended settings:

- Framework preset: None / Static HTML
- Build command: leave empty
- Build output directory: `/` or blank/root, depending on the Cloudflare UI
- Production branch: `main`

## Update flow

```bash
git add .
git commit -m "Update Illy site"
git push
```

Cloudflare Pages will deploy automatically after push when the repo is connected through Git integration.
