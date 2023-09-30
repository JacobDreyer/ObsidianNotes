## Three dots Operator
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
