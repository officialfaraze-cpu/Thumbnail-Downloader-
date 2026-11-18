# Thumbnail Downloader

Paste a YouTube link and download its thumbnail in every available size.

## Files
- `index.html`, `style.css`, `script.js` – the website (no build step)
- `api/download.js` – Vercel serverless function that makes the "Download" button save the file

## Deploy (GitHub + Vercel)
1. Create a new repository on GitHub and upload all these files (keep the `api` folder).
2. Go to vercel.com → **Add New… → Project** → import the repository.
3. Framework Preset: **Other**. Leave build settings empty. Click **Deploy**.
4. Your site is live at `https://<project>.vercel.app`. Add a custom domain under Settings → Domains.

## Run locally
```
npm i -g vercel
vercel dev
```
