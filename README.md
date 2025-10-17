# Hello Space — Tiny Single-file Page

A minimal, beautiful, and fully responsive single-file HTML page that displays "Hello Space". Built using the Tailwind CSS CDN and a small inline JavaScript animation. No build steps or external tooling required — just open index.html in your browser.

## Features

- Single-file HTML (index.html) — everything inline (styles, JS) and production-ready.
- Responsive layout using Tailwind CSS CDN.
- Animated canvas starfield background with subtle parallax and twinkle.
- Accessible controls: copy the text to clipboard, toggle Warp Mode (keyboard & mouse supported).
- Lightweight and portable — perfect as a tiny demo or starting point.

## Usage

1. Download the repository or save the three files (index.html, README.md, LICENSE) to a folder.
2. Open `index.html` in any modern browser (Chrome, Firefox, Edge, Safari).
3. Interact with the page:
   - Click "Copy \"Hello Space\"" to copy the phrase to your clipboard.
   - Click "Warp Mode" to increase the starfield speed and create a warp effect.

There is no server required — the page runs entirely on the client.

## Customization

- Edit the heading text inside the `<h1>` tag if you want a different message.
- Tailwind config is included inline before the CDN script for quick theme tweaks (colors, fonts, etc.).
- The canvas animation is implemented with plain JavaScript in the HTML file; you can tune star density and behavior inside the script.

## Accessibility

- Buttons are keyboard-navigable and announce actions via an off-screen ARIA live region.
- Sufficient contrast and focus outlines are provided for interactive elements.

## License

This project is released under the MIT License — see the included LICENSE file.
