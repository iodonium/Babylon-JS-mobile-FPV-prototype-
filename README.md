# Mobile FPV & HUD Engine

A lightweight, high-performance 3D First-Person View (FPV) engine and customizable HUD prototype designed specifically for mobile web browsers. Built as a single-file application using **Babylon.js** and **Havok Physics**.

---

## Preview

**Mobile FPV Prototype Screenshot**
![ezgif-1c333cd3991e3cc2](https://github.com/user-attachments/assets/7bfd3f40-9f40-4ee8-b830-08831cee3323)
![ezgif-176e75df84ad7e0b](https://github.com/user-attachments/assets/d3e7ffe7-8945-4afe-8258-c32f4a91ae56)
<img width="540" height="236" alt="ezgif-130ff868729bb170" src="https://github.com/user-attachments/assets/31ebf806-e871-4e06-80c2-6ca8b3f3e53c" />



<img width="2460" height="1080" alt="Screenshot_2026-09-07-14-02-46-380_com android chrome" src="https://github.com/user-attachments/assets/9d4b6414-977e-4f23-a4b9-86962bcbf5ac" />
<img width="2460" height="1080" alt="Screenshot_2026-09-07-14-02-41-167_com android chrome" src="https://github.com/user-attachments/assets/7fa8c41d-f687-41a7-a114-6681b31d4c38" />
<img width="2460" height="1080" alt="Screenshot_2026-09-07-14-02-15-209_com android chrome" src="https://github.com/user-attachments/assets/560c92de-7dfe-4697-bb9b-3639b52aa19b" />


---

## ⚡ Live Demo

Try out the interactive prototype directly in your browser:
* **Test Live:** [Launch Mobile FPV Demo](https://iodonium.github.io/Babylon-JS-mobile-FPV-prototype-/PROTOTYPEV4.html)

---

## Key Features

* **Touch-Optimized Controls:** Dual virtual joysticks for fluid movement and camera looking, complete with jump dynamics and configurable look sensitivity.
* **In-Game HUD Layout Editor:** Move and scale touch controls in real time during gameplay. Layout configurations persist instantly via `localStorage`.
* **Physics & Interactions:** Powered by Havok Physics (WASM) for dynamic collisions, target selection, and raycast-based physical impulses.
* **Performance Focused:** Built-in frustum culling, distance-based mesh rendering, and dynamic hardware scaling to ensure high FPS on mobile screens.
* **Zero Asset Overhead:** Pure code-driven UI with inline SVG fallbacks for fast loading without external asset dependencies.

---

## Tech Stack

* **3D Engine:** [Babylon.js](https://www.babylonjs.com/)
* **Physics:** [Havok Physics](https://www.babylonjs.com/havok/)
* **UI Framework:** Babylon GUI (AdvancedDynamicTexture)
* **Language:** JavaScript (ES6+), HTML5 Canvas

---

## Quickstart

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/iodonium/Babylon-JS-mobile-FPV-prototype-.git](https://github.com/iodonium/Babylon-JS-mobile-FPV-prototype-.git)
   cd Babylon-JS-mobile-FPV-prototype-
