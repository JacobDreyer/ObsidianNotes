## ArrayList
#### [[Java]]
- is a generic class with a header: Class ArrayList\<E>
- Similar to an [[Arrays and Files]]
- Automatically expands and shrinks
```java
import java.util.ArrayList;

ArrayList<String> anyNameList = new ArrayList<String>(100);
ArrayList<String> anyNameList = new ArrayList<String>(100);

anyNameList.add("Stuff"); //adds data-item at the end of the array-list
anyNameList.add(1, "Stuff")//adds data at index specified
anyNameList.size(); //returns size of array
anyNameList.get(1); //gets item at location
anyNameList.remove(2); //removes item at location
anyNameList.set(1, "Stuff"); //item at 1 gets overwritten with data
anyNameList.contains("Stuff") //returns true/false if array contains 
							  //data

```
- can't be made for primitive data types
- Must use Integer, Byte, etc
- default length is 10

##### toString
- converts array list into a string
```java
System.out.println(nameList.toString());
System.out.println(nameList);

//both print: [James, Catherine, Bill]
```

#### Examples:
- [[SE2205-LabExercise2-Generics]]