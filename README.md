# ACE Site

Marketing website for **ACE — Your Guy for Everything Digital**.

## What Is This?

A static single-page marketing site for ACE, built with vanilla HTML/CSS/JS. No framework, no build step — just open `index.html`.

## Run Locally

```bash
# Any static file server works. For example:
npx serve .
# or
python3 -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000).

## Deploy on Vercel

1. Import this repo at [vercel.com/new](https://vercel.com/new)
2. Select the `AlaudaAI/ace-site` repository
3. Framework Preset: **Other** (auto-detected via `vercel.json`)
4. Click **Deploy**

That's it — no build command or output directory config needed. The included `vercel.json` handles everything.

Alternatively, deploy from the CLI:

```bash
npx vercel --prod
```
