## JavaScript
```js
let listOfNumbers = [2,3,5,7,11];
console.log(listOfNumbers[2]);
// 5
```
##### Array Methods
```js
let sequence = [1,2,3];
sequence.push(4);
sequence.push(5);
console.log(sequence);
//[1,2,3,4,5]
console.log(sequence.pop());
//5
console.log(sequence);
//[1,2,3,4]
```
##### Looping over Array Elements
```js
for(let i=0; i<listOfNumbers.length;i++){
	console.log(listOfNumbers[i]);
}

for (let e of listOfNumbers){
	console.log(e);
}
```

##### [[Three dots Operator]]
- collects any number of arguments sent to a function
- Must be last parameter in the list
```js
function max(...numbers){
	let result = -Infinity;
	for(let number of numbers){
		if(number > result)
			result = number;
	}
	return result;
}

console.log(max(4,1,9,-2));
// 9
```
- when used with an array it spreads out the elements
```js
let words = ["never", "fully"];
console.log(["will", ...words, "understand"]);
//["will", "never", "fully", "understand"]

let numbers = [5, 1, 7];
console.log(max(...numbers));
//7   // is = to
console.log(max(5,1,7));
```

##### String-to-Array and Array-to-String
```js
let sentence = "Secratarybirds specialize in stomping";
let words = sentence.split(" ");
console.log(words);
//["Secratarybirds", "specialize", "in", "stomping"]
console.log(words.join(". "));
//Secratarybirds. specialize. in. stomping
```

##### [[Array Operations]]
![[Array Operations]]

## Java
```java
String[] cars = {"Volvo", "BMW", "Ford", "Mazda"};

int[] anArray = new int[10];
```
##### Array Functions
```java
int[] array = {10,1,21,3,4};
Arrays.fill(array,2,4,50); //fill array[2] to [4] with 50
Arrays.sort(array); //sorts array
Arrays.binarySearch(array, 30); //search for 30 in array

int[] a = new int[5];
Arrays.equals(array, a); //test if 2 arrays are the same
```


#### Examples
- [[SE2205-LabExercise2-Generics]]