```dataview
table without id title as Title, author as Author, status as Status, order
FROM #book 
where !contains(tags, "template")
sort file.order asc
```
```dataview
list file.tags
from #book  
```
