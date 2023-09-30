## JSON - JavaScript Object Notation
- objects and arrays are stored in the computer's memory holding the addresses  of their contents
- to save data in a file or send it you have to convert the tangles of memory addresses to a description that can be stored or sent
- We can serialize the data (converted into a flat description)
- A popular serialization format is called JSON
- All property names must be surrounded by ""
- Only simple data expressions are allowed
	- no function calls
	- no bindings
	- or anything that invloves actual computation or comments
```js
let day1 = {
	squirrel: false,
	events: ["work", "touched grass", "pizza", "running"]
}
```

```json
{
	"squirrel": false,
	"events": ["work", "touched grass", "pizza", "running"]
}
```

```js
let string = JSON.stringify({squirrel: false, events: ["weekend"]});

console.log(string);
//{"squirrel" : false, "events": ["weekend"]}
console.log(JSON.parse(string).events);
//["weekend"]
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
