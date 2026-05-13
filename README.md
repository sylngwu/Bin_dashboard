# BIN Portfolio Dashboard

Single-page dashboard for a 10-BIN portfolio across Thredd and FIS.

## Run locally

Open `index.html` in a browser, or run a static server:

```bash
python3 -m http.server 8080
```

## Deploy on Vercel

1. Push this folder to a Git repo.
2. Import the repo in Vercel.
3. Vercel detects a static project automatically.
4. `vercel.json` rewrites all routes to `index.html` for SPA behavior.

No build step required.
