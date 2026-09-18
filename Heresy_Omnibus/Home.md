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
