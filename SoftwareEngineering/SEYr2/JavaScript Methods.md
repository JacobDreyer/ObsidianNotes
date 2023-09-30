## Methods
### JavaScript
- properties that hold [[Functions]] values
```js
let person = {
	name: "alice",
	saySomething: function(line){
		console.log(line);
	}
};
person.saySomething("Good Morning"); //Good Morning
```

```js
let saySomething = function(line){
	console.log(this.name + " says: " + line);
}

let person = {
	name: "alice",
	saySomething
};
person.saySomething("Good Morning"); //Good Morning
```