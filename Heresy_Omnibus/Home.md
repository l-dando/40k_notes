# 🏛️ Warhammer 30K Reading Campaign

Welcome to a chronological descent through the Horus Heresy. This vault tracks current progress, explores Legion ideologies, and surfaces thematic arcs across the galaxy’s unravelling.

[[Heresy_Omnibus/Books/Novels/Horus Rising|Horus Rising]]
[[Heresy_Omnibus/Books/Novels/False Gods|False Gods]] 
[[Heresy_Omnibus/Books/Novels/Galaxy in Flames|Galaxy in Flames]] 
[[Heresy_Omnibus/Books/Novels/The Flight of the Eisenstein|The Flight of the Eisenstein]]
[[Heresy_Omnibus/Books/Novels/Fulgrim|Fulgrim]]
[[Heresy_Omnibus/Books/Novels/The First Heretic|The First Heretic]] 
[[Heresy_Omnibus/Books/Novels/Prospero Burns|Prospero Burns]]
[[Heresy_Omnibus/Books/Novels/Know No Fear|Know No Fear]] 
[[Heresy_Omnibus/Books/Novels/Betrayer|Betrayer]]
[[Heresy_Omnibus/Books/Novels/Praetorian of Dorn|Praetorian of Dorn]] 
[[Heresy_Omnibus/Books/Novels/The Master of Mankind|The Master of Mankind]]
[[Heresy_Omnibus/Books/Novels/Slaves to Darkness|Slaves to Darkness]]

## 📚 Reading Progress
```dataview
table order, title, status, omnibus
from "Heresy_Omnibus/Books"
where essential = "Yes"
sort omnibus, omnibus_order asc
```








## Legion Tracker
```dataview
table length(rows)   as "Book Count",
      list(rows.file.link) as "Books"
from "Heresy_Omnibus/Books"
flatten legions as Legion
group by Legion
sort Legion asc

```



## Theme Explorer
```dataview
table title, themes
from "Heresy_Omnibus/Books"
group by themes
```





## Quick Access
- [[Heresy_Omnibus/Tags|Tags]]
- [[Heresy_Omnibus/Dataview Queries|Dataview Queries]]
- [[Heresy_Omnibus/Chaos Influence|Chaos Influence]]



## Worldbuilding Indexes
- [[Heresy_Omnibus/Places/Places|Places]]
- [[Heresy_Omnibus/Events/Events|Events]]
- [[Heresy_Omnibus/Items/Items|Items]]


### Full List
# Phase I

## I. Heresy Rising

- Horus Rising
- False Gods
- Galaxy in Flames
- Flight of the Eisenstein
- Fulgrim

---

# Phase II

## II. Shadow Crusade I: Only the Faithful

- Battle for the Abyss
- The First Heretic
- Know No Fear

## III. The Burning of Prospero

- A Thousand Sons
- Prospero Burns

## IV. Shattersong

- Fulgrim
- Angel Exterminatus

---

# Phase III

## V. Shadow of the Warmaster I: Knives in the Dark

- Flight of the Eisenstein
- Nemesis

## VI. Shadow Crusade II: Underworld War

- Know No Fear
- Macragge's Honour

## VII. Anvil of War

- Legion
- Vulkan Lives

## VIII. Angels of Darkness

- Descent of Angels
- Fallen Angels

## IX. Omnissiah I: Death of Innocence

- Mechanicum

---

# Phase IV

## X. Shadow Crusade III: Chosen of Chaos

- Betrayer
- Fear to Tread

## XI. Ordu of the Khan

- Scars
- The Path of Heaven

## XII. The Truth of Iron

- The Damnation of Pythos

---

# Phase V

## XIII. Imperium Secundus I: Hope's Kindling

- The Unremembered Empire
- Pharos

## XIV. Shadow of the Warmaster II: Lords of Death

- Vengeful Spirit
- The Buried Dagger

## XV. Scale and Stone

- Legion
- Deliverance Lost
- Praetorian of Dorn

---

# Phase VI

## XVI. Imperium Secundus II: Fate's Ashes

- Angels of Caliban
- Ruinstorm

## XVII. Shadow of the Warmaster III: Jaws of Defeat

- Deliverance Lost
- Wolfsbane

## XVIII. Omnissiah II: End of Empires

- The Outcast Dead
- The Master of Mankind

---

# Phase VII

## XIX. Through the Neath

- Deathfire
- The Crimson King
- Old Earth

## XX. Shadow of the Warmaster IV: The Dead and the Dying

- Titandeath
- Slaves to Darkness

---

# Siege of Terra

## XXI. The Siege of Terra

- The Solar War
- Sons of the Selenar
- The Lost and the Damned
- The First Wall
- Saturnine
- Fury of Magnus
- Mortis
- Garro: Knight of Grey
- Warhawk
- Echoes of Eternity
- The End and the Death Vol. I
- The End and the Death Vol. II
- The End and the Death Vol. III
