# Budget-Tracker

![Pages Deploy](https://github.com/eriktong/Budget-Tracker/actions/workflows/pages.yml/badge.svg) ![Last commit](https://img.shields.io/github/last-commit/eriktong/Budget-Tracker) ![License](https://img.shields.io/badge/license-MIT-informational)

**Live Demo:** [https://eriktong.github.io/Budget-Tracker/](https://eriktong.github.io/Budget-Tracker/)

> Short description: _Update this one-liner to summarize the app in a sentence._

---

## Features
- Clean starter with Static HTML/CSS/JS
- Deployed on **GitHub Pages** via Actions
- Production build output: `.`
- Mobile-friendly layout _(if applicable)_
- Routing-ready _(SPA)_  


---

## Quick Start

### Prerequisites
- Node.js LTS (or none if pure static)
- npm (bundled with Node)

### Local Dev
```bash
# install
npm install

# start dev server
npx serve .
```

### Build
```bash
(none)
```

> Build output goes to **`.`**.

---

## Deploy (GitHub Pages)

This repo deploys using **Actions** on pushes to `main`.

- Workflow: `.github/workflows/pages.yml`  
- Public URL: **https://eriktong.github.io/Budget-Tracker/**  
- SPA fallback: `404.html` is created during the workflow so React Router routes work on refresh.

If something breaks:
1. Verify the latest workflow run is green.
2. For CRA, ensure `"homepage": "https://eriktong.github.io/Budget-Tracker/"` exists in `package.json`.
3. For Vite, ensure `base: "/Budget-Tracker/"` in `vite.config.*`.

---

## Screenshots

> Put images under `docs/` and reference them here.

| Screen | Image |
|---|---|
| Home | ![Home](docs/screenshot-1.png) |

---

## Tech Stack
- Static HTML/CSS/JS
- HTML, CSS, JavaScript
- GitHub Actions + GitHub Pages

---

## Project Structure (high level)


---

## Environment Variables
> If none, delete this section. Otherwise, document them like:

| Variable | Example | Required | Description |
|---|---|---|---|
| `VITE_API_URL` | `https://api.example.com` | No | API base URL |

---

## Roadmap / TODO
- [ ] Add better screenshots
- [ ] Fill in real description & features
- [ ] Audit Lighthouse (performance, a11y, SEO)
- [ ] Add tests (Vitest/Jest) _(optional)_
- [ ] Add CI for lint/test _(optional)_

---

## License
This project is licensed under the **MIT License**. See [LICENSE](LICENSE).

---

## Maintainer
- **Erik Tong** — feedback & issues via GitHub
