```dataview
table without id title as Title, author as Author, status as Status
FROM #book 
where !contains(tags, "template")
sort order asc
```
```dataview
list file.tags
from #book  
```
