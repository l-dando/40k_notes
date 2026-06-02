# 🏛️ Warhammer 30K Reading Campaign

Welcome to a chronological descent through the Horus Heresy. This vault tracks current progress, explores Legion ideologies, and surfaces thematic arcs across the galaxy’s unravelling.

Horus Rising
False Gods 
Galaxy in Flames 
The Flight of the Eisenstein
Fulgrim
The First Heretic 
Prospero Burns
Know No Fear 
Betrayer
Praetorian of Dorn 
The Master of Mankind
Slaves to Darkness

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
