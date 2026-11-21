<div align="center">

# 🏗️ SkyBuild 3D: Tower Crane Simulator

### **High-Precision 3D WebGL Construction Physics Simulator**
*Developed by **Md Mujahidul Islam** (@mujahidul80)*

<p align="center">
  <a href="https://mujahidul80.github.io/skybuild-3d-tower-crane-simulator/"><img src="https://img.shields.io/badge/Live%20Demo-Play%20in%20Browser-success?style=for-the-badge&logo=three.js&logoColor=white" alt="Live Demo" /></a>
  <a href="https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fmujahidul80%2Fskybuild-3d-tower-crane-simulator"><img src="https://img.shields.io/badge/Deploy%20with-Vercel-black?style=for-the-badge&logo=vercel&logoColor=white" alt="Deploy with Vercel" /></a>
  <a href="https://github.com/mujahidul80/skybuild-3d-tower-crane-simulator/stargazers"><img src="https://img.shields.io/github/stars/mujahidul80/skybuild-3d-tower-crane-simulator?style=for-the-badge&logo=github&color=007ACC" alt="Stars" /></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="License" /></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Three.js-r128-black?style=flat-square&logo=three.js&logoColor=white" alt="Three.js" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-Industrial%20HUD-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white" alt="Tailwind" />
  <img src="https://img.shields.io/badge/Web_Audio-Procedural%20Sound-blueviolet?style=flat-square" alt="Web Audio" />
  <img src="https://img.shields.io/badge/FPS-60%20Locked-brightgreen?style=flat-square" alt="60 FPS" />
  <img src="https://img.shields.io/badge/Mobile-Touch%20Controls%20Ready-orange?style=flat-square" alt="Mobile Ready" />
</p>

---

[🌐 Live Demo](#-live-demo--preview) •
[✨ Key Features](#-key-features) •
[🕹️ Controls Manual](#%EF%B8%8F-crane-operator-manual) •
[🏗️ Blueprint Contracts](#%EF%B8%8F-blueprint-contracts) •
[📐 Physics Architecture](#-physics--simulation-pipeline) •
[🚀 Deployment](#-deployment-options) •
[👤 Developer](#-developer--contact)

</div>

---

## 🌐 Live Demo & Preview

> **💡 Instant Play on Web Browser:**  
> SkyBuild 3D is a **100% self-contained browser simulation**. Procedural Three.js 3D models, Web Audio sound effects, and physics run in real time with zero plugins or downloads required.

- 🔗 **Play Live on Web Browser:** [**Launch SkyBuild 3D**](https://mujahidul80.github.io/skybuild-3d-tower-crane-simulator/)
- 🚀 **1-Click Free Hosting:** Deploy to Vercel with custom domain in under 60 seconds!

---

## ✨ Key Features

1. **Articulated Industrial Tower Crane:**
   - 360-degree jib slewing rotation.
   - Forward and reverse trolley horizontal traversal along the jib track.
   - Dynamic cable hoisting up/down with realistic cable physics and hook pendulum swinging.

2. **Laser Alignment & Auto-Snap Guidance:**
   - Color-coded vertical laser guide projected beneath the electromagnet hook.
   - Turns **Emerald Green** when aligned with target blueprint coordinates.
   - Real-time precision accuracy calculation (percentage scoring and contract budget rewards).

3. **Procedural Web Audio Engine:**
   - Realistic electric crane motor hum that scales pitch with movement speed.
   - Electromagnet latch and release audio pulses.
   - Heavy structural impact thuds on block placement.
   - Mission completion fanfare.

4. **Multi-Camera Perspective:**
   - **Camera 1:** Free Orbit Camera (left-click drag & zoom).
   - **Camera 2:** Top-Down Precision Camera tracking hook position.
   - **Camera 3:** Operator Cabin Camera mounted high on the slewing mast.

5. **Touch & Mobile Controls Ready:**
   - Complete on-screen touch D-Pad and action buttons for smartphones and tablets.

---

## 🕹️ Crane Operator Manual

| Function | Desktop Keyboard | Mobile / Touch Control |
| :--- | :--- | :--- |
| **Slew Crane Jib** | `A` / `D` or `Left` / `Right` | D-Pad `LEFT` / `RIGHT` |
| **Trolley Travel** | `W` / `S` or `Up` / `Down` | D-Pad `OUT` / `IN` |
| **Hoist Cable** | `Q` / `E` or `Shift` / `Ctrl` | Hoist `UP` / `DOWN` |
| **Grab / Place Block** | `SPACEBAR` | `🧲 GRAB` / `⬇ PLACE` Button |
| **Rotate Piece 90°** | `R` Key | `↻ 90°` Button |
| **Switch Camera** | `C` Key | `🎥 CAMERA` Button |
| **Orbit & Zoom** | Mouse Drag & Scroll | One-Finger Drag & Pinch |

---

## 🏗️ Blueprint Contracts

1. **Level 1: Site Office** — Place concrete perimeter walls, partition blocks, and prefabricated roof slabs.
2. **Level 2: Industrial Warehouse** — Erect heavy steel I-beams, cross trusses, and industrial wall sections.
3. **Level 3: Skyscraper Core** — Hoist elevator shaft columns, structural pillars, and exterior glass panels.
4. **Free Build Sandbox Mode** — Choose materials from the bottom toolbar (Concrete, Steel, Glass, Pillars, Roofs) and build custom architecture freely.

---

## 📐 Physics & Simulation Pipeline

```mermaid
flowchart LR
    A["🕹️ Operator Input<br/>(WASD / Touch D-Pad)"] --> B["⚙️ Crane Kinematics<br/>• Slew Angle<br/>• Trolley Distance<br/>• Cable Hoist Length"]
    B --> C["🪝 Pendulum Dynamics<br/>• Angular Acceleration<br/>• Hook Damping<br/>• Cargo Mass Transfer"]
    C --> D["🎯 Laser Alignment<br/>• Proximity Raycast<br/>• Target Blueprint Match<br/>• Precision Snap-in"]
    D --> E["🔊 Procedural Web Audio<br/>• Dynamic Motor Pitch<br/>• Magnet Clack<br/>• Heavy Impact Thud"]
```

---

## 🚀 Deployment Options

### 1-Click Vercel Deploy
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fmujahidul80%2Fskybuild-3d-tower-crane-simulator)

### GitHub Pages (Automated CI/CD Included)
Pre-configured `.github/workflows/deploy.yml` action automatically publishes pushes on `main` to `https://mujahidul80.github.io/skybuild-3d-tower-crane-simulator/`.

### Local Development
```bash
# Clone repository
git clone https://github.com/mujahidul80/skybuild-3d-tower-crane-simulator.git
cd skybuild-3d-tower-crane-simulator

# Start local server
npm run dev
# or
npx serve .
```

---

## 👤 Developer & Contact

**Md Mujahidul Islam**  
*Game Developer • Creative Web Developer • Packaging Designer*

<p align="left">
  <a href="https://wa.me/8801571432927"><img src="https://img.shields.io/badge/WhatsApp-%2B880_1571--432927-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp" /></a>
  <a href="mailto:mdmujahidul31@gmail.com"><img src="https://img.shields.io/badge/Email-mdmujahidul31%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://t.me/failuretm"><img src="https://img.shields.io/badge/Telegram-%40failuretm-229ED9?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" /></a>
  <a href="https://github.com/mujahidul80"><img src="https://img.shields.io/badge/GitHub-mujahidul80-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://www.behance.net/mujahidulib"><img src="https://img.shields.io/badge/Behance-mujahidulib-1769ff?style=for-the-badge&logo=behance&logoColor=white" alt="Behance" /></a>
  <a href="https://mujahidulib.blogspot.com"><img src="https://img.shields.io/badge/Blog-mujahidulib.blogspot.com-FF5722?style=for-the-badge&logo=blogger&logoColor=white" alt="Blog" /></a>
  <img src="https://img.shields.io/badge/Location-Dhaka%2C%20Bangladesh-059669?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location" />
</p>

---

## 📄 License

This simulation is open-source under the [MIT License](LICENSE).  
© 2026 **Md Mujahidul Islam**. All rights reserved.
