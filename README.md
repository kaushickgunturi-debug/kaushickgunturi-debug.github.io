# Personal Portfolio — Kaushick Varma Gunturi

This repo contains a static website suitable for **GitHub Pages**.

## Quick Deploy (User/Org site)
1. Create a new repo named **`<your-username>.github.io`** (replace with your GitHub username).
2. Upload the files in this folder (or push via Git).
3. Commit to the **`main`** branch. GitHub Pages will publish automatically at `https://<your-username>.github.io`.

## Deploy as a Project Site (optional)
1. Create any repo name, push these files.
2. In **Settings → Pages**, set **Branch: `main` / folder: `/root`**.
3. Your site will publish at `https://<your-username>.github.io/<repo-name>/`.

## Customize
- Replace `assets/profile-placeholder.png` with your real photo (keep the same filename).
- Update links (Résumé, LinkedIn, GitHub) in `index.html`.
- To use a **custom domain**, add a `CNAME` file with your domain and point DNS to GitHub Pages per the docs.

## Local Preview
Open `index.html` directly in your browser or use a simple HTTP server:

```bash
python3 -m http.server 5173
# then open http://localhost:5173
```

## Optional Enhancements
- Add analytics (e.g., GA4) by inserting the snippet in `<head>`.
- Wire a contact form with Formspree or Netlify Forms.
- Convert to React/Vite later; deploy via GitHub Actions.
