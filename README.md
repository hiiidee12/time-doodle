# ⏰ Time Doodle

[![License: MIT](https://img.shields.io/badge/License-MIT-neon%20green.svg)](https://opensource.org/licenses/MIT)
[![Single HTML File](https://img.shields.io/badge/Single%20File-HTML%20%2B%20CSS%20%2B%20JS-ff69b4.svg)](https://time-doodle.vercel.app)
[![No Dependencies](https://img.shields.io/badge/Dependencies-Zero-brightgreen.svg)]()
[![Deploy: Vercel](https://img.shields.io/badge/Deploy-Vercel-black.svg)](https://vercel.com)

> 🌀 A creative clock that tells time by drawing spirograph and sacred geometry patterns in real-time — every second adds a mark, every minute is a unique masterpiece.

## 🎨 Live Demo

**🔗 [time-doodle.vercel.app](https://time-doodle.vercel.app)**

---

## ✨ Features

- 🔮 **Sacred Geometry Patterns** — spirograph-inspired designs rendered with math-driven curves
- ⏱️ **Second-by-Second Drawing** — each passing second adds a new mark, building intricate patterns over time
- 🌈 **Neon Glow Colors** — vibrant, luminous color palettes with real-time glow effects
- 🕐 **Clock Hands** — classic hour, minute, and second hands overlaid on the artwork
- 🎲 **Unique Every Minute** — no two minutes ever produce the same visual — a one-of-a-kind canvas each cycle
- 📦 **Single HTML File** — the entire app is self-contained in one file — no build step, no bundler
- ⚡ **Zero Dependencies** — pure vanilla HTML, CSS, and JavaScript — no frameworks, no libraries
- 📱 **Responsive** — looks beautiful on any screen size

---

## 🚀 How to Use

### Option 1: Visit the Live Demo
Simply open **[time-doodle.vercel.app](https://time-doodle.vercel.app)** in any modern browser.

### Option 2: Run Locally
1. **Clone the repo**
   ```bash
   git clone https://github.com/your-username/time-doodle.git
   cd time-doodle
   ```
2. **Open in browser**
   ```bash
   open index.html    # macOS
   xdg-open index.html # Linux
   start index.html   # Windows
   ```
   That's it. No install, no build, no server needed.

### Option 3: Quick Start with a Local Server
```bash
npx serve .
# or
python3 -m http.server 8080
```
Then open `http://localhost:8080` in your browser.

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| **Markup** | HTML5 |
| **Styling** | CSS3 (animations, filters, glow effects) |
| **Logic** | Vanilla JavaScript (ES6+) |
| **Rendering** | HTML5 Canvas API |
| **Mathematics** | Spirograph equations, polar coordinates, trigonometry |
| **Deployment** | Vercel |

---

## 🧮 How It Works

The clock leverages **spirograph mathematics** — curves traced by a point on a circle rolling around another circle. The parametric equations drive the drawing:

```
x(θ) = R·cos(θ) + r·cos(k·θ)
y(θ) = R·sin(θ) + r·sin(k·θ)
```

- The **second hand** triggers new point placements each tick
- The **minute hand** subtly shifts pattern parameters, ensuring uniqueness
- **Neon glow** is achieved via Canvas shadow blur and composite blending
- Patterns accumulate on the canvas — watching for a full minute reveals the complete geometry

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

```
MIT License — © 2026
Use it, modify it, ship it. Have fun. 🚀
```

---

<div align="center">

**Made with 💜 and math**

*Open the demo. Watch the geometry unfold. Lose track of time.* 🌀

</div>
