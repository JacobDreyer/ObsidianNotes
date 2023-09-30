In addition to their set of properties most [[Objects]] also have a prototype

A prototype is another object that is used as a fallback source of properties

When an object gets a request for a property that it does not have, its prototype will be searched for the property, then the prototype's prototype and so on.

Objects have Object.prototype as their prototype(or another object to provide a different set of default values)

Functions derive from Function.prototype
Arrays derive from Array.prototype

You can use Object.create() to create an object with a specific prototype

```js
let protoRabbit = {
	speak(line){
		console.log(`The ${this.type} rabbit says '${line}' `);
	}
};

let killerRabbit = Object.create(protoRabbit);
killerRabbit.type = "killer";
killerRabbit.speak("SKREEE!");
// -> The killer rabbit says 'SKREE!'
```

JavaScript's prototype system can be interpretated as a somwhat informal take on the object-oriented concept "[[Classes]]"

#### Prototype Constructor Function
creates an object based on a prototype and initializes the values of its properties
```js
function makeRabbit(type){
	let rabbit = Object.create(protoRabbit);
	rabbit.type = type;
	return rabbit;
}
```

By convention the first letter of the Constructor is capitalised

```js
function Course(name, creditHrs, classroom, homeworkGrades){
	this.name = name;
	this.creditHrs = creditHrs;
	this.classroom = classroom;
	this.homeworkGrades = homworkGrades;

	this.evaluation = {
		homework: 20,
		tutorials: 15,
		midterm: 15,
		final: 50
	};
	this.printGrades = function(){
		console.log(this.homeworkGrades);
	}
};

let course1 = new Course("JavaScript", 3, "SEB2200", [8,7,3]);
```

any function in js has the capacity to work as a constructor function

We activate this capacity by using the new keyword when calling it.

A function object in JS has two properties that refer to prototypes
- The property name 'prototype' is the prototype the function gives to the objects it creates
- The property named "\_\_proto\_\_" is the prototype it received when it was created

