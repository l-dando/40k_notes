<<<<<<< Updated upstream
<<<<<<< Updated upstream
<<<<<<< Updated upstream
# Current Reading Status

=======
 # Current Reading Status
>>>>>>> Stashed changes
=======
 # Current Reading Status
>>>>>>> Stashed changes
=======
 # Current Reading Status
>>>>>>> Stashed changes
```dataview
table without id 
	title as Title, 
	author as Author, 
	choice(contains(status,"to_read"), "To Read", 
	choice(contains(status,"reading"), "Reading", 
									   "Finished")) as Reading,
<<<<<<< Updated upstream
<<<<<<< Updated upstream
<<<<<<< Updated upstream
	choice(contains(tags,"Purchased"), "Purchased", 
=======
	choice(contains(tags,"Purchased"), "Purchased",  
>>>>>>> Stashed changes
=======
	choice(contains(tags,"Purchased"), "Purchased",  
>>>>>>> Stashed changes
=======
	choice(contains(tags,"Purchased"), "Purchased",  
>>>>>>> Stashed changes
									   "Not Owned") as Owned
FROM #book 
where !contains(tags, "template")
sort order asc
```

