## Control Statements
#### JavaScript
```js
let theNumber = Number(prompt("Pick a Number"));
if (!Number.isNaN(theNumber)){
	console.log("Your Number is the square root of " + 
     
     theNumber*theNumber)
} else {
	console.log("Why didnt you give me a number");
}

switch (prompt("What is the Weather Like")){
	case "rainy":
		console.log("Remember to bring an umbrella");
		break;
	case "sunny":
		console.log("Dress Lightly");
	case "cloudy":
		console.log("Go Outside");
		break;
	default:
		console.log("Unknown Weather Type");
		break;
}

let number = 0;
while(number <= 12){
	console.log(number);
	number = number + 2;
}

do{
	number += 2;
} while (number <= 12)

for (let i=0; i<=12; i++){
	console.log(i);
}

for(let i=0; i<listOfNumbers.length;i++){
	console.log(listOfNumbers[i]);
}

for (let e of listOfNumbers){
	console.log(e);
}

```

#### Examples
- [[SE2202-TutLab2]]