## JavaScript
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
}

let class1 = new ClassName(x);
class1.y = 5;
class1.func2();
class1.func1(a);

//adding properties and methods to the prototype
//they will be availible to the object if if they are added after
//its creation
ClassName.prototype.b = b;
```
