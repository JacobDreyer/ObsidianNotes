Changes the structure of the hash table so that each array location can represent multiple values

Each Location is called a "Bucket"
- A Bucket Can Be:
	- A List
	- A sorted List ([[Tree Set]])
	- A Chain of linked nodes ([[Linked List]])
	- An [[Array]]
	- a Vector

- If there isnt a collision at another spot we only have to search a linked list containing 1 item which maintains a good time complexity

Seperate Chaining is simple but requires additional memory outside the table

