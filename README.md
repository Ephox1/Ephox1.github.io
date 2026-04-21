# nevinbruce.dev — Personal Portfolio

A single-file, zero-build interactive resume for **Nevin Bruce**.
Vanilla HTML / CSS / JS. Deploys straight to GitHub Pages.

**Live:** https://ephox1.github.io

## Features

- Filter bullets by skill (OR logic, live count per chip)
- Light / dark theme toggle — persists to `localStorage`, respects system preference
- Smooth reflows via the View Transitions API (CSS fallback on older browsers)
- Adaptive Card demo with "View JSON" toggle
- Print-friendly stylesheet (clean black-on-white)
- Works without JavaScript — all resume content is server-rendered HTML

## Deploy to GitHub Pages (3 steps)

1. Push this repo to GitHub as `Ephox1/Ephox1.github.io` (exactly that name makes it your user site).
2. In the repo on github.com, open **Settings → Pages** and set **Source** to **Deploy from a branch**, Branch **`main`** / root (`/`).
3. Wait ~1 minute, then visit **https://ephox1.github.io**.

## Drop your PDFs here

Place the two resume PDFs next to `index.html`, using these exact filenames:

```
/Nevin_Bruce_Resume_Light.pdf
/Nevin_Bruce_Resume_Dark.pdf
```

The "Download Resume" button in the hero links directly to both.

## Files

```
index.html                       — the whole site
Nevin_Bruce_Resume_Light.pdf     — (add manually)
Nevin_Bruce_Resume_Dark.pdf      — (add manually)
README.md                        — this file
```
