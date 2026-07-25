# Office visual patterns

## Default design tokens

Start with `#0F2742` navy, `#12A6A6` teal, `#F6F3ED` warm white, and `#44505C` slate. Use 24–40 px outer padding, 16–24 px card gaps, 12–20 px rounded corners, and one soft shadow at most.

## Layout recipes

### Timeline

Use for 3–6 chronological steps. Give every step a date/phase, short label, and one result. Use a single direction and avoid crossing connectors.

### Process flow

Use for a repeatable system. Draw 3–5 verbs in sequence. Make the key decision or output visually larger; use arrows only to show movement.

### Comparison

Use for two choices only. Give each side the same four comparison rows. Highlight the recommendation with color rather than adding more words.

### Hero plus cards

Use for a single topic with 3–5 supporting insights. Put one illustration/diagram on one side, and use consistent cards on the other. This is the default for presentation slides.

### Word report cover

Use a generous title area, subtitle/date/author, one quiet background or illustration, and a small color strip. Do not fill the page.

## HTML starter rules

- Build one self-contained `index.html` with inline CSS unless a project already has a different pattern.
- Set a fixed artboard size for export: `1600 × 900` for 16:9 slides; `1240 × 1754` for A4 portrait.
- Use semantic headings and real text. Do not rasterize copy.
- Use SVG icons or simple CSS shapes before generating decorative icons.

## Image prompt style selectors

| Situation | Prompt language |
|---|---|
| Business explainer | minimal editorial illustration, clear geometric shapes, calm premium palette |
| Technology/process | clean isometric diagram, subtle 3D depth, modular elements, restrained labels omitted |
| Education | friendly flat illustration, clear visual sequence, warm accessible color palette |
| Report cover | modern abstract editorial collage, generous negative space for title |
| Premium topic | refined paper texture, soft directional lighting, restrained metallic accent |
