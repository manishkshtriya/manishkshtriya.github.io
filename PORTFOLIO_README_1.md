<div align="center">

# Manish M P — Portfolio

### A single-file, self-contained personal site.

Full-viewport portrait hero with a cursor-spotlight reveal, scroll-in project cards, and a one-click résumé download — no frameworks, no build step, no dependencies beyond two Google Fonts.

<img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
<img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
<img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">

<br>

<img alt="No framework" src="https://img.shields.io/badge/framework-none-black.svg?style=flat-square">
<img alt="No build step" src="https://img.shields.io/badge/build%20step-none-black.svg?style=flat-square">
<img alt="License" src="https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square">

</div>

<br>

## About

This is my personal portfolio — final-year Information Science & Engineering student at NMAM Institute of Technology (NMAMIT), building full-stack and applied AI/ML systems, currently researching computer vision at NITK Surathkal.

It's one HTML file. Everything — fonts aside — is inlined: CSS, JavaScript, my photo, my NMAMIT campus shot, and my résumé (embedded as base64, no external hosting required). Open the file and it just works.

<br>

## ✦ Sections

| Section | What's there |
|---|---|
| **Hero** | Full-viewport portrait with a cursor-following spotlight effect — move your mouse and the photo sharpens where you point |
| **Work** | Four projects: AHEAD, EduBoard, UPI MDR Tracker, and a real-time object detection app (in progress) |
| **Experience** | Research Internship at NITK Surathkal — computer vision |
| **Stack** | Languages, web, mobile, AI/ML, databases, core CS, tools |
| **Contact** | Email, GitHub, LinkedIn, and a résumé download button |

Everything below the hero fades in as you scroll — an `IntersectionObserver`-driven reveal, not a library.

<br>

## ✦ Features

- **Cursor-spotlight hero** — a masked layer over the portrait that reveals full clarity/colour wherever the cursor (or a touch, on mobile) moves
- **Word pull-up animation** on the hero heading
- **Scroll-reveal** on every section below the fold, with staggered timing
- **One-click résumé download** — the PDF is embedded in the page itself, no server needed
- **Fully responsive** — breakpoints down to 360px, with safe-area padding for notches
- **Respects `prefers-reduced-motion`** — all animation is disabled for users who ask for it

<br>

## ✦ Tech

```
Markup          Single HTML file, no framework
Styling         Plain CSS — custom properties, grid, flexbox
Fonts           Orbitron + Inter (Google Fonts)
Interactivity   Vanilla JavaScript (IIFE), zero dependencies
```

<br>

## ✦ Run it

Just open `index.html` in a browser. That's the whole setup.

```bash
git clone https://github.com/manishkshtriya/portfolio.git
cd portfolio
open index.html   # or double-click it
```

<br>

## ✦ Deploy (GitHub Pages)

1. Push `index.html` to this repo's `main` branch.
2. **Settings → Pages → Source:** Deploy from a branch → `main` / `(root)`.
3. GitHub publishes it at `https://manishkshtriya.github.io/portfolio/` within a minute or two.

<br>

## ✦ Contact

<div align="center">

[![Email](https://img.shields.io/badge/Email-manishkshtriya333%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:manishkshtriya333@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-manishmp-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/manishmp)
[![GitHub](https://img.shields.io/badge/GitHub-manishkshtriya-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/manishkshtriya)

</div>

<br>

---

<div align="center">

Built by [Manish M P](https://github.com/manishkshtriya) · NMAM Institute of Technology, Nitte

</div>
