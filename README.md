# ✦ GFX_MAHADIHS —  Portfolio

> A playful, neo-brutalist scrapbook portfolio engineered for **Gfx_Mahadihs (Mahadi Hasan)** — Brand Identity Designer, Motion & 3D Artist, and Visual Technologist.

Inspired by the authentic aesthetic, featuring hand-drawn doodle borders, draggable sticker badges, polaroids with masking tape, kinetic marquee ribbons, and rich interactive case studies.

---

## 🎨 Aesthetic & Design System

* **Neo-Brutalist Scrapbook:** Dotted graph blueprint canvas (`ca-grid`), hand-drawn doodle borders (`ca-doodle-box`), and masking tape strips (`ca-tape`).
* **Signature Color Palette:**
  * `--ca-ink`: `#191510` (Charcoal Black)
  * `--ca-surface`: `#faf6ee` (Cream Paper)
  * `--ca-yellow`: `#ffe142` (Warm Yellow)
  * `--ca-orange`: `#ff6b35` (Tangerine Orange)
  * `--ca-purple`: `#c4b5fd` (Lilac Purple)
  * `--ca-green`: `#86efac` (Fresh Green)
  * `--ca-mint`: `#a7f3d0` (Mint)
  * `--ca-magenta`: `#f472b6` (Vivid Magenta)
  * `--ca-blue`: `#3b82f6` (Electric Blue)
  * `--ca-cyan`: `#38bdf8` (Bright Cyan)
* **Expressive Typography:**
  * **Display Header:** `Anton` (`ca-display`) — high-impact condensed sans for giant names.
  * **Handwritten Notes:** `Caveat` (`ca-hand`) — organic script for annotations and arrows.
  * **Metadata & Badges:** `Space Mono` (`ca-mono`) — bold monospace with letter-spacing.
  * **Narrative & Body:** `Space Grotesk` — clean, technical grotesque sans.

---

## ✨ Features & Micro-Interactions

1. **Draggable Scrapbook Canvas:** All hero stickers and polaroid badges can be picked up, dragged, and dropped freely via mouse or mobile touch gestures.
2. **Interactive Case Study Modal:** Deep-dive modal window for each project featuring:
   * **Project 01: Zenith Brand System** (Visual Identity, 3D Brand System)
   * **Project 02: OmniMotion 3D** (Motion Design, Brand Reel)
   * **Project 03: CyberPulse UI/UX** (Esports Web Platform, Dark Interface)
   * **Project 04: Apex Packaging & Print** (Luxury Foil Craft, Physical Production)
   * Key performance metrics (`+84% Brand Equity`, `1.8M+ Views`, `250k+ Players`, `38% Unboxing Share`).
3. **Pure Canvas Confetti Engine:** Zero external library confetti animation triggered on contact form submission, reaction clicks, and email copying.
4. **Instant Email Copying:** Click-to-copy email box (`hello@gfxmahadihs.com`) with an animated sliding toast notification.
5. **Interactive Reaction Pill:** Author feedback card with an interactive reaction counter (`❤️`) and pop bounce animation.
6. **Kinetic Marquee Banner:** Smooth infinite scrolling typography ribbon.
7. **Zero Dependencies & Zero Build Step:** Built with pure semantic HTML5, modern CSS3, and vanilla JavaScript. Runs anywhere without `npm install` or complex build configurations.

---

## 📁 Project Structure

```
GFXMAHADIHS_PORTFOLIO-/
├── index.html       # Semantic layout, meta tags, and component structure
├── style.css        # Full CSS variables, typography, animations & responsive grid
├── script.js        # Draggable stickers, confetti, modal controller & interactions
└── README.md        # Documentation and deployment guide
```

---

## 🚀 Quick Start

### 1. Open Directly in Browser
You don't need a dev server or build step! Simply double-click `index.html` or run:

```bash
# macOS
open index.html

# Windows
start index.html

# Linux
xdg-open index.html
```

### 2. Run with Local Server (Optional)
```bash
# Python 3
python -m http.server 3000

# or Node / npx
npx serve .
```

---

## 🌐 One-Click Deployment

### GitHub Pages (Recommended)
1. In your GitHub repository (`https://github.com/gfx-mahadihs/GFXMAHADIHS_PORTFOLIO-`), go to **Settings → Pages**.
2. Under **Build and deployment**:
   * **Source**: `Deploy from a branch`
   * **Branch**: `main`
   * **Folder**: `/ (root)`
3. Click **Save**. Your portfolio will be live at `https://gfx-mahadihs.github.io/GFXMAHADIHS_PORTFOLIO-/` within 60 seconds!

### Vercel / Netlify
1. Connect the repository `GFXMAHADIHS_PORTFOLIO-`.
2. Leave the **Build Command** blank.
3. Set **Output Directory** to `.` (root).
4. Click **Deploy**.

---

## 🛠️ Customization

1. **Update Name & Taglines:** Search and replace `MAHADI` or `Gfx_Mahadihs` in `index.html`.
2. **Add or Edit Projects:** Open `script.js` and modify the `CASE_STUDIES` object to add your own client work, descriptions, and high-res imagery.
3. **Change Color Accents:** Adjust the color tokens in `:root` inside `style.css`.
4. **Update Email & Socials:** Replace `hello@gfxmahadihs.com` and social profile links (`GitHub`, `Dribbble`, `LinkedIn`, `Behance`) in `index.html`.

---

## 👤 Author & Credits

* **Designer & Technologist:** **Gfx_Mahadihs** ([@gfx-mahadihs](https://github.com/gfx-mahadihs))
* **Design Inspiration:** Crayon / Creative Artsy Architecture
* **Typography:** [Anton](https://fonts.google.com/specimen/Anton), [Caveat](https://fonts.google.com/specimen/Caveat), [Space Mono](https://fonts.google.com/specimen/Space+Mono), and [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk) via Google Fonts.
* **License:** MIT License. Feel free to use, adapt, and build upon this project.
