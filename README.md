# ankita-pradhan-portfolio

Personal portfolio website for **Ankita Pradhan** — Software Engineering student at VIT-AP University. Built as a single-file, zero-dependency HTML site with a warm minimalist aesthetic.

---

## ✦ Live Preview

> Deploy to GitHub Pages, Netlify, or Vercel — drop `index.html` and you're done.

---

## Features

- **Custom animated cursor** with a lagging ring that morphs on hover
- **Scroll-reveal animations** — sections fade and rise into view as you scroll
- **Staggered project card entrance** with a warm underline sweep on hover
- **Active nav highlight** that tracks your scroll position
- **Fully responsive** — degrades gracefully to native cursor on mobile
- **Zero dependencies** — no frameworks, no build step, one `.html` file

---

## Sections

| # | Section | Description |
|---|---------|-------------|
| 1 | **Hero** | Name, role tag, animated entrance |
| 2 | **About** | Bio, CGPA / project / LeetCode stats, skill pills |
| 3 | **Work** | 2×2 project card grid with tech tags and metrics |
| 4 | **Contact** | Email, GitHub, LinkedIn links + location metadata |

---

## Projects Showcased

| Project | Stack | Highlight |
|---------|-------|-----------|
| 🧠 AI Study Assistant | Python, Django REST, LLM | Inference pipeline for large document inputs |
| 🍽️ Snap & Savor | React, MySQL, Docker, CI/CD | End-to-end containerized deployment |
| 🌿 Fruit Yield Estimation | OpenCV, TensorFlow, Flask | ~90% prediction accuracy |
| 📜 Vedanta Summarizer | Python, NLP, Transformers, Flask | ~30% accuracy improvement via HuggingFace |

---

## Getting Started

No build tools needed.

```bash
git clone https://github.com/your-username/ankita-pradhan-portfolio.git
cd ankita-pradhan-portfolio
# Open index.html in your browser
open index.html
```

To deploy on **GitHub Pages**:

1. Push the repo to GitHub
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your site will be live at `https://your-username.github.io/ankita-pradhan-portfolio`

---

## Customization

All content lives directly in `index.html` — no config files or separate data layer.

| What to update | Where |
|----------------|-------|
| GitHub profile link | `<a href="https://github.com">` in the contact section |
| LinkedIn profile link | `<a href="https://linkedin.com">` in the contact section |
| Add/edit projects | `.project-card` blocks inside `#projects` |
| Color palette | CSS variables in `:root` (top of `<style>`) |
| Fonts | Google Fonts `@import` + `--serif` / `--sans` / `--mono` variables |

---

## Design System

```
Fonts      DM Serif Display · DM Sans · JetBrains Mono
Palette    --bg #f7f5f0  --ink #1a1814  --accent-warm #8b5e3c
Layout     Single-page scroll  ·  CSS Grid  ·  Flexbox
Motion     IntersectionObserver  ·  CSS keyframes  ·  rAF cursor loop
```

---

## Tech Stack

Pure HTML · CSS · Vanilla JavaScript — no Node, no npm, no bundler.

---

## Contact

**Ankita Pradhan** · [ankitapradhan1915@gmail.com](mailto:ankitapradhan1915@gmail.com)
