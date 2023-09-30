## [[JavaScript]] in the Browser
- Call Java Script from element attribute
```html
<html>
	<head>
		<Title>Hello World</title>
	</head>
	<body>
		<button onclick='alert("Hello JS World!");'>Say Hello!</button>
	</body>
</html>
```
![[Pasted image 20220913155015.png]]
-------------------------------------------------------
```html
<html>
	<head>
		<title>Hello World</title>
	</head>
	<body>
		<script src='js/hello.js'></script>//calls lower V code block
	</body>
</html>
```
```js
hello.js

alert("hello world");      //semicolon not nessecary unless combining
alert("bye world")           //into one line//should still use it

```
