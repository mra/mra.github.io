# Project Image Generation Prompts

Prompts used to generate the project cover images on the site. They share a common style anchor so the cards form a cohesive set. Paste any of these into Midjourney / ChatGPT (DALL·E) / Gemini / Sora to regenerate.

## Style anchor (prepend or append to every prompt)

> clean scientific illustration, soft pastel palette of teal, sage green, ivory, and muted gold, flat vector style with subtle depth, dark navy/charcoal background, minimalist editorial style suitable for an academic portfolio header card, **16:9 aspect ratio**, no extraneous text.

---

## 1. Whole-body cardiovascular digital twin

> Stylized human silhouette in front view with a network of interconnected nodes representing heart chambers, arteries, veins, and major organs, linked by glowing teal flow lines suggesting blood circulation; electrical-circuit motifs (resistor, capacitor, inductor) overlaid faintly on the vessels to evoke the **RCR (Resistance–Compliance–Inertance) network** analogy.

Output file: `assets/img/projects/p1-cardiovascular.png`

---

## 2. Whole-body lymphatic transport

> Translucent human figure showing the lymphatic system as a delicate tree of nodes and vessels in muted gold and ivory, with floating particle paths suggesting **interstitial drug transport** into lymph nodes; faint connecting lines to a small circulatory system in the background.

Output file: `assets/img/projects/p2-lymphatic.png`

---

## 3. DigiLoCS — digital liver-on-chip simulator

> Top-down microfluidic chip with hexagonal **hepatocyte-like compartments**, channels flowing teal fluid through them, paired with a softly glowing schematic liver above the chip; small molecule icons traveling through the channels representing drug distribution. Include a callout showing parent drug → metabolite → protein-bound species.

Output file: `assets/img/projects/p3-digilocs.png`

---

## 4. Cranial–spinal CSF & Circle of Willis

> Anatomical mid-sagittal view of a human head in sage green tones with the **Circle of Willis** highlighted as a luminous loop of vessels at the brain base; flowing CSF shown as teal ribbons cycling between cranial and spinal compartments; **Monro–Kellie volume coupling** depicted as balanced compartments (brain tissue, blood, CSF).

Output file: `assets/img/projects/p4-csf.png`

---

## 5. Insulin–glucose system & T2D subtypes

> Abstract metabolic diagram: pancreas releasing insulin (teal particles) coupled with a glucose curve (muted gold) on a stylized time axis, with three loosely clustered patient silhouettes off to one side suggesting **patho-clinical subtypes** of type 2 diabetes (insulin-deficient, insulin-resistant, mixed/severe).

Output file: `assets/img/projects/p5-insulin.png`

---

## 6. PBPK DSL + AI agents (DMTA cycle)

> Schematic flow diagram of a **Design–Make–Test–Analyze (DMTA) loop** with four icons (DNA, beaker, microscope, chart), connected by a circular arrow; small **AI-agent glyphs** (hexagonal node with neural-net pattern) sitting on each step; code-like compartment-model boxes floating between nodes; show a PBPK DSL syntax snippet in one corner.

Output file: `assets/img/projects/p6-dsl-agents.png`

---

## 7. Hero / banner (home page)

> Abstract scientific composition: faint cardiovascular tree, hepatic chip outline, and lymphatic network blended into a flowing teal–sage gradient; multi-system integration view evoking digital twins. **Aspect ratio 21:9** (or wider), suitable as a hero-section background; no text.

Output file: `assets/img/projects/hero.png`

---

## Tips for regeneration

- Tools tried: ChatGPT/DALL·E (good for square 1:1), **Gemini (used for current set — best contrast and label rendering)**, Midjourney.
- If labels render with typos or garbled text, ask the tool to **regenerate without text** and add labels yourself in post.
- Keep the dark background palette consistent across all 7 so the project cards feel like a single set.
- Card display crops to **4:3 top-aligned** on the site — so place titles and key labels in the upper half of the image.
