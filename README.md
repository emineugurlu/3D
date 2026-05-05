# 🐝 Apiary3D: Interactive WebGL Motion Architecture

> **"A high-fidelity 3D environment exploring WebGL rendering, GLTF asset orchestration, and real-time animation loops using the Three.js engine."**

![Repo Size](https://img.shields.io/github/repo-size/emineugurlu/3D?color=yellow&style=flat-square)
![Language Count](https://img.shields.io/github/languages/count/emineugurlu/3D?color=yellow&style=flat-square)
![Engine](https://img.shields.io/badge/Engine-Three.js-black?style=flat-square&logo=three.js)

The modern web is three-dimensional. This project is a technical implementation of a **Real-Time 3D Rendering Pipeline**, utilizing **Three.js** to bridge the gap between low-level WebGL and intuitive user interaction. By managing scene graphs, lighting matrices, and mesh animations, I created a performant 3D experience where a high-detail bee model interacts dynamically with its virtual ecosystem.

---

## 🚀 Engineering Mindset

This project focuses on **3D Graphics & Rendering Logic**:

*   **Scene Graph Management:** Architecting a complex hierarchical scene including cameras, ambient/directional lighting, and 3D geometry.
*   **GLTF Pipeline Optimization:** Efficiently loading and rendering external 3D assets (sourced from Skarfect) while maintaining high frame rates (60 FPS).
*   **Animation Loop Orchestration:** Implementing a recursive `requestAnimationFrame` loop to handle real-time spatial transformations and flight path simulations.
*   **Viewport & Perspective Mapping:** Dynamically recalculating the `Aspect Ratio` and `Projection Matrix` to ensure the 3D scene remains distortion-free across various screen resolutions.

## 🌟 Key Features

*   **Interactive 3D Entity:** A responsive bee model that reacts to environment parameters and user input.
*   **Cinematic Lighting:** Realistic shadow mapping and light-source positioning for enhanced visual depth.
*   **Immersive Motion:** JavaScript-driven flight physics that simulate natural movement patterns.

## 🔧 Technical Stack

*   **Three.js:** Primary engine for WebGL abstraction and 3D rendering.
*   **HTML5 & CSS3:** For the container architecture and UI overlay integration.
*   **JavaScript (ES6+):** Logic for asset loading, animation controllers, and event listeners.

## 📸 Visual Showcase

### 🎥 3D Rendering & Lighting
![ThreeJS View 1](https://github.com/user-attachments/assets/6dbbd6a6-366f-4b07-b781-14612a6dd042)
![ThreeJS View 2](https://github.com/user-attachments/assets/b675f803-9f26-4ff8-8cac-0d8bad0affe3)
![Bee Mesh 1](https://github.com/user-attachments/assets/5baf287a-95dc-439c-b2ed-ebe1270a58c3)
![Bee Mesh 2](https://github.com/user-attachments/assets/b89c249c-4b7b-43f6-873b-f44249bcc2ff)

---

## 🛠️ Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/emineugurlu/3D.git](https://github.com/emineugurlu/3D.git)

2. **Open the Project:**
   ````bash
   cd 3D
   open index.html

Developed by Emine Uğurlu with a focus on WebGL engineering and interactive 3D graphics.
