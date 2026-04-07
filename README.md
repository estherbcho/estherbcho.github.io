# estherbcho.github.io

Personal portfolio website for **Esther B. Cho** — hosted for free via GitHub Pages with no custom domain required.

**Live site:** [estherbcho.github.io](https://estherbcho.github.io)

## What This Is

A single-page portfolio showcasing Esther's career in influencer marketing, content strategy, and digital media. Built as a static site (HTML + CSS) so it loads fast, requires no backend, and deploys automatically when changes are pushed to `main`.

## Site Structure

```
estherbcho.github.io/
├── index.html   ← the portfolio page (what visitors see)
├── style.css    ← all styling
└── README.md    ← this file (only visible on GitHub)
```

## Sections

- **Hero** — name, tagline, and short summary with CTA buttons
- **About Me** — detailed bio with photo placeholder and stats (10+ years, 15+ brands, 12+ roles)
- **Brand Marquee** — scrolling banner of major clients (Uber, Apple, Intel, Microsoft, Red Bull, L'Oreal, etc.)
- **Experience** — 6 featured roles in a 2-column card grid + 6 earlier roles behind a "Show More" toggle
- **Skills** — 4 category cards (Strategy, Influencer & Content, Media & Digital, Leadership)
- **Education** — placeholder (needs real info)
- **Contact** — LinkedIn + placeholder email

## How to Update

1. Clone the repo:
   ```bash
   git clone https://github.com/estherbcho/estherbcho.github.io.git
   ```
2. Edit `index.html` and/or `style.css`
3. Commit and push to `main`:
   ```bash
   git add -A
   git commit -m "describe your change"
   git push
   ```
4. GitHub Pages deploys automatically — changes go live within a few minutes

## Placeholders to Replace

These still have dummy content:

| What | Where in `index.html` | Replace with |
|------|----------------------|--------------|
| Photo | `.photo-placeholder` div | An `<img>` tag with a real headshot |
| Education | `#education` section | Real school names, degrees, and years |
| Email | `mailto:placeholder@email.com` | Real contact email |

## Tech Stack

- **HTML + CSS** — no frameworks, no JavaScript dependencies
- **Google Fonts** — DM Sans (body) + Playfair Display (headings)
- **GitHub Pages** — free hosting, auto-deploys from `main` branch

## Links

- [Live Site](https://estherbcho.github.io)
- [LinkedIn](https://www.linkedin.com/in/estherbcho/)
