# Gerard Baldo | System-First Software Engineer Portfolio

A premium, developer-centric portfolio designed around a brutalist, blueprint-inspired engineering aesthetic. Built on Astro for high-performance static rendering, vanilla CSS system variables for instant theme toggling, and targeted vanilla JS controllers for fluid client-side interactive telemetry.

---

## 🛠️ Core Technology Stack & Architecture

- **Core Framework**: [Astro](https://astro.build) (Target: `ESNEXT`) — statically pre-rendered to ship zero client-side JavaScript by default.
- **Style Compilation**: [Tailwind CSS v4](https://tailwindcss.com) — utility-first structure paired with custom system design parameters.
- **Interface Orchestration**: Vue.js pipelines (for main relational state management).
- **Validation Guardrails**: Cypress, Playwright, and Postman API profiling.
- **Map System**: [Leaflet.js](https://leafletjs.com) — selected for zero-friction corporate handoff, token-free initialization, and layout performance.

---

## 🚀 Key Enhancements & Changes (Redesign Draft)

We have implemented a series of micro-interactions, telemetry widgets, layout enhancements, and theme fixes to elevate visual fidelity and client-side responsiveness.

### 1. Interactive Capstone Card (`SPATIAL_ECOMMERCE_ENGINE`)
- Swapped out the old static DSWD project details accordion card for a split-layout capstone card.
- Implemented a dual-panel display view:
  - `--spec`: Standard functional description detailing object manipulation and paint-cycle optimizations.
  - `--verbose`: Virtual compiler stream output displaying Virtual Core context, WebGL binding engines, and streaming allocations.
- Included a real-time GPU render status widget.

### 2. Live Telemetry Widget (`// EVENT_TELEMETRY_LOGS`)
- Embedded a command-line log streamer panel inside the right-hand aside column of the dashboard.
- Configured a log streamer script to output sequential boot sequences (OK, SPEC, INFO, RDY status flags) using natural network stepping delays when a client lands on the page.
- Prevented click propagation so that clicking the console does not trigger the metrics toggle card.

### 3. Spec-Sheet Manifesto Redesign
- Replaced paragraphs inside the *System Over Syntax* component with a structured table outlining project **Constants**, **Variables**, **Core Value**, and **Operational Capabilities** check-lists.

### 4. Case Study Page Redesign (`spatial-map.astro`)
- Restructured the single-column case study page into the asymmetric 12-column grid layout to unify it with the main dashboard.
- Integrated the `// ENGINE_METRICS` column and its collapsible build walkthrough console.
- Injected command-line path headers with active blinking cursors (`.terminal-path`) at the top of each case study section.

### 5. Theme-Aware Card Hover Colors & Readability Fix
- Redesigned hover styles for `.system-card`:
  - **Dark Mode**: Applied subtle dark background highlights (`rgba(30, 30, 30, 0.4)`) and muted border highlights to ensure text readability.
  - **Light (Beige) Mode**: Maintained warm sand highlights (`rgba(235, 231, 220, 0.6)`) and custom border colors (`#d3cdb3`).

### 6. System Micro-Animations
- **Pulsing Status Indicator (`.engine-status-active`)**: A pulsing CSS keyframe glow showing environment active status.
- **Blinking Terminal Cursor (`.terminal-path`)**: A terminal block cursor animation appended to file paths.

### 7. Copy Polish & Technology Badge Upgrades (Phase 2)
- **Manifesto Realignment**: Replaced the placeholder constants/variables spec grid with professional copy emphasizing robust architecture, structural execution, data integrity, and cross-stack logic.
- **Platform Solutions Spec Consolidation**: Streamlined the sidebar spec box across all templates to showcase a single authoritative credential: *Freshservice Advanced Product Certification*.
- **Interactive Monochrome Badge Grid**: Upgraded the capabilities text blocks to an interactive grid of monochrome badges (Vue, Laravel, Astro, Cypress, Playwright, Postman) that dynamically light up with their brand colors upon hover.
- **Telemetry Event Log Refinement**: Swapped generic compiler logs for professional execution logs, including ITSM rollouts, custom local-only productivity apps, and Laravel payload verification.

---

## 🧞 Local Commands

All commands are run from the project root:

| Command | Action |
| :--- | :--- |
| `npm install` | Installs dependencies |
| `npm run dev` | Starts local dev server at `localhost:4321` |
| `npm run build` | Compiles production bundle to `./dist/` |
| `npm run preview`| Preview the production bundle locally |
