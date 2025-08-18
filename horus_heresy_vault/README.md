Book order and current 
```dataview
table without id title as Title, author as Author, status as Status, order as Order
FROM #book 
where !contains(tags, "template")
sort order asc
```

