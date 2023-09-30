## The Set Interface
- extends [[The Collection Interface]]
- does not introduce new methods or constants, but it requires that an instance of Set contains no duplicate elements
- The concrete classes that implement Set must ensure no duplicate elements can be added to the set
#### The Set Interface Heirarchy:
![[Pasted image 20220929173955.png]]
- [[Hash Set]]
- [[Abstract Set]]
- [[Sorted Set]]
- [[Linked Hash Set]]
- [[Tree Set]]
- [[The Collection Interface]]

```java
public static void main(String[] arg){
	Set<String> mySet = new HashSet<String>():

	mySet.add("London");
	mySet.add("Toronto");
	mySet.add("Calgary");
	mySet.add("Halifax");
	mySet.add("Kingston");
	mySet.add("Ottawa");
	mySet.add("London");
	System.out.println(mySet);

	Iterator<String> myiterator = mySet.iterator();
	while(myiterator.hasNext()){
		System.out.print(myiterator.next() + " ");
	}

	for(String n: mySet)
		System.out.print(n + ", ");
}
```



