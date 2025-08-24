# Current Reading Status

```dataview
table without id 
	title as Title, 
	author as Author, 
	choice(contains(status,"to_read"), "To Read", 
	choice(contains(status,"reading"), "Reading", 
									   "Finished")) as Reading,
	choice(contains(tags,"Purchased"), "Purchased", 
									   "Not Owned") as Owned
FROM #book 
where !contains(tags, "template")
sort order asc
```
