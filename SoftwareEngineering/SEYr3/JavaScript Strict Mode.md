- Activated by following as the first line:
```js
use strict;
```
- Turns "silent errors" to "throw errors"
	- Variables must be declared 
	- Any assignment that fails becomes an error
	- Cannot delete undeletable properties
	- Property names and function parameter names must be unique
	- Use 0o as octal prefix instead of 0: e.g. 0o644 instead of 0644
	- Cannot set properties on primitive types: Numbers, Strings, etc.
- Makes code easier to optimize
- Allows catching errors due to typos
```js
let theCost;
tehCost = 15;
```
- Old browser versions may not support strict mode
	- Test in browsers that support strict mode and in ones that don't
