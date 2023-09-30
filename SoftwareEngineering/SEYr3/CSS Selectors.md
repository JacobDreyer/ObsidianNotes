- A selector is a list of tag names
- For each selector, some properties are assigned values:
	- b {color: red; font-size: 12pt}
	- i {color: green}
- Longer selectors give context sensitivity
	- table b {color: blue; font-size: 12pt}
	- form b {color: yellow; font-size: 12pt}
	- i {color: green}
- The most specific selector is chose to apply
```html
<E>
	<X>
		<F>Hi</F>
	</X>
</E>
```
- E F matches any F element that is a descendant of E element
- E > F matches any F element that is a child element of E
- E.foo matches any E element whose class attribute contains foo
- E#foo matches any E element with ID equal to foo