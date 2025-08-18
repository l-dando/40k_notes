Book order and current 
```dataview
table without id order as Order, title as Title, author as Author, status as Status
FROM #book 
where !contains(tags, "template")
sort order asc
```

