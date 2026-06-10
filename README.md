# chuabohao.com — Personal Site

The personal site of **Chua Bo Hao** — Singapore-based builder, operator and
strategist. Operations-trained (facilities management), self-taught in
software, shipping AI-powered finance and productivity tools.

## Stack

- Hand-written **HTML / CSS / vanilla JS** — no framework, no build step.
- Fonts: [Fraunces](https://fonts.google.com/specimen/Fraunces) (display serif)
  + [Inter](https://fonts.google.com/specimen/Inter) (body), via Google Fonts.
- Aesthetic: *executive cyber-classicist* — deep slate, tactical gold,
  editorial typography. Consistent with the rest of the venture fleet.
- Accessible and responsive: semantic landmarks, `prefers-reduced-motion`
  support, mobile navigation, JSON-LD `Person` schema for SEO.

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
index.html   — single-page site (hero, about, ventures, experience, credentials, contact)
styles.css   — design system + layout
script.js    — nav state, mobile menu, scroll reveals, section spy
```
