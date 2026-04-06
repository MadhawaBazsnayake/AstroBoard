<h1 align="center">🚀 AstroBoard  </h1>
<h3 align="center">A Next-Generation Infinite Canvas Smart Whiteboard</h3>

<p align="center">
  <b>Designed for educators. Engineered for precision.</b><br/>
  ♾️ Infinite Space • 🧠 Algorithmic Shape Recognition • ⚡ Zero-Latency UX
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge"/>
  <img src="https://img.shields.io/github/stars/MadhawaBazsnayake/AstroBoard?style=for-the-badge&color=gold"/>
  <img src="https://img.shields.io/badge/License-MIT-orange?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/PRs-Welcome-brightgreen?style=for-the-badge"/>
</p>

<p align="center">
  <a href="https://astroboard.pages.dev/">
    <img src="https://img.shields.io/badge/🚀%20Live%20Demo-Try%20AstroBoard-14b8a6?style=for-the-badge&logo=rocket"/>
  </a>
</p>

<p align="center">
  <a href="#-about-the-project">About</a> •
  <a href="#-key-features">Features</a> •
  <a href="#-technical-deep-dive">Technical Details</a> •
  <a href="#-keyboard-shortcuts">Shortcuts</a> •
  <a href="#-roadmap">Roadmap</a>
</p>

---

## 🌌 About the Project

**AstroBoard** is an open-source, high-performance infinite-canvas smart whiteboard designed to redefine the digital classroom experience. Built with a focus on fluid interaction and intelligent assistance, it bridges the gap between natural handwriting and precise digital assets.

Unlike traditional whiteboards limited by pixel boundaries, AstroBoard treats the screen as an expanding galaxy, allowing educators to build complex, multi-layered lessons without ever running out of space.

---

## ✨ Key Features

* **♾️ Seamless Infinite Canvas** – Pan and zoom across an unlimited workspace without performance degradation.
* **🧠 Smart-Snap Recognition** – Custom-built logic that instantly perfects hand-drawn sketches into geometric primitives (Circles, Rectangles, Triangles, Diamonds).
* **🎭 Contextual Education Templates** – One-click switching between **Dot-Grids**, **Ruled Paper**, **Music Staves**, and **Mathematical Grids**.
* **⚡ Zero-Latency Rendering** – Optimized path processing ensures a pen-on-paper feeling, even on lower-end smart board hardware.
* **🌓 Adaptive Theming** – A sophisticated Dark Mode that intelligently flips stroke contrast to ensure maximum visibility and reduced eye strain.
* **🪄 Presentation Suite** – Includes a fading Laser Pointer for dynamic focus and a highlighting Marker for key annotations.

---

## 📸 Interface Preview

<p align="center">
  <img src="https://raw.githubusercontent.com/MadhawaBazsnayake/AstroBoard/refs/heads/main/%7B1246B0F8-9508-4B9D-B60D-CF92C705E23E%7D.png" alt="AstroBoard Interface" style="border-radius: 10px; box-shadow: 0 10px 30px rgba(0,0,0,0.2);"/>
</p>

---

## 🛠️ Technical Deep Dive

AstroBoard isn't just a drawing app; it's a showcase of **Vector Math** and **Pattern Recognition** logic.

### 📐 Algorithmic Shape Detection
The **Smart-Snap** feature utilizes a hybrid approach:
1.  **Douglas-Peucker Algorithm:** Simplifies complex hand-drawn paths into their essential geometric skeletons by reducing redundant points.
2.  **Shoelace Formula:** Calculates the signed area of a drawn polygon to determine "Fill Ratios," allowing the system to distinguish between a Triangle (approx. 0.5 fill) and a Rectangle (approx. 1.0 fill).
3.  **Geometric Feature Analysis:** Analyzes corner counts and radius variance to identify circles and lines with high confidence.

### 🏗️ Tech Stack
* **Canvas Engine:** [Fabric.js](http://fabricjs.com/) (Object-based vector manipulation)
* **Styling:** [Tailwind CSS](https://tailwindcss.com/)
* **Animations:** [GSAP](https://greensock.com/gsap/) (High-performance UI transitions)
* **Icons:** [Lucide React](https://lucide.dev/)
* **Deployment:** Cloudflare Pages

---

## ⌨️ Keyboard Shortcuts

| Action | Key | Action | Key |
| :--- | :--- | :--- | :--- |
| **Select Mode** | `V` | **Sticky Note** | `S` |
| **Pen Tool** | `P` | **Text Tool** | `T` |
| **Marker** | `M` | **Color Palette** | `C` |
| **Laser Pointer** | `L` | **Eraser** | `E` |
| **Undo / Redo** | `Ctrl+Z` / `Y` | **Pan Canvas** | `Space + Drag` |

---

## 🚀 Installation & Contribution

1. **Clone the Galaxy:**
   ```bash
   git clone [https://github.com/MadhawaBazsnayake/AstroBoard.git](https://github.com/MadhawaBazsnayake/AstroBoard.git)
