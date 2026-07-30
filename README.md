# Analog Fidelity Lab

A small rack of browser-based hardware/film emulation tools. Each one is a single, dependency-free HTML file, no build step, no server, no upload leaving your machine.

## Units

| Unit | File | What it does |
|---|---|---|
| **AFL-001, Deglazer** | `deglazer.html` | Restores film-stock texture on AI art: grain, halation, chromatic aberration. |
| **AFL-002, CRT Lab** | `CRT_Lab.html` | Authentic phosphor emulator: shadow mask, scanlines, bloom, convergence error. |
| **AFL-003, N64 Lab** | `N64_Lab.html` | Emulates the N64's RCP render pipeline: trilinear filtering, dithering, low-res reconstruction. |

## Using it

Open `index.html`, it's the rack front panel and links out to each unit. To host it on GitHub Pages, keep all four files in the same folder (repo root, or one subfolder) so the relative links resolve, then point Pages at that location.

No build tools, no npm install, no dependencies. Everything runs client-side in the browser.

## Structure

```
/
├── index.html      ← rack index (this is the entry point)
├── deglazer.html   ← AFL-001
├── CRT_Lab.html    ← AFL-002
└── N64_Lab.html    ← AFL-003
```
