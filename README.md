# CarbonTrace ID — Static Site

This repository contains a simple static main page for CarbonTrace ID.

- Published (GitHub Pages): https://agungpramudhita.github.io/carbontraceid/

Quick local preview

1. From the project root run:

```bash
python3 -m http.server 8000 --directory /workspaces/carbontraceid
```

2. Open in your browser:

```bash
http://localhost:8000/index.html
```

Stop the server:

```bash
pkill -f "http.server 8000"
```

How to update the published site

- Edit `index.html` (or other files).
- Commit and push to `main`:

```bash
git add index.html README.md
git commit -m "Update site"
git push origin main
```

- This repository also has a `gh-pages` branch that was created and pushed. GitHub Pages will serve the site from:

```
https://agungpramudhita.github.io/carbontraceid/
```

Notes

- The "Hubungi Kami" button opens WhatsApp: `https://wa.me/6281334699967`.
- If the Pages site returns 404 after first push, wait 1–2 minutes and refresh.
- If you want a custom domain or automated CI deployment (Netlify/Vercel/GitHub Actions), tell me and I can add a workflow or instructions.
