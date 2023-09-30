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

//class1.js
class SomeClass {
	constructor(e,f){}
}
module.exports = SomeClass;

//index.js
const calc = require('./calc');
const theClass = require('/class1');
console.log(calc.add(a,b));
console.log(calc.subtract(a,b));
console.log(calc.x);

let newClass = new theClass(e,f);
```