# List, Two Ways

A list-component system for IXD-404 (Week 5, Dan Park) — one shared structural grid (left slot, 1/2-line text, trailing slot, navigate vs. expand, default/hover/pressed states), rendered through an ASCII lens in two tones:

- **Static Hour** — nostalgic, dream-pop. A live dye-diffusion field (Jos Stam's stable-fluids solver) rendered as hard-pixelated monospace characters under real film grain and a VT323 scanline. Click to bloom color into the field; moving the cursor through it parts it like wiping condensation off glass, then it fades back.
- **Undertow** — dramatic, fluid dynamics. The same solver run lower-viscosity and more turbulent, with a built-in wave source so there's always motion on screen, a live velocity readout, and a cursor that interrupts the current rather than adding to it.

Both sets implement the full brief: left slot (icon / avatar / thumbnail / none), one- and two-line rows, trailing text/icon/both, a clickable navigate action and an expandable action, all three interaction states, and the component spec (spacing, type, radius, color, motion, and the generative field's own parameters) shown inline rather than as a separate Figma file. Each set also has a "Show measurements" toggle that draws live dimension lines on a row, read directly off the DOM.

Open `index.html` directly, or enable GitHub Pages on this repo (Settings → Pages → deploy from `main`) to get a live link.
