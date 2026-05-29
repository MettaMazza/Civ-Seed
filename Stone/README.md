# Stone — Granite-Ready Engraving Files

Compressed versions of the Seed vault, formatted for laser engraving on stone, metal, ceramic, or any durable surface.

---

## The Scaling Problem

Different engravers have different surface areas. A 30cm x 30cm tile holds very different content than a 1m x 2m granite slab. The content must scale to fit any medium.

### How It Works

Every slab file has a known **character count**. Your engraving surface has a known **character capacity** (determined by dimensions and font size). Divide and distribute.

### Quick Reference — Slab Sizes

| Slab | File | Characters | Words | Priority |
|------|------|-----------|-------|----------|
| 1 | 01_The_Rosetta.md | 7,222 | 1,373 | CRITICAL |
| 2 | 02_Survival_Fire_Measure.md | 5,183 | 917 | CRITICAL |
| 3 | 03_The_Body.md | 6,252 | 1,057 | CRITICAL |
| 4 | 04_The_Soil.md | 4,397 | 729 | CRITICAL |
| 5 | 05_The_Warning_and_Within.md | 7,614 | 1,266 | CRITICAL |
| 6 | 06_The_Matter.md | 4,903 | 817 | IMPORTANT |
| 7 | 07_The_Build.md | 5,103 | 829 | IMPORTANT |
| 8 | 08_The_Signal.md | 4,408 | 744 | IMPORTANT |
| 9 | 09_The_Sky.md | 4,414 | 750 | IMPORTANT |
| **Total** | | **49,496** | **8,482** | |

### Priority Order

If you can only engrave a limited number of surfaces, do them in this order:

1. **Slab 1 — The Rosetta** — without the decoder, everything else is noise
2. **Slab 5 — The Warning and Within** — the WHY. The pattern. The principles
3. **Slab 3 — The Body** — what kills and how to stop it
4. **Slab 4 — The Soil** — how to grow food
5. **Slab 2 — Survival** — fire, measure, energy, mechanics

After these five, the reader can survive, grow food, treat injuries, and understand why the vault exists. Slabs 6-9 add depth.

---

## Calculating Your Capacity

Use `calculator.html` (open in any browser) or calculate manually:

### Manual Method

1. **Measure your engraving surface** in millimetres (width x height).
2. **Choose your font size** in millimetres (character height).
   - 3mm = readable at arm's length, very dense
   - 5mm = readable at close range, moderate density
   - 8mm = readable at a few paces, low density
   - 12mm+ = readable from a distance, very low density
3. **Calculate characters per line**: surface width / (font size x 0.6)
   - The 0.6 factor accounts for character width being narrower than height
4. **Calculate lines per surface**: surface height / (font size x 1.5)
   - The 1.5 factor accounts for line spacing
5. **Calculate total character capacity**: characters per line x lines per surface
6. **Compare to slab character counts** above

### Examples

**Small tile (300mm x 300mm, 5mm font):**
- Chars per line: 300 / (5 x 0.6) = 100
- Lines: 300 / (5 x 1.5) = 40
- Capacity: 4,000 characters
- Result: each slab needs 1-2 tiles

**Medium slab (600mm x 400mm, 5mm font):**
- Chars per line: 600 / 3 = 200
- Lines: 400 / 7.5 = 53
- Capacity: 10,600 characters
- Result: most slabs fit on one surface. The whole vault fits on 5 slabs.

**Large slab (1000mm x 600mm, 8mm font):**
- Chars per line: 1000 / 4.8 = 208
- Lines: 600 / 12 = 50
- Capacity: 10,400 characters
- Result: similar to medium but more readable at distance.

**Monumental (2000mm x 1000mm, 12mm font):**
- Chars per line: 2000 / 7.2 = 277
- Lines: 1000 / 18 = 55
- Capacity: 15,235 characters
- Result: the entire vault fits on 4 surfaces with room to spare.

---

## Formatting Rules for Engraving

1. ALL CAPS for section headers
2. No markdown formatting (no *, no #, no |)
3. Blank lines between sections for visual separation
4. Numbers use digits (1, 2, 3) not words (one, two, three)
5. Dashes (—) for emphasis instead of bold/italic
6. Each slab begins with its number and title: "SLAB 1 — THE ROSETTA"
7. If splitting a slab across multiple surfaces, mark: "SLAB 1 — PART 1 OF 2"

---

## Multi-Surface Distribution

If a slab exceeds your surface capacity, split at a section break (a blank line between two ALL CAPS headers). Never split mid-paragraph or mid-procedure.

If your surfaces are very small (under 2,000 characters), the slabs can be further subdivided into **blocks**. Each ALL CAPS header in a slab file marks a natural block boundary. Blocks can be distributed independently.

---

## Adding Diagrams

If your laser cutter supports line drawings, the following concepts benefit enormously from visual representation:

| Concept | Slab | Description |
|---------|------|-------------|
| 3-4-5 right triangle | 2 | A triangle with sides marked 3, 4, 5 and the right angle marked |
| Bow drill | 1 | The fire-starting apparatus: board, spindle, bow, socket |
| Bellows | 7 | Two boards hinged with leather sides, nozzle, valve |
| The arch | 7 | Wedge-shaped stones in a curve with keystone marked |
| Bowline knot | 7 | The loop knot tied in sequence |
| Opposing twist (rope) | 6 | Two bundles twisting in opposite directions |
| Balance scale | 2 | A beam on a pivot with two pans |
| Water wheel | 2 | A wheel with paddles in falling water |

Diagrams are not included in the text files. They should be created separately and engraved alongside the relevant text block.

---

## Translation

If translating into another language:
- Maintain plain, direct language. No academic register.
- Preserve ALL procedural steps exactly. Do not summarise or paraphrase procedures.
- Preserve all warnings (things that kill) with maximum clarity.
- Test the translation with a native speaker who has no technical background. If they cannot follow a procedure from the translated text alone, the translation has failed.

---

## License

This work is released into the public domain. No rights reserved. Copy it. Translate it. Engrave it. Bury it. The entire purpose is survival of the knowledge, not control of it.
