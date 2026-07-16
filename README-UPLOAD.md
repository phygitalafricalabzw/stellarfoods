# Stellar Foods — Upload to cPanel / GoDaddy / Any Static Host

## Quick upload (cPanel File Manager)

1. Log in to cPanel → open **File Manager**.
2. Navigate to `public_html/` (or the folder for your domain / subdomain).
3. Click **Upload** and upload `stellar-foods-cpanel.zip`.
4. Right-click the uploaded zip → **Extract** → extract into `public_html/`.
5. Delete the zip file after extraction.
6. Visit your domain — the site is live.

## What's included

- `index.html` — home page
- `products/<slug>/index.html` — one page per product (10 total)
- `404.html` — shown for unknown URLs
- `assets/` — CSS + JS bundles (hashed filenames, safe to cache)
- `images/` — all product photos and hero art
- `.htaccess` — pretty URLs, custom 404, gzip + long cache headers

## Notes

- No server code required. This is a pure static site.
- Google Fonts loads from Google's CDN (internet required). Ask if you'd like the fonts bundled locally instead.
- To update: rebuild in Lovable, re-export, re-upload.
