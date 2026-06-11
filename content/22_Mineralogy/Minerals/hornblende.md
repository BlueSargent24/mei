---
tags:
  - mineral
  - silicates/inosilicate
category:
  - Silicates
formula: (K,Na)₀₋₁(Ca,Na,Fe,Mg)₂(Mg,Fe,Al)₅(Al,Si)₈O₂₂(OH)₂
etymology: German *Horn* ("horn") and *blende* ("deceiver"), referring to its horn-like appearance and tendency to be mistaken for other minerals.
crystalsystem: Monoclinic
crystalclass: Prismatic
hardness: 5–6
color: Dark green, black, brown
streak: Colorless to pale gray
cleavage: Two directions at 56° and 124°
specificgravity: 2.9–3.4
luster: Vitreous to dull
opticaltype: Biaxial (-)
pleochroism: Strong; green to brown to black
synonyms: Common amphibole
habit: Prismatic, elongated crystals, often fibrous or columnar
specimen:
microscopic:
  - z_attachments/ts hornblende ppl.jpg
  - z_attachments/ts hornblende xpl.jpg
image: https://www.mindat.org/imagecache/b7/44/09582180017382710507738.jpg
---


## General Properties

`VIEW[**Formula:** {formula}][text(renderMarkdown)]`
`VIEW[**Hardness:** {hardness}][text(renderMarkdown)]`
`VIEW[**Crystal System:** {crystalsystem}][text(renderMarkdown)]`
`VIEW[**Crystal Class:** {crystalclass}][text(renderMarkdown)]`
`VIEW[**Color:** {color}][text(renderMarkdown)]`
`VIEW[**Streak:** {streak}][text(renderMarkdown)]`
`VIEW[**Cleavage/Fracture:** {cleavage}][text(renderMarkdown)]`
`VIEW[**Specific Gravity:** {specificgravity}][text(renderMarkdown)]`
`VIEW[**Luster/Transparency:** {luster}][text(renderMarkdown)]`

---

### Specimens

```meta-bind
INPUT[imageListSuggester(optionQuery("")):specimen]
```


---
## Optical Properties

`VIEW[**Type:** {opticaltype}][text(renderMarkdown)]`
`VIEW[**Pleochroism:** {pleochroism}][text(renderMarkdown)]`

### Thin Section


```meta-bind
INPUT[imageListSuggester(optionQuery("")):microscopic]
```

---

## Occurrence

```dataview
TABLE WITHOUT ID
    file.link AS "Rock",
    rock_type,
    choice(contains(essential_minerals, link(this.file.name)), "✅", "") AS "Essential In",
    choice(contains(accessory_minerals, link(this.file.name)), "✅", "") AS "Accessory In"
    
WHERE contains(essential_minerals, link(this.file.name))
   OR contains(accessory_minerals, link(this.file.name))
```
