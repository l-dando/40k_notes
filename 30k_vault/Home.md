``# 🏛️ Warhammer 30K Reading Campaign

Welcome to a chronological descent through the Horus Heresy. This vault tracks current progress, explores Legion ideologies, and surfaces thematic arcs across the galaxy’s unravelling.

## 📚 Reading Progress
```dataview
table order, title, status, rating, owned
from "30k_vault/Books"
sort order asc
```





## Legion Tracker
```dataview
table length(rows)   as "Book Count",
      list(rows.file.link) as "Books"
from "30k_vault/Books"
flatten legions as Legion
group by Legion
sort Legion asc

```



## Theme Explorer
```dataview
table title, themes
from "30k_vault/Books"
group by themes
```



## Timeline Navigation
- [[Timeline/Pre-Heresy]]
- [[Timeline/Heresy]]
- [[Timeline/Siege of Terra]]


## Quick Access
- [[Tags]]
- [[Dataview Queries]]
- [[Chaos Influence]]

