In general, a hash function is generated based on the two steps:
- Step 1: The search key is converted into an integer called the hash code
- Step 2: The hash code is compressed into the range of indices for the hash table

Typical hash functions are not unique 
- They can allow more than one search keys to map into a single index
- This is known as a [[Collision]]

### Good Hash Functions
- Minimize [[Collision]]s
- Distribute Elements uniformly throughout the [[Hash Table]]
- Be fast to compute

### Generating [[Hash Codes]]
- Any search key is converted into an integer value called the has code
- You can use a [[Wrapper Class Reference Types]] and use .hashCode() to see the hash code of the value
	- For characters it returns the [[ASCII]] code for that character
	- for integers it returns the integer
- [[Folding]]:
	- Process of dividing a long search key into several pieces and then combining those pieces by using either addition or bitwise ex-or operation

The Hash Code for a String s
```java
int hash = 0;
int n = s.length();
for(int i=0; i<n; i++)
	hash = g * hash + s.charAt(i);
```
- Above procedure adds [[Unicode]] of the characters
- Java's hashCode() method in String class uses g=31
- Overflow:
	- This computation may result in an Overflow
	- Java ignores these overflows
	- For an appropriate choice of g the result will be reasonable
	- overflow may result in negative values
		- These are taken care of during the compression step

##### Generating our Own
- To generate a hash-code in Java we override the hashCode() methof availible in the [[Object Class]]

Guidelines:
- If a class overrides equals() it should override hashCode()
- If equals() true. hashCode() must also return the same value for each object
- if hashCode() is executed multiple times on data it must return the same value each time
- An objects hashCode can be different during one execution compared to another execution

### Compressing a Hash Code
- Must compress the hash code so it fits into the index range of a [[Hash Table]]
- typical method for hash code c
	- compute c % n
		- n is a prime number (the size of the table)
		- index will then be between 0 and n-1

Choice of size of Hash Table
- if n is even
	- even hash codes will result in even indices
	- odd hash codes will result in odd indices
	- This will result in non-uniform distribution if all the has codes are even or odd
- A prime number solves this issue
- Note: Hash code might return a negative integer
	- since an index cannot be negative we add n to it

### Computing Hash index for Search Key
```java
private int getHashIndex(K key){
	int hashIndex = key.hashCode() % hashTable.length
	if(hashIndex){
		hashIndex = hashIndex + hashTable.length
	}
	return hashIndex;
}
```

## [[Python]]
In python the built-in hash() function takes any hashable object and generates a numeric hash value

An object is hashable if it has a hash value which never changes during its lifetime

Hashable objects are considered equal only if they have the same hash value

Built in [[Immutable Objects]] are hashable

