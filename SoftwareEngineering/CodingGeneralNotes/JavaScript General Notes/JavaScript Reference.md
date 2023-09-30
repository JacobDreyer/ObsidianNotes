### [[JavaScript Data Types]]
```js
//binding names can contain $ and _ but nothing else
let x = 5; //number
var x = "5"; //string //var does not recogize block scope
const x = true; //boolean //const is a varible that cant be changed

typeOf x;
x.toPrecision(3); //5 -> 5.00

//Type Conversion
String(x);
Number(x);
Boolean(x);

//private members

//JS is still object based so its better to follow convention and surround
//variables meant to be private with double underscores

//closures

let functionName = function(x){
    let xInFunction = x;              //xInFunction is private
    let getXInFunction = function(){
        return xInFunction;
    }
    return getXInFunction;
};
let functionRepresentingX = functionName(5);
console.log(functionRepresentingX()); //prints 5

//class
class ClassName{
    constructor(x){
        let xInClass = x;                //xInClass is only availible in
        this.funcGetVarX = function(){   //the constructor. so its private
            return xInClass;
        }
    }
}
let theClass = new ClassName(5);
console.log(theClass.funcGetVarX());

//# syntax
class ClassWithPrivateFields {
    #x;
    constructor(x){
        this.#x = x;
    }
    get getX(){
        return this.#x;
    }
    printDoubleX(){
        console.log(this.#calculateDouble());
    }
    #calculateDouble(){
        return this.#x*2;
    }
}  
let theClass = new ClassWithPrivateFields(5);
console.log(theClass.getX);
theClass.printDoubleX();
```

### [[Control Statements]]
```js
//if statements
if(true){
	//execute
}
/*************************/
if(true){
	//execute if true
} else if(true){
	//execute if passed first statement and true
} else {
	//execute if pass all previous statements
}
/**************************/
switch (variable){
	case 1:
		//execute if case matches variable
		break; //so that it doesnt execute following statements/cases
	case 2:
		//execute if case matches variable
		//no break means following cases will be executed
	case "string":
		//execute if case matches variable or previous case matches
		//variable because there is no break statement in previous 
        //case
		break;
	default:
		//execute if no case matches
		break;
}
/*********** Loops ****************/
for(let i=start; i<end; i+=plus){
	//runs cap-start times
	//starts at start. ends at end. increases by plus
}
/*********************************/
for(let listVal of List){
	//iterates over length of List
	//listVal becomes value of List at each "slot" in List
}

for(let index in List){
	console.log(index); //if List has 4 elements: 0 1 2 3
}
/*********************************/
while(true){
	//execute code while statement is true
}
/*********************************/
do{
	//execute code once before checking while statement is true
} while(true)

//Logical Operations
if(x>y) 
if(x<y)
if(x>=y) //x greater than or equal
if(x<=y)
if(x==y) //x equals y
if(x!=y) //x does not equal y
if(a && b) //a and b are true
if(a || b) //a or b are true
if(!a) //if a isnt true
```

### [[Functions]] and [[JavaScript Methods]]
```js
function func(arg){
	//accepts argument and sets it to arg
	//execute code
	return variable; //returns value of variable
}
/*********************************/
const func = function(...args){
	//execute code
	//... accepts any number of arguments and assigns them to list args
	//must be last argument
	//no return statement means undefined is returned
}; 
/*********************************/
const func = (arg1, arg2) => {
	//execute code
	//missing parameters are sent through as undefined(valid for all func)
	//extra parameters ignored(valid for all func)
};
/*********************************/
const func = arg => variable=arg;

/************* Methods ***************/
let meth = function(arg){
	//execute code
}
//Immediately Invoked Function Expressions

( // first () hides function from outer scope
	function doStuff(a,b){};
)(a,b); //second () executes function so its immediately invoked
```

### [[Objects]]
```js
let obj = {
	var1: "name",
	"var 2": 3,
	subobj: {
		var3: 4,
		"var4": "other name"
	},
	var5: 5
	func: function(){
		//execute
	}
}

let obj2 = {
	name : "alice",
	saySomething
};

function saySomething(line){
	console.log(this.name + " " + line) //alice
	//this. only works on non arrow notation functions
}

obj.saySomething(line)
saySomething.call(obj2, line);

obj.var1;
obj.["var1"];
obj["var 2"];
obj.subobj.var3;

delete obj.var1;
("var1" in obj); //false
("var5" in obj); //true

//Prototypes

Object.getPrototypeOf(obj); //returns prototype of object
let obj = Object.create(proto); //creates an object based on a prototype

//Constructor Function
function Course(x,y,z){
	this.x = x;
	this.y = y;
	this.z = z;

	this.func = function(){
	}

	this.subObj = {};
}

let course1 = new Course(x,y,z);
```

### [[Class]] Notation
```js
class ClassName {
	constructor(x){     //these are added to the object
		this.x = x;
		this.y = 0;
		this.z = "default";
		this.func2 = function(){
			y = 5;
		}
	}
	                     //only functions are allowed
	func(a){             //this will be added to the prototype
		console.log(a);
	}

	anotherFunc(b){             //this will be added to the prototype
		console.log(b);
	}

	get varX(){
		return this.x;
	}

	set varX(value){
		this.x = value;
	}

	static statFunc(value){ //stored as a property of constructor class
		return new ClassName(value - this.x * 2); 
	}
}

let class1 = new ClassName(x);
class1.y = 5;
class1.func2();
class1.func1(a);

console.log(class1.varX);
class1.varX = 10;
ClassName.statFunc(20);

//adding properties and methods to the prototype
//they will be availible to the object if if they are added after
//its creation
ClassName.prototype.b = b;

//Inheritance
class InheritedClass extends ClassName {
	constructor(k){ //if we override default constructor we must
		super(k-3);   //call super
		this.k = k;
	}

	anExtraFunction(i){
		console.log(i + this.x);
	}

	anotherFunc(j){
		super(5);            //call parent anotherFunc()
		                     //arrow functions have no super
		console.log(j + 2);
		this.anExtraFunction(6);
	}
}

let inhertiedClassVar = new InheritedClass(k);
inheritedClassVar.func(a);
inheritedClassVar.anotherFunc(j);
console.log(inheritedClassVar.anExtraFunction(i);)
```

### [[String Methods]]
```js
"string".slice(2,5);
"string".indexOf("str");
"string".repeat(3);
"    string    ".trim();
let words = "string and string".spilt(" "); //returns array of segemnts
words.join("-");

`100 divided by 2 is ${100/2}`  //inside the curly brackets is evaluated

x.charAt(0);
x.toLowerCase();
x.toUpperCase();

//Regex
/^[a-zA-Z]+$/.test(str);  //testing strings
//^ - Assert position at start of string
//[a-zA-Z] - Match a single character present in the list below
//+ between one and unlimited times, as many as possible
//a-z a character in range of a-z
//A-Z a character in range of A-Z
//$ assert position at the end of the string

```

### [[Arrays]]
```js
let list = [1,2,3,4,5];
list[2];

//functions
list.push(6);
list.pop();

//array operations
let arrayName = [1,2,3,4];

arrayName.forEach(element => {console.log(element); element+=5; 
 console.log(element)}) //arrayName is still [1,2,3,4] we only change
                        //element

filteredArr = arrayName.filter(test); //test is a function. if test 
                              //returns true for a element in the array; 
                              //it is added to an array which is returned
							  //test must accept a value(the val to test)

transformedArr = arrayName.map(transform); //transform changes each 
                 //element which is then added to array which is returned

reducedArr = arrayName.reduce(reduceTo); //reduces array to one element
									//functionality dictated by reduceTo()
reducedArr = arrayName.reduce(reduceTo, startPoint); //can set start point
```

### [[File Reading and Writing]]
```js
let fs = require('fs');
fs.writeFile('filePath.txt', message, ()=>{}); //calls the function after 
                       //finishes. will create the file if it isnt already

//importing JSON
let name = require('./fileName.json');
console.log(name.otherName);
```

### [[Modules]]
```js
//calc.js
function add(a,b){
	return a+b;
}
function subtract(c,d){return c-d;}
let x=5;
module.exports.add = add;
module.exports.subtract = subtract;
module.exports.x = x;
```

```js
//class1.js
class SomeClass {
	constructor(e,f){}
}
module.exports = SomeClass;
```

```js
//index.js
const calc = require('./calc');
const theClass = require('/class1');
console.log(calc.add(a,b));
console.log(calc.subtract(a,b));
console.log(calc.x);

let newClass = new theClass(e,f);
```

### [[JSON]]
```js
JSON.stringify(str); //formats str with "" and / etc.
JSON.parse(str);     //brings str back to normal object form
```

```json
//in a json file there can be an array of json objects:
[
	{
		"stuff" : "stuff"
	}
,
	{
		"more stuff":"more stuff"	
	}
]
```

### [[DOM]]
```html
<u1>
	<li id="one" class="two">Three</li>
	<li id="four" class="five">Six</li>
	<li id="four" class="two">Seven <em>Eight</em> Nine</li>
</u1>
```

```js
/***************Queries***************/
var a = document.getElementById("one");
document.getElementsByClassName("two"); //if there is multiple it returns 
                                        //as list
document.getElementsByTagName("li");

document.querySelector('#one');
document.querySelector('.hot');
document.querySelector('li');
document.querySelectorAll('li.hot')
/**************Traversing*************/
variable.parentNode;
variable.previousElementSibling;
variable.nextElementSibling;
superVar.firstElementChild;
superVar.lastElementChild;
/*************Accessing**************/
document.getElementById("one").textContent;
document.getElementById("four").innerHTML;

createElement();
createTextNode();
appendChild();
/***************DOM Events***********/
element.onblur = func;

element.addEventListener("click", func1);
element.addEventListener("click", function(){func2(5);});

function func1(e){
	e.target; //element that received event
	e.type;   //type of the element
}

function func2(x){
}
```

Event Listener in HTML (DO NOT USE)
```html
<input type="text" id="username" onblur="checkUsername()">
```

##### Types of Events:
- User Interface Events
	- load
	- unload
	- error
	- resize
	- scroll
- Keyboard Events
	- keydown
	- keyup
	- keypress
- Mouse Events
	- click
	- dblclick
	- mousedown
	- mouseup
	- mouseover
	- mouseout
- Focus Events
	- focus / focusin
	- blur / focusout
- Form Events
	- input
	- change
	- submit
	- reset
	- cut
	- copy
	- paste
	- select

### [[Node Package Manager]]
```node
//to initialize:
//with defaults:
npm init --yes
//custom:
npm init

//to install:
npm install packagename

//to uninstall:
npm uninstall packagename
```

### [[Asynchronous Program]]
```js
setTimeout(()=>console.log("stuff after time"), 1500);

//promises
let somePromise = new Promise(function(resolve, reject){
	//perform some asynchronous operation then:
	//resolve(value) if the operation succeeded, or
		//resolve basically calls the "then" function
	//reject(error) if the operation failed
});

somePromise.then(function(value){
	//handle successfull operation
	//called when asynchronous operation finishes
}).catch(function(error){
	//handle failed operation
})
```

### [[Catching Errors]]
```js
try{
	//stuff
} catch(e) {
	//other stuff if theres an error
}
```
