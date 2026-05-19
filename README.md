# ◈ Analog Fidelity Lab

> Signal Processing · Retro Rendering · Texture Restoration · Chiptune

A suite of four client-side browser instruments for applying authentic analog, retro, and lo-fi character to images, video, and audio. No server. No dependencies. No data collected. Open a file and run.

---

## Instruments

### AFL-001 · Deglazer
**AI art texture restoration**

Strips the plasticky, over-smooth sheen from AI-generated images by layering real analog imperfection back in; film grain, chromatic aberration, halation, and analog noise. Works on still images and live camera input.

`Film Grain` `Chromatic Aberration` `Halation` `Live Camera`

---

### AFL-002 · CRT Lab
**Authentic phosphor emulator**

WebGL-accelerated CRT simulation with configurable presets. Renders scanlines, slot mask patterns, barrel distortion, bloom, color bleed, phosphor crawl, and phosphor persistence in real time. Supports video export.

`WebGL` `Phosphor` `Slot Mask` `Scanlines` `Video Export`

---

### AFL-003 · N64 Lab
**N64 Reality Signal Processor pipeline converter**

Emulates the RCP rendering pipeline of the Nintendo 64, low-poly vertex jitter, texture warping, limited color depth, Z-fighting artifacts, and point-sampled (3-point) filtering. For images that feel like they escaped a cartridge.

`RCP Pipeline` `Vertex Jitter` `Dithering` `3-Point Filter`

---

### AFL-004 · GB Note Player
**Handheld chiptune sequencer**

A Game Boy–style piano-roll instrument with per-channel waveform control, pulse width modulation, and envelope shaping. Rendered in DMG green palette with atomic purple housing aesthetic. Compose and export chiptune sequences directly in the browser.

`Chiptune` `Piano Roll` `Waveform` `DMG Palette` `Envelope`

---

## Usage

All instruments are self-contained HTML files. No build step, no install.

```
git clone https://github.com/Kasai-Kitsune/Analog-fidelity-Lab.git
cd Analog-fidelity-Lab
```

Open `index.html` in any modern browser. Click an instrument card to launch it. That's it.

Alternatively, each `.html` file can be opened directly on its own.

---

## Design Philosophy

Everything runs locally in the browser. No telemetry or no network calls; just open a file and use it. The instruments are intentionally self-contained so they work offline, stay private, and don't depend on anything that can go away.

---

## License

MIT — see [LICENSE](LICENSE)
