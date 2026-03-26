# CreatorVerse — Marketing Playbook

Static slide deck: `index.html` + `creatorverse-playbook.css`. No build step.

## Run locally

Open `index.html` in a browser, or from this folder:

```bash
python3 -m http.server 8080
```

Then visit [http://localhost:8080](http://localhost:8080).

## Deploy on Vercel

1. Push this repo to GitHub (see below).
2. In [Vercel](https://vercel.com/new), import the repository.
3. Use defaults: **Framework Preset** “Other”, **Root Directory** `./`, no build command, **Output** not required (static files at repo root).

Or use the one-click flow (after the repo has content on GitHub):

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fayushrai-hub%2Fcreatorverse)

## Repository layout

| File | Role |
|------|------|
| `index.html` | Slides and structure |
| `creatorverse-playbook.css` | Styles and theme |
| `vercel.json` | Optional Vercel routing/URL preferences |
