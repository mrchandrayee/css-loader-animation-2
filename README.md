# CSS Loader Animation — video recreation

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-blue?style=for-the-badge&logo=github)](https://mrchandrayee.github.io/css-loader-animation-2/)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org) [![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org) [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](./LICENSE)

This standalone project recreates the five loaders shown in the supplied 23.8-second screen recording.

## Loaders, in video order

1. **Liquid Lava Loader** — orange/yellow gradient blob that morphs its border radius.
2. **Holographic Cube Loader** — thin cyan outlined square rotating continuously.
3. **Quantum Orbit Loader** — dark circular orbit with a cyan satellite dot.
4. **Cyber Circuit Loader** — green repeating-grid ring rotating continuously.
5. **Infinity Portal Loader** — partial circular ring with violet and cyan arcs.

## CSS visible in the video

The readable declarations and values are transcribed into the code panels in `index.html`:

- `.lava`: 70px square, orange/yellow 45-degree gradient, 50% radius, `blob 2s infinite`.
- `.cube`: 60px square, 3px cyan border, preserve-3d, `spin 3s linear infinite`.
- `.orbit`: 70px circle, 2px `#475569` border, relative positioning, `spin 2s linear infinite`; `::before` satellite is 10px, cyan, circular, offset `top: -5px; left: 30px`.
- `.circuit`: 80px square, green repeating linear-gradient grid, `spin 6s linear infinite`.
- `.portal`: 70px circle, 5px transparent border with violet top and cyan right edges, `spin 1s linear infinite`.

The video text is small and some code edges are soft/clipped. The declarations above retain the readable values; the circuit's radial mask is included to create the ring-shaped grid visible in the preview. Markup, layout, and visual supporting styles are reconstructed for a runnable standalone page. This is not claimed to be the creator's complete original source.

## Run

1. Extract the ZIP.
2. Open `index.html` in Chrome, Firefox, Safari, or Edge.
3. Scroll down to see all five animations.

No JavaScript, packages, build process, or external assets are required.

## Files

- `index.html` — markup and visible CSS snippets for all five loaders
- `style.css` — responsive dark layout and animated loader implementations
- `README.md` — transcription notes and run instructions

## 👨‍💻 Author

**mrchandrayee** · [GitHub](https://github.com/mrchandrayee)

## 📄 License

[MIT License](./LICENSE)
