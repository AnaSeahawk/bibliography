# Frawley — *Ayurveda and the Mind: The Healing of Consciousness* (1996)

**File:** `Frawley-Ayurveda-and-the-Mind.pdf`
**Format: IMAGE SCAN — no extractable text layer.**

## Extraction status

This PDF is a photographic scan. No text layer present. Standard extraction tools fail:
- `strings`: returns only encoding metadata
- `pdftotext`: not installed

OCR required:
```bash
sudo apt install poppler-utils tesseract-ocr
pdftoppm Frawley-Ayurveda-and-the-Mind.pdf /tmp/frawley_pages -png
tesseract /tmp/frawley_pages-0001.png stdout
```

---

## Contents and key arguments

This is the most comprehensive treatment of the Ayurvedic psychology of the three vital essences: **Prana** (life-force), **Tejas** (inner fire/intelligence), and **Ojas** (vital fluid/immunity). Frawley argues that all three must be cultivated together — Ojas without Tejas is stagnation; Tejas without Ojas is burning.

**Central sections to locate:**

- Part I: The Nature of the Mind in Ayurveda — three qualities (sattva, rajas, tamas) and their physiological correlates
- Chapter on Prana, Tejas, Ojas — the three master forms of the three doshas
- The relationship between Ojas and reproductive tissue (shukra dhatu) as source of immunity
- Ojas as both physical substance (measurable, located in the heart) and subtle field
- The practice of building Ojas: diet, herbs, rest, meditation, conservation of vital fluids
- Tejas as the discriminative intelligence that allows Ojas to be used well rather than wasted

---

## Key passages to locate once OCR'd

- Frawley's definition of Ojas as "the immune system at the level of pure consciousness"
- The distinction between para ojas (eight drops, located in the heart) and apara ojas (the broader vital reserve)
- "Ojas is what remains when all the metabolic processes of the body are completed" — or similar formulation
- The relationship between Soma (the plant/drink) and Ojas (the bodily substance): Soma is the herb that builds Ojas
- The warning about Ojas depletion: what depletes it (excess sex, stress, grief, illness) and what restores it

---

## Archive relevance

- **Presentation translation table**: Ojas/Tejas/Prana as the three modes of the living essence — a finer map than just "ojas." The triple mirrors the Sulphur/Mercury/Salt triad in alchemy. Worth adding to the translation table in a future revision.
- **Sovereign biophysics**: Ojas as measurable biological substance (IgA, neuroimmune factors?) is the bridge claim. Frawley doesn't make this himself but it is implied by the framework.
- **Distillation parallel**: "what remains when all metabolic processes are completed" is the definition of a final distillate. This is the Ayurvedic formulation of the alchemical lapis.
