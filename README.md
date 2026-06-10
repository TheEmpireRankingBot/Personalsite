# Personal Site — Chua Bo Hao

The personal site of **Chua Bo Hao** — a Singapore-based maker who vibecodes
tools he wishes existed: apps for calmer investing, deeper focus and everyday
discipline, built with AI as a pair programmer and polished by hand.

## Stack

- Hand-written **HTML / CSS / vanilla JS** — no framework, no build step.
- Fonts: [Fraunces](https://fonts.google.com/specimen/Fraunces) (display serif)
  + [Inter](https://fonts.google.com/specimen/Inter) (body), via Google Fonts.
- Aesthetic: deep slate + tactical gold, matching the rest of the project
  fleet (Grand Horizon, ULTRACODE).
- Accessible and responsive: semantic landmarks, `prefers-reduced-motion`
  support, no-JS fallback for scroll reveals, mobile navigation, JSON-LD
  `Person` schema for SEO.

## Run locally

It's a static site — any server works:

```bash
python -m http.server 8000
# → http://localhost:8000
```

Or just open `index.html` in a browser.

## Deploy (GitHub Pages)

1. Repo **Settings → Pages**.
2. Source: *Deploy from a branch* → `main` → `/ (root)`.
3. The site goes live at `https://theempirerankingbot.github.io/Personalsite/`.

## Structure

```
index.html   — single-page site (hero, about, projects, experience, background, contact)
styles.css   — design system + layout
script.js    — nav state, mobile menu, scroll reveals, section spy
```
