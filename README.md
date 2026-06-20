# Sri Raghavendra Tiffens — Deployment

This is a static single-page site (`index.html`) for Sri Raghavendra Tiffens. Below are two simple ways to deploy it to Vercel.

## Option A — Vercel CLI (fast)

1. Install the Vercel CLI (requires Node.js/npm):

```bash
npm install -g vercel
```

2. Login to Vercel:

```bash
vercel login
```

3. From the project folder (where `index.html` lives) run:

```bash
cd /home/arya/Desktop/SRF
vercel --prod
```

Follow the interactive prompts (project name, scope). For a static site you can accept the defaults.

## Option B — GitHub + Vercel Dashboard

1. Push the project to a GitHub repository.
2. In the Vercel dashboard, choose "New Project" → Import from GitHub → select the repo.
3. For a static site, set the framework preset to "Other" and root to `/` (repository root). Deploy.

## Notes
- If you want a fixed domain, add it in the Vercel dashboard and follow DNS instructions.
- I can add a `vercel.json` file to pin the static build settings (below).

---
_If you'd like, I can create the GitHub repo and push these files for you or add a `vercel.json` now._
