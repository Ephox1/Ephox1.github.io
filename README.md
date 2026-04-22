<div align="center">

# ephox1.github.io

**Personal portfolio — an interactive, filterable web version of my resume.**

### 👉 [Click here to check it out](https://ephox1.github.io/) 👈

[![Live](https://img.shields.io/badge/live-ephox1.github.io-e8755c?style=flat-square&logo=githubpages&logoColor=white)](https://ephox1.github.io)
[![Deploy](https://img.shields.io/badge/GitHub%20Pages-deployed-2ea44f?style=flat-square&logo=github)](https://github.com/Ephox1/Ephox1.github.io/deployments)
[![No build step](https://img.shields.io/badge/build-none-17120e?style=flat-square)](#stack)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue?style=flat-square)](LICENSE)

</div>

---

A single `index.html` — no framework, no build step, no tracking. Readable at ~23&nbsp;KB, deploys via GitHub Pages on push to `main`, and reflows cleanly on mobile and in print.

## Features

- **Skill filter chips** — click to show only the experience bullets tagged with a given skill. Multi-select uses OR logic with live per-chip counts.
- **Light / dark theme** — respects `prefers-color-scheme`, persists to `localStorage`, animated via the View Transitions API with a CSS fallback.
- **Print-ready** — a dedicated `@media print` stylesheet strips the chrome to a clean black-on-white layout.
- **Works without JavaScript** — the full resume is server-rendered HTML. JS only progressively enhances with filtering and the theme toggle.

## Stack

- HTML, CSS, vanilla JavaScript — no build tools, no dependencies
- [Fraunces](https://fonts.google.com/specimen/Fraunces) (display) and [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) (metadata) via Google Fonts
- [GitHub Pages](https://pages.github.com/) for hosting
- No frameworks, no analytics, no trackers

## Structure

```
index.html                     site + inline CSS/JS
Nevin_Bruce_Resume_Light.pdf   static download
Nevin_Bruce_Resume_Dark.pdf    static download
LICENSE
README.md
```

## Run locally

```bash
git clone https://github.com/Ephox1/Ephox1.github.io
cd Ephox1.github.io
python -m http.server 8000
# open http://localhost:8000
```

Or just open `index.html` in a browser — it works offline.

## Deploy

Any change pushed to `main` is live at [ephox1.github.io](https://ephox1.github.io) within about a minute.

## License

[MIT](LICENSE) &copy; Nevin Bruce.

## Contact

**Nevin Bruce** — Lead, Executive Social Media Care
[nevin@phoxden.com](mailto:nevin@phoxden.com) &nbsp;·&nbsp; [github.com/Ephox1](https://github.com/Ephox1)
