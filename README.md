# M Bilal Khalid — AI/ML Engineer Portfolio

A modern, dark-themed single-page portfolio website for an AI/ML Engineer specializing in **Retrieval-Augmented Generation (RAG)** and **multilingual NLP systems**.

![Portfolio Preview](images/background.png)

## Overview

This repository contains a static, self-contained portfolio website built with pure HTML and CSS (no build step required). It showcases professional experience, technical skills, featured projects, education, and certifications with a responsive, animated UI.

## Features

- **Hero Section** — Animated floating cards highlighting RAG, hybrid retrieval, and AI generation.
- **Stats Bar** — Quick-glance metrics (projects, experience, technologies, certifications).
- **About** — Professional summary, highlights, and a personal-info card.
- **Skills** — Grouped, tag-based breakdown of expertise (RAG, Python, vector DBs, frameworks).
- **Featured Work** — Project cards with tech tags and links.
- **Education** — Degree, certifications, and coursework timeline.
- **Contact** — Email, LinkedIn, and GitHub touchpoints.
- Fully **responsive** design (desktop → tablet → mobile).

## Tech Stack

- HTML5
- CSS3 (custom properties, grid, animations, media queries)
- Google Fonts — [Inter](https://fonts.google.com/specimen/Inter)
- Inline SVG icons (no external icon dependency)

## Project Structure

```
.
├── index.html            # Full single-page portfolio (markup + styles)
├── images/
│   └── background.png    # Hero/background visual
└── README.md
```

## Getting Started

No installation or build tools required — open the file directly in any browser.

### Run Locally

```bash
# Clone the repository
git clone https://github.com/bilalkhalidalvi/ai-engineer-portfolio-website.git

# Move into the project
cd ai-engineer-portfolio-website

# Open in your browser (choose one)
# Windows
start index.html
# macOS
open index.html
# Linux
xdg-open index.html
```

Or serve it with a simple static server:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

## Deployment

The site is a static single file, so it can be hosted on any static platform:

- **GitHub Pages** — enable in *Settings → Pages* (source: `master` branch, root).
- **Netlify / Vercel** — drag-and-drop the folder or connect the repo.
- **Any web server** — upload `index.html` and `images/`.

## Customization

All content lives in `index.html`:

- Text & links: edit the markup inside each `<section>`.
- Colors & theme: tweak the CSS variables in the `:root` block at the top of the stylesheet.
- Background image: replace `images/background.png`.

## Contact

- **Email:** [bilalkhalidalvi786@gmail.com](mailto:bilalkhalidalvi786@gmail.com)
- **LinkedIn:** [bilal-alvi-88b1ba42b](https://www.linkedin.com/in/bilal-alvi-88b1ba42b)
- **GitHub:** [@bilalkhalidalvi](https://github.com/bilalkhalidalvi)

---

&copy; 2026 M Bilal Khalid. All rights reserved.
