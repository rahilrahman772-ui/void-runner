# 🚀 Void Runner

**Void Runner** is a real-time 3D space flight-combat game built for the browser with **JavaScript, Three.js, and WebGL**. It combines arcade-style flight, enemy combat, progressive waves, power-ups, and configurable GPU-heavy rendering into a standalone web experience.

## 🎮 Live Demo

**Play Void Runner:**  
https://rahilrahman772-ui.github.io/void-runner/

**Source Code:**  
https://github.com/rahilrahman772-ui/void-runner

## ✨ Features

- Real-time 3D space flight and combat
- WebGL-powered rendering through Three.js
- Mouse-controlled flight using Pointer Lock
- WASD thrust and strafing controls
- Space / Shift vertical movement
- Hold left mouse button to fire cannons
- Progressive enemy waves
- Enemy drones with ranged attacks
- Boss encounters with radial projectile attacks
- Asteroid field with destructible asteroids
- Health, boost, score, and combo systems
- Collectible power-ups: health restoration, rapid-fire mode, and boost recharge
- Radar / minimap for nearby objects and enemies
- Visual damage feedback and screen shake
- Pause and restart systems
- Real-time FPS and rendering statistics
- Four selectable rendering-quality presets

## 🖥️ Rendering & Graphics

Void Runner is designed to make substantial use of browser GPU rendering.

- WebGL rendering through Three.js
- Dynamic lighting
- Shadow mapping
- Fog and atmospheric space effects
- GPU-rendered starfield
- Particle and glow effects
- PBR-style materials
- Adjustable render resolution
- Multiple real-time lighting configurations
- Live rendering statistics including FPS, draw calls, triangles, and active lights

### Render Quality

| Preset | Description |
|---|---|
| **Low** | Reduced scene complexity and no dynamic shadows |
| **Medium** | Shadows with a moderate object/light count |
| **High** | Higher geometry density, shadows, lighting and resolution |
| **Ultra** | Maximum configured scene density, shadow resolution and render resolution |

You can switch quality during gameplay with:

**1 → Low**  
**2 → Medium**  
**3 → High**  
**4 → Ultra**

## 🎮 Controls

| Control | Action |
|---|---|
| **Mouse** | Steer the ship |
| **W / A / S / D** | Thrust / strafe |
| **Space** | Climb |
| **Shift** | Dive |
| **Left Click (Hold)** | Fire cannons |
| **1 / 2 / 3 / 4** | Change render quality |
| **ESC** | Pause / resume |
| **R** | Restart after game over |

## ⚔️ Gameplay

Survive increasingly difficult waves while destroying hostile drones and asteroids.

As the game progresses:

- Enemy and asteroid populations increase.
- Enemy health scales with the wave.
- Every fifth wave can introduce a **Warden** boss.
- Bosses have increased health and radial projectile attacks.
- Destroying enemies increases your score and combo multiplier.
- Power-ups can appear after destroying enemies or asteroids.

## 🛠️ Technologies

- **HTML5**
- **CSS3**
- **JavaScript**
- **Three.js**
- **WebGL**
- **Pointer Lock API**
- **HTML Canvas API**

The project is currently implemented as a standalone `index.html` application with Three.js loaded from a CDN.

## ▶️ Running Locally

No build system is required.

### Option 1 — Open directly

Download or clone the repository and open `index.html` in a modern web browser.

### Option 2 — Run with a local server

For the most reliable browser behavior, serve the project through a local HTTP server.

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## 🌐 Deployment

The project is deployed using **GitHub Pages**.

Every update pushed to the `main` branch can be published through the repository's GitHub Pages configuration.

**Live site:**  
https://rahilrahman772-ui.github.io/void-runner/

## 📁 Project Structure

```text
void-runner/
└── index.html    # Complete game application
```

The current version keeps the game in a single HTML file for simple deployment and portability.

## 💡 Project Goals

Void Runner was created as a personal project to explore:

- Browser-based 3D graphics
- WebGL GPU rendering
- Three.js
- Real-time game loops
- Object movement and collision systems
- Enemy AI behavior
- Projectile systems
- Game-state management
- Performance monitoring
- Interactive HUD design
- Dynamic rendering-quality controls

## 👨‍💻 Author

**Rahil Abdul Rahman**

Computer Science Engineering (AI & Learning) student interested in:

- Python
- Software Development
- Artificial Intelligence
- Game Development
- Web Technologies

### Links

- **GitHub:** https://github.com/rahilrahman772-ui
- **Void Runner:** https://github.com/rahilrahman772-ui/void-runner
- **Live Demo:** https://rahilrahman772-ui.github.io/void-runner/

---

⭐ If you found the project interesting, consider starring the repository!