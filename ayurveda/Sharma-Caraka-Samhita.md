# Sharma — *Caraka Saṃhitā* (trans. Priya Vrat Sharma, Chaukhambha Orientalia)

**Files:** `Sharma-Caraka-Samhita-Vol1.pdf` (209MB), `Sharma-Caraka-Samhita-Vol2.pdf` (155MB)
**Format: IMAGE SCAN (high-res scan of printed edition) — no extractable text layer.**

This is the standard scholarly English translation of the Caraka Samhita, published in the Jaikrishnadas Ayurveda Series. P.V. Sharma is one of the foremost translators of classical Ayurvedic texts. This edition preserves the Sanskrit alongside the English.

## Extraction status

PDFs are photographic scans of the printed book. No text layer:
- `strings`: encoding metadata only
- `pdftotext`: not installed

OCR required:
```bash
sudo apt install poppler-utils tesseract-ocr
pdftoppm Sharma-Caraka-Samhita-Vol1.pdf /tmp/caraka_pages -png -r 200
# Then per-page: tesseract /tmp/caraka_pages-0001.png stdout
```

Given the size (209MB, 155MB), OCR will take significant time. For targeted quotes, identify the relevant sutras first, then OCR those specific pages.

---

## Structure

**Vol. 1 covers:**
- Sūtrasthāna (general principles, diet, therapies) — Chapters 1–30
- Nidānasthāna (diagnosis) — Chapters 1–8
- Vimānasthāna (pathology, epistemology) — Chapters 1–8
- Śārīrasthāna (embryology, anatomy, soul) — Chapters 1–8

**Vol. 2 covers:**
- Indriyasthāna (prognosis, sense diagnosis) — Chapters 1–12
- Cikitsāsthāna (therapeutics) — Chapters 1–30
- Kalpasthāna (pharmacy, preparations) — Chapters 1–12
- Kalpasthāna continued / Siddhisthāna (pañcakarma, rasāyana) — Chapters 1–12

---

## Key sutras to locate

**On Ojas (bala/ojas as vital essence):**
- Sūtrasthāna 17.74–76: ojas as the essence of all dhatus (tissues), residing in the heart
- Cikitsāsthāna 1.1 (Rasāyana chapter): the comprehensive treatment of rasāyana — what builds ojas, what depletes it, the eight-drop para ojas
- Śārīrasthāna 6: embryological chapter — ojas formed during gestation, its role in fetal development

**On Agni (digestive and transformative fire):**
- Cikitsāsthāna 15: agni as the root of all metabolism; what weakens and strengthens it
- Vimānasthāna 5: the classification of agni types

**On Bhāvana (repeated processing):**
- Kalpasthāna: pharmaceutical preparations using bhāvana — the repeated soaking and drying process that concentrates potency in medicines. This is the Ayurvedic parallel to double distillation.

**On Anupana (vehicle/medium):**
- Sūtrasthāna 27: the role of the vehicle in directing medicines; water, milk, ghee, honey as anupanas; the anupana changes the site and depth of a medicine's action

**On Rasa (taste/essence/fluid):**
- Sūtrasthāna 26: rasa as primary category — the first contact, the first teaching of a substance to the body

---

## Key formulations to locate (for direct quote)

> "Ojas is the first substance formed in the body of the developing embryo... it is the essence of all the seven dhatus... It supports the body, sustains life, and if destroyed, life ceases."
*(Sūtrasthāna 17 — locate exact verse)*

> "Just as oil is the essence of sesame, ghee is the essence of milk, so Ojas is the essence produced from all the dhatus through proper digestion."
*(attributed to Caraka — locate)*

---

## Archive relevance

- **Presentation translation table**: Bhāvana = double distillation. Anupana = vehicle that carries the medicine to the deep tissue (the body's own anupana for its intelligence). These are the most precise Ayurvedic anchors in the presentation.
- **Translation map**: Ojas as the endpoint of the seven-dhatu chain (food → plasma → blood → muscle → fat → bone → marrow → ojas) maps exactly onto the alchemical "seventh distillation" or final refining.
- **Rasāyana chapter (Cikitsāsthāna 1)**: the classical Ayurvedic treatment of rejuvenation. This is the primary source for the claim that the body's own refined essence is the highest rasāyana.
