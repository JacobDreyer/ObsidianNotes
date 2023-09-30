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