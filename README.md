# Player One — a short gaming & consoles site

A single, self-contained `index.html`. No build step, no dependencies, no database.
All illustrations are hand-drawn SVG embedded in the page, so nothing breaks or "phones home."

## Deploy to Vercel — pick one

**1. Drag & drop (easiest)**
Go to https://vercel.com/new → drop this folder onto the page → Deploy. Done.

**2. Vercel CLI**
```bash
npm i -g vercel
cd gaming-site
vercel        # follow the prompts, then `vercel --prod` to go live
```

**3. GitHub**
Push this folder to a repo, then on Vercel click **Add New → Project**, import the repo,
and deploy. Vercel auto-detects it as a static site — no settings needed.

## Editing
Everything lives in `index.html` (HTML, CSS, and the SVG art are all in one file).
The color palette and fonts are defined as CSS variables at the top under `:root`.
