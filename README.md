<div align="center">

# 🎭 Meme Generator

**Create memes in seconds — no signup, no uploads, 100% private.**

A fast, single-file meme generator that runs entirely in your browser. Upload an image, add your caption, drag it into place, and export — all client-side, with zero tracking and zero backend.

[**🚀 Try it live**](https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/) · [Report a bug](../../issues) · [Request a feature](../../issues)

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](#)
[![No dependencies](https://img.shields.io/badge/dependencies-0-success)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-purple.svg)](LICENSE)

</div>

---

## 📸 Screenshot

> _Add a screenshot of the app here once you have one. Example:_
>
> ```markdown
> ![Meme Generator screenshot](./screenshot.png)
> ```

---

## ✨ Features

### For everyone
- 🖼️ **Upload, drag & drop, or paste** — from clipboard or file, works everywhere
- ✍️ **Multi-line captions** — manual line breaks supported
- 🖱️ **Drag to reposition** — grab the text block and move it anywhere
- 🎨 **Full color control** — preset swatches + a "pick anything" custom picker for both fill and outline
- 🔤 **5 curated fonts** — Impact, Anton, Bebas Neue, Montserrat, Permanent Marker
- 🎚️ **Independent top / bottom font sizes** — sized as a % of image height
- 🅰️ **ALL CAPS toggle** — classic meme style, on or off
- 💾 **Autosave** — your captions and styles survive a page refresh
- 📥 **Download PNG** — one click, high quality
- 📋 **Copy to clipboard** — perfect for pasting straight into chat
- 🍎 **iOS-friendly export** — long-press to Save to Photos on iPhone/iPad

### For developers
- 🪶 **Zero dependencies** — one HTML file, no build step, no npm
- 🔒 **Fully client-side** — images never leave the browser
- 🎯 **Modern APIs** — Canvas 2D, Pointer Events, Clipboard API, `localStorage`
- 📱 **Responsive** — works on mobile, tablet, desktop
- ♿ **Accessible** — focus rings, ARIA labels, reduced-motion support
- ⚡ **Small footprint** — entire app < 40 KB unminified

---

## 🚀 Quick start (users)

**Option A — Use it online**

Open the live demo: [**https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/**](https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/)

**Option B — Run it locally**

1. Download [`index.html`](./index.html)
2. Double-click it — it opens in your browser
3. Done. No installation, no server, no internet required.

---

## 🛠️ Local development

### Prerequisites

None. That's the point.

### Setup

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME

# Option 1: just open the file
open index.html          # macOS
start index.html         # Windows
xdg-open index.html      # Linux

# Option 2: serve locally (recommended for clipboard & font testing)
python3 -m http.server 8000
# → http://localhost:8000
