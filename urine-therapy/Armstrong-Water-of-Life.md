# Armstrong — *The Water of Life: A Treatise on Urine Therapy* (1944)

**File:** `Armstrong-Water-of-Life.epub`
**Extraction method:**
```bash
cp Armstrong-Water-of-Life.epub /tmp/armstrong.zip
unzip -q /tmp/armstrong.zip -d /tmp/armstrong_extract
# content in text/part000N.html
# key files: part0004.html (Ch. II — history/distillation argument),
#            part0005.html (Ch. III — objections answered / rebuilding passage),
#            part0007.html (Ch. V — gangrene / living solution quote)
sed 's/<[^>]*>//g' /tmp/armstrong_extract/text/part0007.html | grep -v "^[[:space:]]*$"
```

---

## Key quotes

### Urine as living tissue (Ch. V — *Gangrene*, part0007.html)

> Yet need we be surprised, once we understand that urine is not dead matter, but so to say, flesh, blood and vital tissues in living solution?

Context: after documenting a complete gangrene cure in 18 days using urine fasting and compresses. The question follows the observation that the urine formed new skin.

---

### The body distils its own medicine (Ch. II — *The Water of Life*, part0004.html)

Quoting Mr. Ellis Barker:
> "Our body distils the most wonderful medicines and provides the most perfect serums and anti-bodies."

Armstrong continues:
> Thus urine extolled by many of the ancients, but misunderstood by the semi-moderns, now appears in the light of a wonderful reservoir—a philtre of pre-eminent value. It contains in a pure and often undreamt of quantity, products of the most vital nature...

---

### The rebuilding passage (Ch. III — *Some Objections Answered*, part0005.html)

> Urine, on being taken into the body, is filtered; it becomes purer and purer even in the course of one day's living upon it, plus tap-water, if required. First, it cleanses, then frees from obstruction and finally rebuilds the vital organs and passages after they have been wasted by the ravages of disease. In fact it rebuilds not only the lungs, pancreas, liver, brain, heart, etc., but also repairs the linings of brain and bowel and other linings, as has been demonstrated in the case of many "killing" diseases, such as consumption of the intestines and the worst form of colitis. In fine, it accomplishes what fasting merely on water or fruit juices (as some naturopaths advocate) can never achieve.

---

### Nature returns what the soil produces (Ch. III)

> We find that where instead of "scientific" manures, the dead leaves are put back into the soil, the resultant flowers are the most fragrant, the fruits the sweeter, and the trees the healthier... The idea that Nature is wasteful is erroneous. She only appears wasteful to us because we do not understand her.

---

### Urine analysis in the 17th century (*Salmon's English Physician*, 1695, quoted in Ch. II)

> Urine is taken from human kind and most four-footed animals; but the former is that which is chiefly used in Physick and Chemistry. It is the serum or watery part of the blood, which being diverted by the emulgent arteries to the reins is there separated, and by the ferment of the parts, converted into urine...

---

## Archive relevance

- **Amaroli / urine-therapy section**: Armstrong is the foundational Western source. The "living solution" quote is the most concise statement of why urine is not waste — essential anchor for the distillation method writing.
- **Sovereign biophysics manifesto**: the body-as-laboratory argument; the body distilling its own remedies is the core claim the archive extends and documents experimentally.
- **Women of Alchemy essay**: the philtre/reservoir language — urine as *prima materia*, the thing underfoot that practitioners knew was medicine. Connects suppressed knowledge lineage to the body's own products.
- **Translation map**: the "Nature is not wasteful" passage parallels the alchemical principle that nothing in the vessel is refuse — all transformation is part of the work.
