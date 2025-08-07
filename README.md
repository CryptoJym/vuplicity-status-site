# Vuplicity MVP — Executive Status Site

Static, executive‑friendly snapshot: what’s done, impact, current status, what’s next, risks. No live data calls.

## Local preview

```bash
python3 -m http.server 8788 --directory .
open http://localhost:8788
```

## Deploy

### GitHub
1. Create a new repo (e.g., `vuplicity-status-site`).
2. Push this folder as the repo root.

### Vercel
- Root Directory: `/` (repo root)
- Build Command: none
- Output Directory: `/`
- Framework preset: Other (Static)

Or use CLI:
```bash
vercel deploy --prod --yes --confirm
```
