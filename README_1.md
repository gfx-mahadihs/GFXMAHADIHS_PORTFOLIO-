# ✦ Crayon Portfolio

A playful, scrapbook-style portfolio for designers and creatives. Pure HTML, CSS and vanilla JavaScript: no build step, no dependencies, no framework.

Layout and mood take cues from the "creative artsy" style of portfolio (big hand-lettered type, sticky notes, polaroids, chunky shadows), but the code, copy, and visuals here are original.

## Features

- **Draggable scrapbook board** in the hero: polaroids and sticky notes can be moved around (mouse and touch).
- **Marquee ribbon** for your skills.
- **Featured works** cards with a tilt and bounce on hover.
- **Playground canvas**: click or drag to splat paint. A small place for experiments.
- **Responsive**: works from phone to desktop.
- **Accessible defaults**: semantic HTML, good contrast, and `prefers-reduced-motion` support.
- **Zero dependencies**: only Google Fonts (Caveat and Space Grotesk).

## Project structure

```
crayon-portfolio/
├── index.html   # page markup and content
├── style.css    # all styling, colors defined as CSS variables
├── script.js    # drag interactions, cursor note, paint canvas
└── README.md
```

## Getting started

```bash
git clone https://github.com/<your-username>/crayon-portfolio.git
cd crayon-portfolio

# open directly in a browser
open index.html          # macOS
xdg-open index.html      # Linux
start index.html         # Windows

# or serve locally
npx serve .
# or
python3 -m http.server 8000
```

## Customize it

1. **Your details**: edit the name, role, city, and about text in `index.html`. Search for `Alex Hart` and `hello@example.com`.
2. **Projects**: each `<article class="card">` in the `#work` section is one project. Change the title, blurb and tags, or add and remove cards.
3. **Colors**: change the variables at the top of `style.css`:
   ```css
   :root {
     --paper: #fff8ec;
     --ink: #1d1b2e;
     --pink: #ff7eb6;
     --yellow: #ffe066;
   }
   ```
4. **Your own images**: swap the gradient placeholders (`.photo`, `.thumb`) for real images, for example:
   ```css
   .t1 { background: url("images/wayline.jpg") center / cover; }
   ```
5. **Fonts**: replace the Google Fonts link in `index.html` and update `--hand` and `--sans` in `style.css`.

## Deploy

**GitHub Pages**

1. Push the project to a GitHub repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, then select `main` and `/ (root)`.
4. Your site goes live at `https://<your-username>.github.io/<repo-name>/`.

**Netlify / Vercel / Cloudflare Pages**: import the repo and leave the build command empty. The publish directory is the project root.

## Browser support

Current versions of Chrome, Edge, Firefox and Safari.

## License

MIT. Use it, remix it, make it yours. A link back is appreciated but not required.

## Credits

- Fonts: [Caveat](https://fonts.google.com/specimen/Caveat) and [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk) via Google Fonts.
