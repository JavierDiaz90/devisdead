# 山水 Shanshui

**Dither + ASCII + Motion** — a live, self-contained animation that renders a
Guilin karst landscape (peaks, pagoda, red sun, sailboat, water reflection and
drifting birds) as indigo ASCII using 8×8 Bayer ordered dithering.

- **Dither** — ordered-dither stipple mapped to a full ASCII brightness ramp
- **ASCII** — every cell is a real glyph, chosen by the brightness under it
- **Motion** — a per-frame flowing displacement field ripples the river and drifts the peaks
- **3D** — the whole plate tilts to your cursor on a live perspective, with depth parallax
- **Seasons** — click / tap to cycle the palette (spring · dusk · jade · ink)

Everything is drawn procedurally in the browser — no external images, fonts, or
scripts. Just open `index.html`.
