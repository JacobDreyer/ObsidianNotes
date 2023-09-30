## Cascaded Style Sheets
- CSS Associates Style Rules with HTML elements
- Properties describe physical layout of specific HTML tags
- The essential concepts are selectors and properties
```c++
p {font-family: Arial;}

h1, h2, h3 {font-family: Arial; color: yellow;}
```

Example:
```html
<h1>From Garden to Plate</h1>
<p>A <i>potager</i> is a french term for an ornamental vegetable or kitchen garden...</p>

<h2>What to Plant</h2>
<p>Plants are chosen as much for their functionality as for their colour and form...</p>
```
![[Pasted image 20220912135644.png]]
With CSS:
```CSS
body {font-family: Arial, Verdana, sans-serif;}

h1, h2 {
	color: #ee3e80;}

p {color: #665544;}
```
![[Pasted image 20220912135927.png]]
#### Using Internal CSS
```css
<head>
	<title>Using Internal CSS</title>
	<style type="text/css">
		body {
			font-family: arial;
			background-color: rgb(185, 179, 175);}
		h1 { color: rgb(255,255,255);}
	</style>
</head>
```
#### Using External CSS
```html
<html>
	<head>
		<title>Using External CSS</title>
		<link href="css/styles.css" type="text/css"
		 rel="stylesheet">
	</head>
	<body>
		<h1>Potatoes</h1>
		<p>There are dozens of...</p>
	</body>
</html>
```
- href sets path
- type and rel remain same
##### Why use External
- Same CSS can be used for every page
- No need to copy style code into each webpage
- Changes to CSS automatically apply to entire website
- Easier for many people to create new pages in same style

#### [[CSS Properties and Values]]
![[CSS Properties and Values]]

#### [[CSS Selectors]]
![[CSS Selectors]]
#### Examples:
- [[SE2202-TutLab1-MyPortfolio]]
