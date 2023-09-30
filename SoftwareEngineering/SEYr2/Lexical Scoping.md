## Lexical Scoping
- The Lexical Scope of a binding is the extent or the range in which it can be seen
- Scopes can be nested
	- The outer scope can be overshadowed by bindings of the same name in the Inner scope

#### Scopes:
- [[Global Scope]]
	- Accessible from anywhere
	- Whatever belongs to the [[globalThis Object]]
- [[Local Scope]]
	- created by:
		- a function definition
		- A [[Module]] in [[Node.js]] or a [[Script]] in the browser
- [[Closure Scope]]
	- Created by inner functions(functions in functions)
	- Allows scope of outer function to be availible in the inner function
- [[Block Scope]]
	- Bindings created by let or const inside a block delimited by curly brackets or the round brackets of a for loop

