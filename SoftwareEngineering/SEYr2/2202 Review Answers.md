## Following are from Review 1

#### Question 1
Sort the following steps:
1.  The server sends the response to the client
2.  The client displays the content to the user
3.  The client receives the requested URL from the user.
4.  The client receives the HTTP Response from the server
5.  The server creates the HTTP response containing the requested resource
6.  The server receives the HTTP request from the client
7.  The client sends the request to the server
8.  The server finds the requested resource
9.  The client creates the HTTP request

3, 9, 7, 6, 8, 5, 1, 4, 2

#### Question 2
Sort the following lines in order to create a proper structure for the HTML document

A. \</html>
B. \<title>This is the Title of...\</title>
C. \<body>
D. \</body>
E. \<p>This is a paragraph\</p>
F. \<head>
G. \<h1>This is a header\</h1>
H. \</head>
I. \<html>

I, F, B, H, C, G, E, D, A

#### Question 3
The focus of this course is on:
- [ ] All the options
- [x] The fundamentals of JS language
- [ ] Developing Web Applications using JS
- [ ] How to use JS Frameworks

#### Question 4
In order to change the HTML content of a page from the browser, you need to right-click on the page and click on "View page source" then update the HTML code in the source page that will appear.
- [ ] True
- [x] False

#### Question 5
Which of the following is an empty element? (choose all correct answers)
- [ ] button
- [ ] a
- [x] br
- [x] img
- [x] input

#### Question 6
Fill in the missing words to refer to an external CSS file in an HTML page  
<  ==link== href="css/styles.css" type="text/css" rel="==stylesheet==">

#### Question 7
Based on the HTML code of the login page shown below, match the name-value pairs that will be sent to the server after the user submits the form.
![[Pasted image 20221025111724.png]]
A. Not a valid name
B. john@gmail.com
C. value not shown

1. Password $\to$ A (Not a valid name)
2. pwd $\to$ C (value not shown)
3. eaddress $\to$ B (john@gmail.com)

## Following are from Review 2

#### Question 1
What is the mistake in this image?
![[Pasted image 20221025112309.png]]
$\to$ Alert

#### Question 2
In the shown image, the alert message is displayed because:
![[Pasted image 20221025112425.png]]
- [ ] The user clicked on a button with the onclick value calling the alert function
- [ ] There was a script element in the page that calls the alert function in its content
- [ ] There was a js file with the alert function call linked to the page
- [x] None of the Above

#### Question 3
Choose All that apply to Node.js
- [x] A command line tool to execute JS
- [x] Allow Executing JS statements through REPL
- [ ] REPL allows executing JS statements like "alert(hello world!)"
- [x] REPL allows executing commands like ".help"

#### Question 4
Why is the line in the image highlighted? (type one keyword)
![[Pasted image 20221025112952.png]]
$\to$ breakpoint

#### Question 5
Choose all that apply to the JIT Compilation:
- [ ] Stands for Javascript International Translation
- [x] Run time Compilation
- [x] Enhances the performance of execution
- [ ] Turns JS into a completely compiled language (no iterpretation at all)

#### Question 6
Match the following values with their corresponding JS data type

A. float
B. number
C. string

1. 3.5 $\to$ B (number)
2. "4.5" $\to$ C (string)
3. Not a valid JS type $\to$ A (float)

#### Question 7
What is the value of the expression !(null + 9) || (true - 6)
$\to$ $-5$

#### Question 8
Choose all valid binding/variable-declaration statements in JS
- [x] let x;
- [x] var x;
- [ ] int x;
- [x] let x=5, y=6;
- [ ] int x=5, y=6;

#### Question 9
Choose all that's equivalent to the statement 
```js
let square = y => y * y ;
```
- [ ] let square = (y) => {y * y;};
- [x] let square = (y) => {return y * y;};
- [x] let square = function (y) { return y * y;};
- [x] function square(y) {return y * y;}

#### Question 10
The code shown in the image below is an example of a ==callback== function. (Hint: the concept)
```js
let sayHi = function(name){
	console.log("Hi, "+name);
};
let sayBye = function(name){
	console.log("Bye, "+name);
};
let talk = function(sayWhat, toWho){
	sayWhat(toWho);
}
talk(sayHi, "John");
talk(sayBye, "Tom");
```

## Following are from Review 3

#### Question 1
Based on the image below, what is the result of calling 
max(10, 20, ...numbers, 3, 15)?
$\to$ 20
```js
function max(...numbers){
	let result = -Infinity;
	for(let number of numbers){
		if (number>result) 
			result = number;
	}
	return result
}

let numbers = [5,1,7];
console.log(max(...numbers)); // -> 7
console.log(max(4,1,9,-2)); // -> 9
```

#### Question 2
"scripting languages fundamentals".slice( ==10== ,  ==19== ) will return the value "languages"

#### Question 3
JASON.==stringify== transforms a JS object to a string, while JASON.==parse== transforms a string into a JS object

#### Question 4
In JS the square brackets can be used to access a(n) ==property== of an object as well as a(n) ==element== of an array.

## Following is from Review 4

#### Question 1
A function that references bindings from the local scopes around it (the enclosing scope) is called a ==closure==

#### Question 2
```js
let raiseToPower = function(power){
	let powerOf = function(value){
		let result = 1;
		for(let i=0; i<power; i++){
			result = result * value;
		}
		return result
	}
	return /*????*/
}

let powerOfTwo = raiseToPower(2);
console.log(powerOfTwo(5));
```
Considering the code in the image, what needs to be written in place of the question mark in line 12 to get the code to work properly?
- [ ] result;
- [ ] powerOf();
- [x] powerOf;
- [ ] raiseToPower();
- [ ] raiseToPower;

#### Question 3
```js
let raiseToPower = function(power){
	let powerOf = function(value){
		let result = 1;
		for(let i=0; i<power; i++){
			result = result * value;
		}
		return result
	}
	return ????
}

let powerOfTwo = raiseToPower(2);
console.log(powerOfTwo(5));
```
Considering the code in the image, what would be the output.
- [ ] 10
- [ ] 5
- [x] 25
- [ ] undefined

#### Question 4
```js
let raiseToPower = function(power){
	let powerOf = function(value){
		let result = 1;
		for(let i=0; i<power; i++){    //line 6
			result = result * value;
		}
		return result
	}
	return ????
}

let powerOfTwo = raiseToPower(2);
console.log(powerOfTwo(5));
```
Considering the code in the figure, the variable power in line 6 is accessible through:
- [x] The Closure scope
- [ ] The local scope
- [ ] The global scope
- [ ] None of the above

#### Question 5
Match the JS scope and its description

A. Created by a module or a function
B. Created by inner functions (functions defined inside other functions)
C. Accessible from anywhere

1. Global Scope $\to$ C
2. Local Scope $\to$ A
3. Closure Scope $\to$ B

#### Question 6
The block scope is not applicable to variables defined using the keyword  ==var==

## Following is from Review 5

#### Question 1
Complete the missing parts of the code below: (a) ==createElement== , (b) ==myDiv== ,       (c) ==appendChild==
![[Pasted image 20221025121154.png]]

#### Question 2
The 'e' binding in the code below represents the ==event object== (two words)
```js
function checkUsername(e){
	var target = e.target
}

var e1 = document.getElementById('username');
e1.addEventListener('blur', checkUsername, false);
```

#### Question 3
Searching and locating HTML elements in the DOM is called
- [ ] DOM selections
- [x] DOM queries
- [ ] DOM Locating
- [ ] DOM searching

#### Question 4
Match the following prefix with its indication when used with the querySelector method

A. Search by the id
B. Search by class name
C. Search by tag name

1. dot(.) $\to$ B
2. # $\to$ A 
3. No Prefix $\to$ C

#### Question 5
When linking an event to a function using the event attribute, the value of the attribute should be set to a function ==call== , while when using the event property or the event listener, we link the event to a function ==definition==

## Following is from Review Questions 6
#### Question 1
When we use the class notation we are actually creating a ==constructor== function.

#### Question 2
Deleting a method that was defined in the class notation outside the constructor function affects all objects created based on that class because the method belonged to the  ==prototype==

#### Question 3
Defining a method using the 'static' keyword adds the method as a property of the  ==constructor function== (two words)

#### Question 4
When we defined the Rabbit class to extend the Animal class the property  ==\_\_proto\_\_== of the object Rabbit. ==prototype== will refer to Animal. ==prototype== . (Hint: type the names of the properties)

#### Question 5
Overridden methods can be accessed using the keyword ==super==

#### Question 6
==behaviour parameterization== is when we send a function definition to another function so that different behavior would be executed depending on the given function definition.

#### Question 7
Match the data processing function and its description

A. Applying some aggregation over the elements
B. Selecting elements that meet a certain condition
C. Applying some processing on each element

1. Filter $\to$ B
2. Map $\to$ C 
3. Reduce/Fold $\to$ A

#### Question 8
When calling the built-in reduce function, if we don't send a starting point, it's assumed to be the ==first== element.

## Following is From Review Questions 7
#### Question 1
![[Pasted image 20221125112622.png]]
The output of the code displayed in the image is ==NaN==

#### Question 2
The definitions of 'module' and 'require' are part of the ==CommonJS== framework.

#### Question 3
==fs== is a ==built-in== Node.js module that allows us to access the file system.

#### Question 4
NPM stands for ==Node Package Manager==

#### Question 5
Which of the following is NOT true about importing json files
- [ ] The file has the extension '.json'
- [ ] The file extension can be omitted when we send it to the 'require' function
- [x] We need to parse the imported object before we can use it as a plain JS object
- [ ] The json file can contain multiple objects

## Following is from First Kahoot

#### Question 1
What is the result of the expression: null / 10 
- [ ] NaN
- [ ] 10
- [x] 0
- [ ] null

#### Question 2
What is the result of the expression: undefined / 10
- [x] NaN
- [ ] undefined
- [ ] 10
- [ ] 0

#### Question 3
What is the result of the expression: "5" + 2
- [ ] NaN
- [ ] Error
- [x] 52
- [ ] 7

#### Question 4
What is the result of the expression: "5" - 2
- [x] 3
- [ ] 52
- [ ] Error
- [ ] NaN

#### Question 5
What is the result of the expression: "five" - 2
- [ ] 3
- [x] NaN
- [ ] Error
- [ ] 52

#### Question 6
What is the result of the expression: (5 - 5) || (5 + 5)
- [x] 10
- [ ] false
- [ ] true
- [ ] 0

#### Question 7
What is the result of the expression: (5 + 5) || ( 5 - 5)
- [x] 10
- [ ] false
- [ ] true
- [ ] 0

#### Question 8
What is the result of the expression: (5 + 5) && (5 - 5)
- [ ] true
- [ ] 10
- [x] 0
- [ ] false

#### Question 9
What is the result of the expression: (5 - 5) && ( 5 + 5)
- [x] 0
- [ ] 10
- [ ] false
- [ ] true

## Following is from Second Kahoot

#### Question 1
Numeric values in JavaScript are considered of primitive data type
- [ ] True
- [x] False

#### Question 2
JavaScript is an Object-==based== Language

#### Question 3
What is the output of console.log("Hello".slice(2,4))
- [x] ll
- [ ] ell
- [ ] ello
- [ ] llo

#### Question 4
What s the result of: console.log ([3, ['a', 'b', 'c'],5])
- [ ] 3 ['a', 'b', 'c'] 5
- [x] [3, ['a', 'b', 'c'], 5]
- [ ] 3, 'a', 'b', 'c', 5
- [ ] [3, 'a', 'b', 'c', 5]

#### Question 5
What s the result of: console.log ([3, ...['a', 'b', 'c'],5])
- [ ] 3 ['a', 'b', 'c'] 5
- [ ] [3, ['a', 'b', 'c'], 5]
- [ ] 3, 'a', 'b', 'c', 5
- [x] [3, 'a', 'b', 'c', 5]

#### Question 6
Which of the following is a proper JSON format
- [ ] '{x : 5, y : 8, distance: calcDistance()}'
- [ ] '{x : "5", y : "8", distance: "calcDistance()"}'
- [ ] '{"x" : 5, "y" : 8, "distance": calcDistance()}'
- [x] '{"x" : "5", "y" : "8", "distance": "calcDistance()"}'

#### Question 7
In JavaScript the variable referred to by the keyword 'this' belongs to:
- [ ] an object
- [ ] a class
- [x] a function
- [ ] the global object

#### Question 8
In JavaScript the global object in Nodejs is referred to by:
- [x] global
- [x] globalThis
- [ ] window
- [ ] globalObject

#### Question 9
In JavaScript the global object in the browser is referred to by:
- [ ] global
- [x] window
- [x] globalThis
- [ ] globalObject

## Following is from Third Kahoot

#### Question 1
Which of the following JS Scopes is created by a function or a module
- [ ] Global Scope
- [x] Local Scope
- [ ] Closure Scope
- [ ] Block Scope

#### Question 2
Which of the following JS Scopes is seen from inside an inner functions
- [ ] Global Scope
- [ ] Local Scope
- [x] Closure Scope
- [ ] Block Scope

#### Question 3
Which of the following JS Scopes allows access to the properties of the global object
- [x] Global Scope
- [ ] Local Scope
- [ ] Closure Scope
- [ ] Block Scope

#### Question 4
Which of the following JS Scopes does not apply to variables defined using **var** but applies to those defined with **let**
- [ ] Global Scope
- [ ] Local Scope
- [ ] Closure Scope
- [x] Block Scope

#### Question 5
Which of the following JS Scopes is accessible everywhere
- [x] Global Scope
- [ ] Local Scope
- [ ] Closure Scope
- [ ] Block Scope

#### Question 6
The variables read in line 26 (**the highlighted**) line are accessible through which scope?
```js
let print = function(a){
	let b = a + 10;
	var c = 30;
	console.log("x=" + x);
	console.log("y=" + y);
	console.log("z=" + z);
	console.log("a=" + a + "b=" + b + "c=" + c);

	let innerFunction = function(k){
		let m = 80;
		var n = 70;

		console.log("a=" + a + "b=" + b + "c=" + c); //line 25
		console.log("k=" + k + "m=" + m + "n=" + n);
	}

	innerFunction(50);
}
print(5);
```
- [ ] Global Scope
- [x] Local Scope
- [ ] Closure Scope
- [ ] Block Scope

#### Question 7
The variables read in line 25 (**the line above the highlighted)** line are accessible through which scope?
```js
let print = function(a){
	let b = a + 10;
	var c = 30;
	console.log("x=" + x);
	console.log("y=" + y);
	console.log("z=" + z);
	console.log("a=" + a + "b=" + b + "c=" + c);

	let innerFunction = function(k){
		let m = 80;
		var n = 70;

		console.log("a=" + a + "b=" + b + "c=" + c); //line 25
		console.log("k=" + k + "m=" + m + "n=" + n);
	}

	innerFunction(50);
}
print(5);
```
- [ ] Global Scope
- [ ] Local Scope
- [x] Closure Scope
- [ ] Block Scope

#### Question 8
The combination of an inner function and its surrounding context is called a ==closure==

#### Question 9
What is the value of '**factor**' when the calls in lines 38 and 39 are executed
```js
let multiplier = function(factor){
	let innerMultiplier = function(value){
		return factor * value;
	}
	return innerMultiplier;
}

let twice = multiplier(2);
console.log(twice(5));      //line 38
console.log(twice(10));     //line 39
let tenTimes = multiplier(10);
console.log(tenTimes(5));
console.log(tenTimes(10));
```
- [ ] 5
- [ ] 10
- [ ] factor is not accessible
- [x] 2

#### Question 10
What is the value of '**factor**' when the calls in lines 41 and 42 are executed
```js
let multiplier = function(factor){
	let innerMultiplier = function(value){
		return factor * value;
	}
	return innerMultiplier;
}

let twice = multiplier(2);
console.log(twice(5));      //line 38
console.log(twice(10));     //line 39
let tenTimes = multiplier(10);
console.log(tenTimes(5));   //line 41
console.log(tenTimes(10));  //line 42
```
- [ ] 5
- [x] 10
- [ ] factor is not accessible
- [ ] 2

## Following is from 4th Kahoot
#### Question 1
Behaviour Parameterization can be done in JavaScript using ==callback== functions.

#### Question 2
Which of the following Array operations can be used to change the values in the original array?
- [x] foEach
- [ ] filter
- [ ] map
- [ ] reduce

#### Question 3
Which of the following Array operations select some elements from the array based on a given predicate?
- [ ] foEach
- [x] filter
- [ ] map
- [ ] reduce

#### Question 4
Which of the following Array operations applies a transformation function on each element of an array?
- [ ] foEach
- [ ] filter
- [x] map
- [ ] reduce

#### Question 5
Which of the following Array operations may optionally take another argument besides the callback function?
- [ ] frEach
- [ ] filter
- [ ] map
- [x] reduce

## Following is from 5th Kahoot
#### Question 1
In JavaScript a Module is a \_\_\_\_\_
- [x] File
- [ ] Group of related Files

#### Question 2
What is the result (log print) of the following script?
- [ ] undefined
- [x] 3
- [ ] 5
- [ ] NaN

#### Question 3
\_\_\_\_\_ is used to expose objects of a given module to allow using them in another module.
- [ ] require
- [ ] expose
- [x] module.exports
- [ ] reveal

#### Question 4
\_\_\_\_\_ is used to import a module into a script
- [x] require
- [ ] expose
- [ ] module.exports
- [ ] reveal

#### Question 5
The JS built-in module that's used to access the file system is called \_\_\_\_
- [ ] FileSystem
- [ ] file_system
- [x] fs
- [ ] f_s

#### Question 6
When importing a JSON file using require(), we need to call JSON.parse to be able to access its objects.
- [ ] True
- [x] False

#### Question 7
When writing a JSON file using fs.writeFile, we need to call JSON.stringify to be able to write it in the correct format
- [x] True
- [ ] False

## Following is Practice from 2020 Midterm

#### Question 1
In web applications, the ==server== is responsible for receiving requests from and sending responses to the ==client==

#### Question 2
==ECMAScript== is a standard that describes the way the JavaScript language should work so that the various pieces of software that claimed to support JavaScript were actually talking about the same language

#### Question 3
Match the technology/tool with its usage in web applications

A. Create Presentation/Layout 
B. Create Structure 
C. Create Behaviour

1. HTML $\to$ B
2. CSS $\to$ A
3. JavaScript $\to$ C

#### Question 4
```html
<a ???="http://www.imdb.com">IMDB</a>
```
What is missing in the picture is an ==attribute== name and it should be ==href==

#### Question 5
Choose all the possible ways to run JavaScript code from an HTML page
- [x] Writing the code within the content of a 'script' element
- [x] Writing the code in a separate file and set the 'src' attribute of the 'script' tag to refer to that file.
- [ ] Writing the code in a separate file and set the 'src' attribute of the opening 'link' tag to refer to that file.
- [x] Write the code as the value of an event attribute

#### Question 6
In JavaScript, every line MUST end with a semicolon.
- [ ] true
- [x] false

#### Question 7
The expression !(false + 9) || (null - 6) evaluates to
$\to$ -6

#### Question 8
GUI based functions like 'alert' cannot be called if you run the script in Node.js.
- [x] true
- [ ] false

#### Question 9
==REPL== feature in Node.js allows you to type JavaScript statements directly in the command line.

#### Question 10
Choose all that applies on JS functions
- [x] They can be assigned and reassigned to different binding names
- [x] They can be sent as arguments to other functions
- [x] They can return from another function
- [x] They are objects

#### Question 11
A function that references bindings from the local scopes around it (the enclosing scope) is called a ==closure==.

#### Question 12
```js
let sayHi = function(name){
	console.log("Hi, "+name);
};
let sayBye = function(name){
	console.log("Bye, "+name);
};
let talk = function(sayWhat, toWho){
	sayWhat(toWho);
};
talk(sayHi, "John");
talk(sayBye, "Tom");
```

Which of the functions in the previous code snippet is a callback function? ==sayWhat==

#### Question 13
```js
let d = function(b){
	return v => v/b;
}

let t = d(3);
console.log(t(60)); //line 7
```
The output of line 7 is ==20==

#### Question 14
JavaScript is an Object-==based== language as opposed to Java which is an Object-==Oriented== language.

#### Question 15
If an object's property holds a function definition as a value it would be called a ==method==

#### Question 16
Match the code snippet with its description
A. 
```js
let day1 = {
	squirrel: false,
	events: ["work", "touched tree", "pizza", "running"]
};
```
B.
```js
{
	"squirrel": false,
	"events": ["work", "touched tree", "pizza", "running"]
}
```

1. JavaScript Object $\to$ A
2. JASON Object $\to$ B

#### Question 17
DOM stands for ==Document Object Model== and it organizes HTML element in a ==tree== data structure.

#### Question 18
```js
function c (...e){
	return e;
}

let b = c(5,7,8,0);
console.log(...b);  //line 7
```
The output of line 7 in the previous code snippet is ==5 7 8 0==

#### Question 19
DOM queries are methods of the ==document== object that allow us to select element nodes

#### Question 20
==proto== is a property that belongs to an object and it holds the prototype it received when it was created. While ==prototype== is a property that belongs to the constructor function and it holds the prototype that the function gives to the objects it creates.

#### Question 21
Objects created using the constructor function don't have to keep the properties it received from the constructor function, we can add or delete any property of these objects.
- [x] true
- [ ] false

#### Question 22
In JavaScript the 'this' keyword belongs to the ==function== while in Java it belongs to the ==object==

#### Question 23
```js
let saySomething = function(line){
	console.log(this.name + " says: "+ line);
	let innerSay = function(){
		console.log(this.name + " says (from innerSay): " + line);
	}
	innerSay();
};

let person = {
	name: "Alice",
	saySomething
};

person.saySomething("Good Morning");
```

In the code snippet above the properties referred to by arrows 1 and 2 (this.name) are exactly the same and they hold the value "Alice"
- [ ] true
- [x] false

#### Question 24
Order the steps needed to allow DOM events to trigger JS code

A. Indicate the event on the selected node(s) that will trigger a response
B. Select the element node(s) the script should respond to
C. State the code you want to run when the event occurs

1. Step 1 $\to$ B
2. Step 2 $\to$ A
3. Step 3 $\to$ C

#### Question 25
If 'el' is the name of the object representing the HTML element, choose all correct code ways that allow us to trigger a JS function named 'checkUsername' in response to the 'blur' event over 'el'
- [x] el.onblur = checkUsername;
- [ ] el.onblur = checkUsername();
- [x] el.addEventListener(‘blur’, checkUsername);
- [ ] el.addEventListener(‘blur’, checkUsername());