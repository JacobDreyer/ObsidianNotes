# Objects
### JavaScript
##### Custom Objects
```js
let course1 = {
	name: "Scripting Languages", 
	"credit hours" : 3, 
	classroom : "SEB2200",
	evaluation : {
		homework: 20,
		tutorials: 15,
		midterm: 15,
		final: 50
	} ,
	homeworkGrades : [5,3,10]
	printGrades: function () {
		console.log(this.homeworkGrades);
	}
};

console.log(course1.name);
//Scripting Languages
course1.name = "JavaScript";
console.log(course1.name);
//JavaScript
console.log(course1["credit hours"]);
//3
course1["credit hours"] = 2;
console.log(course1["credit hours"]);
//2

console.log(course1.evaluation.final);
//50
console.log(course1.homeworkGrades[1]);
//3
```

```js
let anObject = {left:1, right: 2};
console.log(anObject.left);
//1
delete anObject.left;
console.log(anObject.left);
//undefined
console.log("left" in anObject);
//false
console.log("right" in anObject);
//true
```

##### The Global Object
- represents the js enviroment and encapsulate built in objects, eg. the console, the definition of the array, ...etc
- in node.js its called global
```node
global.console.log("Test")
//Test
//undefined
```

- in the browser its called window
```js
window.console.log("Test")
```

- globalThis still refers to different enviroment objects
	- ex. 'prompt' is specific to the browser
	- ex. 'process' is specific to node

![[this Keyword]]
