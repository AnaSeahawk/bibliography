# Wolkstein & Kramer — *Inanna: Queen of Heaven and Earth* (1983)

**File:** `Wolkstein-Kramer-Inanna-Queen-of-Heaven.pdf`
**Format: IMAGE SCAN — no extractable text layer.**

## Extraction status

This PDF is a photographic scan of the printed book. There is no embedded text layer. Standard text extraction tools fail:
- `pdftotext`: not installed (requires poppler-utils)
- `python pdfplumber` / `pypdf`: no text layer to extract
- `strings`: returns only encoding metadata, no readable passages

**To get text from this book**, OCR is required:
```bash
# Requires poppler-utils and tesseract (needs sudo to install)
sudo apt install poppler-utils tesseract-ocr
pdftoppm Wolkstein-Kramer-Inanna-Queen-of-Heaven.pdf /tmp/inanna_pages -png
tesseract /tmp/inanna_pages-0001.png stdout
```

Alternatively: source the epub version from Anna's Archive (search for Wolkstein Inanna epub — a text-layer version may exist).

---

## Contents (from memory/prior reading)

This is the primary source translation. Two complementary parts:
- **Samuel Noah Kramer**: scholarly transliteration and annotation of the Sumerian tablets
- **Diane Wolkstein**: narrative retelling woven from the translations

Key texts included:
1. *The Descent of Inanna* — the central myth
2. *Inanna and the God of Wisdom* — the *me* (sacred powers) transfer
3. *The Courtship of Inanna and Dumuzi* — the sacred marriage
4. *The Dream of Dumuzi* — his foreknowledge of death
5. *Dumuzi's Death* — the descent of the beloved
6. *The Lament of the Flutes for Dumuzi*

---

## Passages to locate once OCR'd

- The seven gates passage: each piece of regalia removed, named
- "Holy Ereshkigal! Sweet is your praise!" — final line
- Inanna's abandonment of her domains before descent
- The *kurgarra* and *kalatur* mourning scenes
- Wolkstein's narrative framing of the descent as feminine initiation

---

## Archive relevance

- **Inanna essay**: THE primary source. Any direct quote from the myth must cite "trans. Kramer, in Wolkstein & Kramer 1983." Perera's *Descent to the Goddess* (also in this folder) draws directly on this translation.
- **Translation map**: the seven gates / stripping sequence is the structural spine of the descent pattern the archive traces across multiple traditions.
