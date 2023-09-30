- if and if else are almost identical to that of [[Java]] or [[C++]]. In this syntax the condition is contained within () brackets with the body contained in {} blocks
```js
if (hourOfDay > 4 && hourOfDay < 12){
	greeting = "Good Morning";
} else if (hourOfDay >= 12 && hourOfDay < 18){
	greeting = "Good Afternoon"
} else {
	greeting = "Good Evening"
}

switch (artType){
	case "PT":
		output = "Painting"
		break;
	case "SC"
		output = "Sculpture"
		break;
	default
		output = "Other"
}
```
- [[JavaScript]] uses [[Type Coercion]] in Boolean contexts
- A value is said to be truthy if it evaluates to true, while a value is said to be falsy if it evaluates to false
- Almost all values in JavaScript evaluate to true
- false, null, "", ", 0, NaN, and undefined are falsy
