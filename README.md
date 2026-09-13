# 🪐 Aether — Interactive Solar System

**Aether** is a frontend-only, single-file 3D experience of our solar system — built with [Three.js](https://threejs.org/). Every texture, ring, glow, and starfield is generated procedurally in the browser, so there's nothing to download or configure. Just open it and fly.

**🔗 Live demo:** [aether-solar-system.vercel.app](https://aether-solar-system.vercel.app) -- replace with your actual Vercel URL -->

---

## ✨ Features

- **Realistic procedural planets** — the Sun and all 8 planets, each with hand-tuned canvas-generated textures (craters, cloud bands, landmasses, storm bands) — no external image assets, no CORS issues, works fully offline
- **Saturn's rings, Earth's Moon & clouds**, a procedural satellite orbiting Earth, and an asteroid belt between Mars and Jupiter
- **Cinematic landing page** — camera opens on a random planet each visit, scramble-text hero reveal, animated nebula background, live data ticker, and cursor parallax
- **Full orbit + zoom camera controls** via mouse drag / touch, with click-to-focus fly-to animation on any celestial body
- **Detailed info panels** — diameter, distance from Sun, orbital period, day length, moons, and a field-notes fact for every body
- **Search bar** — jump straight to any planet by name
- **Compare mode** — line up two planets' stats side by side
- **Guided tour** — an auto-piloted camera tour through the entire solar system, pausing at each stop
- **Speed control** — scale orbital motion from paused to 4× real-time
- **Mini-map / radar** — live top-down view of every planet's current position
- **Ambient sound toggle** — a synthesized deep-space drone (Web Audio API, no audio files)
- **"Did you know?" facts** — periodic space trivia toasts
- **Rich sky-dome** — Milky Way band, thousands of speckled stars, distant galaxies, and nebula smudges
- **Fully responsive** — tuned for desktop, tablet, and mobile, including notch/safe-area support and landscape layouts

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| 3D rendering | [Three.js](https://threejs.org/) (WebGL) |
| Textures | Procedurally generated via HTML5 Canvas — no image downloads |
| Audio | Web Audio API (synthesized ambient drone) |
| UI | Vanilla HTML / CSS / JavaScript (no framework, no build step) |
| Fonts | Spectral & IBM Plex (Google Fonts) |

No bundler, no `npm install`, no backend — it's a single `index.html` file.

## 🚀 Getting Started

### Run locally
Just open the file in a browser:

```bash
git clone https://github.com/<your-username>/aether-solar-system.git
cd aether-solar-system
open index.html   # or double-click the file
```

> Requires an internet connection on first load only, to fetch Three.js from a CDN.

### Deploy your own copy
This project is a static site, so it deploys anywhere in one click:

- **Vercel:** Import this repo → framework preset "Other" → Deploy
- **Netlify:** Drag and drop `index.html` at [app.netlify.com/drop](https://app.netlify.com/drop)
- **GitHub Pages:** Settings → Pages → deploy from the `main` branch

## 📁 Project Structure

```
aether-solar-system/
└── index.html   # everything — markup, styles, and Three.js scene logic
```

## 🗺️ Roadmap / Ideas

- [ ] Real-scale distance toggle (true astronomical scale)
- [ ] Constellation overlay on the sky-dome
- [ ] Downloadable/printable fact sheet per planet

## 👤 Author

Built solo — 3D scene, UI/UX, all interactions, and documentation.

<!-- Add your name / GitHub / portfolio link below -->
- 

## 🙏 Acknowledgments

- [Three.js](https://threejs.org/) — 3D rendering engine and example references
- [Sketchfab](https://sketchfab.com/) — referenced for early model exploration
- Planetary facts sourced from NASA public data

## 📄 License

This project was built for academic purposes. Feel free to fork and adapt for learning.

---

<p align="center"><i>Built with curiosity, one procedurally generated planet at a time.</i></p>
