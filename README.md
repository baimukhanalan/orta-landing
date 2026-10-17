<div align="center">

# Orta — Landing

### One living learning environment — from the classroom panel, home, and back to the teacher.

A single-page, animated marketing site for **Orta** (Kazakh: *"environment"*), an education product that ties together a live 3D scene, a sovereign AI tutor, and unified student progress.

<br>

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SVG](https://img.shields.io/badge/SVG-FFB13B?style=for-the-badge&logo=svg&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

[![Live Demo](https://img.shields.io/badge/Live_Demo-0c8593?style=for-the-badge&logo=vercel&logoColor=white)](https://orta-landing-baimukhanalan1-5914s-projects.vercel.app)

</div>

---

## 📖 About

**Orta — Landing** is the promotional landing page for Orta, a learning-environment product aimed at Kazakhstani schools. The page introduces the product's core idea — one continuous environment that follows the student from the classroom to home and back to the teacher — and presents it through scroll-driven storytelling, in Kazakh and Russian.

The entire experience lives in a **single, dependency-free `index.html`**: markup, styles, and interaction logic are hand-written, with no build step and no front-end framework. The only external resources are Google Fonts.

## ✨ Highlights

- 🎬 **Animated intro / preloader** that reveals the page once the brand mark finishes.
- 📜 **Scroll-reveal choreography** built on `IntersectionObserver` — sections and elements fade and rise into view as you scroll.
- 🧲 **Magnetic buttons** and subtle **mouse-parallax** driven by a single `requestAnimationFrame` loop.
- 🔢 **Animated counters** that count up to their target when their section enters the viewport.
- ↔️ **Before / after comparison slider** with mouse and touch support.
- 🧭 **Interactive journey slider** and a scroll-synced chapter rail for navigation.
- 🧵 **Inline-SVG motion** — flowing "thread" paths, comets, a country map, and a full custom icon set, all drawn as SVG.
- 🎨 **Themeable design system** via CSS custom properties, a layered background (spotlight, grain, waves), and three typefaces: *Unbounded*, *Golos Text*, and *IBM Plex Mono*.
- ♿ **Respects `prefers-reduced-motion`** and uses `:focus-visible` outlines for keyboard users.

> Note: Orta's "3D scene" and AI tutor are described as product features in the copy; this repository is the marketing landing page, with the motion rendered through CSS and SVG.

## 🖼️ Screenshots

<!-- Add screenshots or a screen recording of the landing page here, e.g. ![Orta landing hero](docs/hero.png) -->

## 🛠️ Tech Stack

| Layer | Technology |
| --- | --- |
| Markup | HTML5 (single `index.html`) |
| Styling | CSS3 — custom properties, `clamp()` fluid type, keyframe animations |
| Behavior | Vanilla JavaScript (no framework, no build) |
| Graphics | Inline SVG (icons, paths, map) |
| Fonts | Google Fonts — Unbounded, Golos Text, IBM Plex Mono |
| Hosting | Vercel |

## 🚀 Getting Started

No dependencies and no build step are required — it's a static page.

```bash
# 1. Clone the repository
git clone https://github.com/baimukhanalan/orta-landing.git
cd orta-landing

# 2. Open it directly in your browser
open index.html          # macOS   (use "start" on Windows, "xdg-open" on Linux)

# — or — serve it locally (recommended, for correct font loading)
python3 -m http.server 8000
# then visit http://localhost:8000
```

Prefer not to run anything? Just view the [live demo](https://orta-landing-baimukhanalan1-5914s-projects.vercel.app).

## 📄 License

Released under the [MIT License](LICENSE). © 2026 Alan Bai.
