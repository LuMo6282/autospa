# L&L Autospa

Marketing site for **L&L Autospa** — Mercer Island auto detailing.

Static HTML/CSS, no build step. Deployable to any static host.

## Run locally

```sh
python -m http.server 9123
```

Open http://localhost:9123/

## Deploy to Vercel

1. Push this repo to GitHub.
2. Import the repo on https://vercel.com/new.
3. Framework preset: **Other** · Build command: *(empty)* · Output directory: `.`
4. Deploy.

A custom domain (e.g. `mercerautospa.com`) can be attached from the Vercel project settings.

## Edit prices / copy

All copy lives in [`index.html`](./index.html). Tier prices are in the `.size-prices` definition lists inside each `.card`. Update the numbers there and redeploy.
