# Gerard Baldo — Personal Portfolio & Systems Showcase

> High-performance personal engineering portfolio built with **Astro**, **Vanilla JavaScript**, **Three.js (WebGL 2.0)**, **Leaflet.js**, and **Tailwind CSS**.

---

## 🚀 Key Systems & Showcase Architecture

### 1. Spatial E-Commerce Engine (`// SPATIAL_ECOMMERCE_ENGINE`)
* **3D Viewport Architecture**: Asynchronous GLTF model parsing and rendering powered by `Three.js` and WebGL 2.0.
* **Auto-Normalization Pipeline**: Calculates GLTF bounding box matrices dynamically to auto-scale assets to a target focus volume (`1.8` units) and re-centers geometries.
* **Studio Lighting & Reflections**: Configured ACES Filmic tone mapping and a custom `PMREMGenerator` environment map generator to render realistic metallic and gemstone reflections.
* **Context-Preserving Fullscreen Modal**: Toggling `[ FULLSCREEN ]` migrates the active `<canvas>` element directly into an `h-[85vh]` modal container without tearing down or reconstructing the underlying WebGL context, camera, or model buffers.

---

### 2. Unified Intake & Spatial Mapping Engine (`// UNIFIED_INTAKE_SPATIAL_MAPPING`)
* **GIS Map Integration**: Lightweight, zero-friction coordinate mapping built over `Leaflet.js` and OpenStreetMap.
* **Relational Coordinate Registry**: Interactive pin commitment system (`COMMIT_PIN`) caching latitude and longitude vectors in memory with instant pin recall and auto-panning.
* **Case Study Page**: Dedicated technical overview located at [`/projects/spatial-map`](file:///d:/Portfolio/src/pages/projects/spatial-map.astro).

---

### 3. Ongoing Project Sandbox (`// ONGOING_PROJECT_SANDBOX`)
* **Experimental Workspace**: Live prototyping dashboard located at [`/projects/ongoing-project`](file:///d:/Portfolio/src/pages/projects/ongoing-project.astro).
* **Modular Hero Nodes**: Staged sandbox containers for WebGL fragment shader calculations, vector particle physics engines, and relational graph schemas.
* **Telemetry Stream Logger (`// SIMULATION_SOCKET`)**: Real-time terminal log streamer simulating socket telemetry, compile states, and socket packet inspection.

---

## 🎨 UI & Design System

* **Tabbed Showcase Navigation**: Dynamic `#project-tabs` view controller that cleanly switches visible cards between projects with active tab styling and smooth transitions.
* **Brutalist Technical Aesthetic**: Custom dot-matrix background grids, rigid brutalist card shadows (`rigid-card`), and blinking terminal path cursors (`.terminal-path`).
* **Theme System**: Persisted Dark / Beige (`BEIGE_MODE`) theme toggler synchronized across all pages via `localStorage`.

---

## 📁 Repository Structure

```
d:/Portfolio/
├── src/
│   ├── pages/
│   │   ├── index.astro                 # Main portfolio page & project tab controller
│   │   └── projects/
│   │       ├── spatial-map.astro       # GIS Intake case study page
│   │       └── ongoing-project.astro   # Experimental sandbox & telemetry socket stream
│   └── styles/
│       └── global.css                  # Global Tailwind CSS directives & tokens
├── public/
│   └── assets/
│       └── models/                     # Staged 3D GLTF asset files (.glb)
├── astro.config.mjs                    # Astro configuration file
└── package.json                        # Node dependencies & script manifests
```

---

## 🧞 Local Development & Commands

Run all commands from the project root:

| Command | Action |
| :--- | :--- |
| `npm install` | Installs project dependencies |
| `npm run dev` | Starts local development server at `http://localhost:4321` |
| `npm run build` | Compiles static production site into `./dist/` |
| `npm run preview` | Previews production build locally |

---

## 🛠️ Verification & Build Status

- Verified static production compilation with `npm run build`.
- Built routes:
  - `/index.html`
  - `/projects/spatial-map/index.html`
  - `/projects/ongoing-project/index.html`
