# 墨 — Dither + ASCII + Motion

A live homage to the "Dither + ASCII + Motion" look: an image dissolved into a
fine ink halftone of real glyphs. It reads photographic from across the room
and dissolves into individual characters up close.

**Live:** https://javierdiaz90.github.io/devisdead/

- **Dither** — ordered Bayer stipple maps every tone to ink grain — no greys, only density
- **ASCII** — every square cell is a real monospace glyph, from ` ` to `@`, chosen by the brightness under it
- **Motion** — the stipple lattice "boils" frame by frame, a living halftone rather than a frozen one
- **3D** — the whole plate tilts to your cursor on a live perspective, with parallax depth
- **Two inks** — strongly red pixels (a rising sun, a seal, a tongue) print in vermilion accent ink
- **Ink** — click / tap to cycle the ink & paper (sumi · indigo · vermilion · jade)

## The image

The page renders `dragon.jpg` from the repo root — drop in any image with that
name and it becomes the artwork, card aspect and all. If the file is missing,
a procedurally drawn giant panda takes its place. Visitors can also drag &
drop (or tap **换图 Swap Image**) to dither any picture of their own, live.

No build step, no external fonts or scripts. Open `index.html` or push to
`main` to deploy.
