---
name: gptimg2-4-office
description: Use when creating attractive infographics, explanatory visuals, document covers, or slide visuals for Word, PowerPoint, or a single-page HTML site; especially when a user has content but needs a clear layout, an image-generation brief, and office-ready output.
---

# GPT Image 2 for Office

Create clear, editable office visuals. Treat AI images as assets and use HTML, Word, or PowerPoint for final copy.

## Workflow

1. Extract audience, format, aspect ratio, and one-sentence takeaway.
2. Reduce content to one title and 3–5 points. Put supporting detail in speaker notes or document body, not the visual.
3. Choose a layout from `references/office-visual-patterns.md`.
4. Create image prompts for illustrations, diagrams, textures, or a hero scene. Keep important words, numbers, citations, and tables editable.
5. Build a self-contained HTML page for composed infographics or slides. Use CSS Grid/Flexbox and real text; do not add frameworks unless requested.
6. Check hierarchy, legibility at 100%, factual accuracy, and whether it still works in grayscale. Then export or place the visual in the requested Office file.

## Choose the output

| Need | Use |
|---|---|
| Explain stages, deadlines, or history | Timeline |
| Explain how something works | Process flow |
| Contrast options or before/after | Comparison |
| Summarize a complex topic | Hero visual + 3–5 cards |
| Make a Word page feel polished | Cover/header visual + callout strip |

Prefer one-page HTML for PPT slides, report covers, infographics, or standalone images. Use native Word/PPT text where it must change, be copied, searched, or be accessible.

## Prompt protocol

Use this order. Replace brackets, remove unused fields, and keep it short.

```text
Create a [aspect ratio] [visual type] for [audience].
Topic: [topic]. Core takeaway: [one sentence].
Layout: [layout pattern] with [3–5 modules/steps].
Hero visual: [single metaphor or subject].
Style: [e.g., minimal editorial / soft 3D / warm watercolor].
Palette: [two accent colors] on [light/dark] background.
Leave generous blank space for editable text. Clear shapes, calm composition,
no watermark, no logos, no tiny labels, no unreadable or invented text.
```

Recreate important generated copy in HTML or Office; never rely on it for accuracy.

## Visual rules

- Use one visual metaphor, two fonts maximum, and two accents plus neutrals.
- Make the title the strongest element; make every card/step visually consistent.
- Use 16:9 for slides, A4/Letter portrait for Word pages, and 4:5 only for social sharing.
- Use high contrast. Avoid text on busy images; add a solid or translucent panel behind it.
- Use short labels: 2–6 words. Use icons only when they clarify meaning.
- For a Word/PPT series, reuse the same palette, corner radius, spacing, and illustration style.

## Deliverables

Return, as applicable:

1. a concise visual brief;
2. an image-generation prompt;
3. a self-contained HTML file or editable Word/PPT content;
4. a one-line placement/export note.

Read `references/office-visual-patterns.md` for layouts and prompt selectors.

## Avoid

- Dense AI-made posters with many tiny text labels.
- More than five equal-priority sections.
- Literal 3D charts when a simple bar, line, or table is clearer.
- Photorealistic people as decoration for analytical material.
- Imitating living artists or brand identities; use descriptive visual qualities instead.
