# 🕷️ Spider-Man | Multiversos — 3D Web Experience

An interactive 3D web experience built with **Three.js**, **GSAP**, and **FBX Animations**. Explore dynamic camera transitions, detailed character technical specs, smooth scroll-linked animations, and an immersive Spider-Verse themed overlay modal.

---

## 🚀 Live Demo

Check out the live project here:  
👉 **[Spider-Man Multiversos Demo](https://spider-by-jd.netlify.app/)**

---

## ✨ Features

- **3D Interactive Model Rendering:** High-fidelity 3D Spider-Man FBX model loading and character animation powered by Three.js and Mixamo sequence animation clips.
- **Scroll-Driven Camera Control:** Dynamic camera pose interpolation (`lerp`) synchronized with the user's scroll progress to reveal different views and technical details.
- **Glassmorphism UI:** Modern, translucent UI panels with backdrop filters, smooth hover states, and responsive design for all device viewports.
- **Interactive About Overlay:** Spider-Verse themed interactive modal showcasing character origin stories and team statistics.
- **Developer Debug Tools:** On-screen Camera Inspector panel and coordinate logging button for easy camera pose tuning and sequence debugging.

---

## 🛠️ Tech Stack

- **HTML5 & CSS3** — Responsive layout, CSS clip-paths, and custom keyframes.
- **JavaScript (ES6+)** — Asynchronous model loading, animation sequence control, and UI interaction logic.
- **[Three.js](https://threejs.org/)** — WebGL rendering engine, FBXLoader, PerspectiveCamera, OrbitControls.
- **[GSAP](https://greensock.com/gsap/)** — Smooth UI animation transitions.
- **Mixamo** — Character rig & 3D character animation sequence assets (`.fbx`).

---

## 📂 Project Structure

```text
├── index.html                  # Main HTML layout, inline styling, & Three.js script logic
├── 1.png                       # Spider-Man logo/icon image asset
├── 4.jpg                       # Background city skyline asset
├── 6.fbx                       # Spider-Man 3D model & intro animation asset
├── 1ed.fbx                     # Secondary 3D animation clip asset
└── pages/
    └── tom-holland/
        └── spiderman1.html     # Dedicated character breakdown page
