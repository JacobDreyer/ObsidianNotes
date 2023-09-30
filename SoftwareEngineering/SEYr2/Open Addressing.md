Resolves [[Collision]]s by using another location

- [[Open Addressing]]
	- [[Linear Probing]]
		- Look at the next location(s) in the table for an open location
	- [[Quadratic Probing]]
		- functionality
			- given search key k
			- Probe at (k+1), (k+$2^2$), (k+$3^2$), $\cdots$ , (k+$n^2$)
		- Reaches Half of the locations in the [[Hash Table]] if table size is a [[prime number]]
		- Quadratic Probing avoids [[Primary Clustering]]
			- Can lead to [[Secondary Clustering]]
	- [[Double Hashing]]
		- Uses a Second [[Hash Function]]
			- Different from the first
			- Depends on the search key
			- Returns non-zero value
		- Resolves collision by examining locations
			- At Original Hash index
			- Plus an increment determined by $2^{nd}$ function which is dependent on the search key
				- 1 for [[Linear Probing]]
				- $j^2$ for [[Quadratic Probing]]
		- Reaches Every location in the hash table if table size is a prime number
		- Avoids both [[Primary Clustering]] and [[Secondary Clustering]]
		- Common Choice of [[Compression Function]]:
			- $h_2(key) = q-key\mod q$
			- where q < n
			- q is a prime number

#### Problems With Open Addressing
- A Hash Table may not have a null location
	- frequent additions and removals can cause every location in the hash table to reference either a current entry or a former entry
- Searching will not work in this case
- Increasing the size of the hash table may correct this problem if done ahead of time
- [[Seperate Chaining]] does not have this problem