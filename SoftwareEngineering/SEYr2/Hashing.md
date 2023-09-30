## Hashing
#### What is it?
- A technique that determines a storage index or location for storing an item in a data structure
- the hash function receives the element to store and returns the index of an array where the element is stored
	- In this case the array is called the hash table, and
	- the index is known as the hash-code or hash-index

### [[Hash Function]]
![[Hash Function]]

### [[Collision Handling]]
![[Collision Handling]]

### [[Locations in the Hash Table]]
![[Locations in the Hash Table]]

### Retrieving, Removing, Adding
- To retrieve an entry
	- Search the probe sequence for the key
	- Examine entries that are present, ignore locations in availible state
	- Stop search when key is found or null is encountered
- To remove an entry
	- Search the probe sequence
	- if key is found mark location as availible
- To add an entry
	- search the probe sequence
	- Note first availible location
	- Use availible slot if the key is not found

