### Functionalities
- get(k): if map M has an entry with key k, return its associated value; else, return null
- put(k, v): insert entry (k, v) into the map M; if key k is not already in M, then return null; else return old value associated with k
- remove(k): if the map M has an entry with key k, remove it from M and return its associated value; else, return null
- size(), isEmpty() - same as other ADT's we discussed
- entrySet(): return an iterable collection of the entries in M
- keySet(): return an iterable collection of keys in M
- values(): return an iterator of the values in M
![[Pasted image 20221018105429.png]]

- The Map Interface
	- Search Key : Entry
	- The search key is integers

#### The map UML Diagram
![[Pasted image 20221018105614.png]]

##### Map.Entry
![[Pasted image 20221018105636.png]]

##### UML Structure
![[Pasted image 20221018105753.png]]

#### Implementations

![[Hash Map]]

![[Tree Map]]