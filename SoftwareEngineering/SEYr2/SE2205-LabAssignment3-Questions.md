1. What is the goal of using hashing technique in Data Structure? 
	- Distribute entries uniformly through table
	- reduce search time so its independent of # of entries
2. Explain linear, quadratic, double hashing probing techniques? 
	- Linear: find hash index. locate next empty location
	- Quadratic: find hash index. locate next empty location at 1+i^2
	- DHashing: find hash index. compute second hash index find next empty location at: h1 + i\*h2
	- All should wrap around when exceeding length of array
3. What are the advantages of using open addressing over linear chaining? What is the price you pay to enjoy those advantages? 
	- Pros:
		- Less Memory
		- Quicker
	- Cons:
		- Could completely fill the table
		- More Complex
1. Best-case/worst-case time/space complexity of hashing technique in inserting/searching/removing data items when open addressing/linear chaining resolve collision. What is the rationale of your answer. 
	- Time:
		- Best: O(1) because we find an opening right away
		- Worst O(n) because we have to search whole array for opening
	- Space: Best and Worst O(n) because we always have the whole array set aside in memory and each always has a value associated with it
1. What is load factor. How does it play a role in hashing? Lab Assignment 3 SE2205a QMR 9 
	- measures for fullness. If its too large perfomance decreases
2. What is the use of ‘available’ flag in hashing? 
	- to determine whether a location had a value prior and was just rewritten
3. Based on the background provided in the lecture hand out, explain/show how (by drawing on the screen) for each run in both questions, a linear chain can be constructed. 
4. Explain/demonstrate how in q-2, run-2 the quadratic probing failed due to a load factor of greater than 0.5. Will this always happen? Demonstrate it using the following data set with a load factor of 0.75 in the order as shown: -7, 13, -29 40, 54. 
5. Demonstrate by hand what would be content of a hash-table when the data set from above (Q7) is used with load factor 0.75 for each of the following cases: linear probing resolve collision, quadratic probing resolve collision, doublehashing resolve collision, linear-chaining resolve collision. 
6. For the open addressing techniques, run your code and demonstrate that your code for open addressing is working fine. (The TAs will have the results) 
7. What is rehashing? Why is it required? How to accomplish this task. Explain how did you write the code for rehashing? 
	- It expands the array/table. its required if we need to add more values to the array but we have no space
8. Explain the method checkPrime()? 
9. Explain how the removeValue() method works. 
10. It seems to be much easier approach if we overwrite the hash table with no argument constructors, every time instead of defining a public static void method called emptyHashTable() method, which will reset the hashTable with values -1 (null-flag). What is the rationale behind defining this method?
