## Functions
#### JavaScript
```js
function square(x){
	return x*x;     //if we dont use return it will return undefined
}

let x = 2;
let num = square(x);

const square = function(x){
	return x*x;
}; //; is needed for this kind of function

console.log(square(12)); //outputs 144
```

#### Arrow Functions
```js
const power = (base, exponent) => {
	let result = 1;
	for(let count = 0; count<exponent; count++){
		result *= base;
	}
	return result
}

const square = x => x*x;

const horn = () =>{
	console.log("toot");
}
```
- missing parameters will be sent through as undefined
- extra parameters will be ignored

#### Functions as Values
```js
let saySomething = function(){
	console.log("Something")
}

let saySomethingAgain = saySomething;
saySomethingAgain();
```

#### [[Immediately Invoked Function Expression]]
![[Immediately Invoked Function Expression]]


#### Examples
- [[SE2202-TutLab2]]

### [[Python Function]]
![[Python Function]]