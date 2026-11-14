# Minecraft-in-html

A browser-based Minecraft-inspired project built with HTML/JavaScript (single-file experience).

**Live demo:** https://chandrasen74.github.io/Minecraft-in-html/  
**Direct game file:** https://chandrasen74.github.io/Minecraft-in-html/JScarft.html  
**Repository:** https://github.com/Chandrasen74/Minecraft-in-html

![Screenshot of Minecraft-in-html](screenshot.png)

## Overview
`Minecraft-in-html` runs a Minecraft-like experience in the browser from `JScarft.html` (with `index.html` redirecting to it for GitHub Pages).

- **Primary language:** HTML
- **Languages detected:** HTML, JavaScript, CSS (embedded)
- **Stack/tech:** Single-file HTML app with embedded scripts/styles/shaders
- **Controls:** see [`controls.txt`](controls.txt)

## How to install & run
### Prerequisites
- A modern web browser (WebGL-capable recommended)
- (Optional) [Python 3](https://www.python.org/) or any static file server for local serving

### Run locally
```bash
git clone https://github.com/Chandrasen74/Minecraft-in-html.git
cd Minecraft-in-html
```
- **Option 1:** open `index.html` (or `JScarft.html`) in your browser
- **Option 2 (recommended):** serve locally, then open the shown URL:
```bash
python -m http.server 8000
# open http://localhost:8000
```

## Repository structure
- `index.html` - redirect/entry for GitHub Pages root
- `JScarft.html` - main game file
- `controls.txt` - controls/reference
- `screenshot.png` - preview image
- `.nojekyll` - disables Jekyll processing so Pages serves files directly
- `README.md`

## Notes
- If the root Pages URL shows text/README instead of the game, ensure Pages is serving static files (this repo includes `.nojekyll` and `index.html`) and try the direct `JScarft.html` link.
- The project may load external resources; behavior can depend on browser/network conditions.

## Status
Documented with screenshot, language/stack details, and setup instructions; Pages entry fixed with `index.html` + `.nojekyll`.
