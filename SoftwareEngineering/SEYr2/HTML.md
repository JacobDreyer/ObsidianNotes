[[HTML and CSS Reference]]
### Hyper Text Markup Language
- Simple, purist design principles
- HTML describes the logical structure of a document
- [[Browser]]s are free to interpret tags differently
- HTML is a lightweight file format
	- Size of file containing just "Hello World"
		- MS Word: 11,274 bytes
		- PDF: 4915 bytes
		- HTML: 28 bytes
##### HTML Validity
- HTML has a formal syntax specification
- 800 lines of [[DTD Notation]]
- A validator gives syntax errors for invalid documents
- Valid documents may contain this logo
![[Pasted image 20230919083419.png]]
- Check Validity with validator.w3.org
	- Most websites have validation errors

Reasons for Invalidity
- Ignorance of HTML standard
- Lack of Testing
- "This page is optimized for the XYZ browser"
- "This page is best viewed in 1024x768"
- Automatic tools generate invalid HTML output
- Forgiving browsers try to interpret invalid input

Problems with Invalidity:
- Many Implementations
	- Vendors; Platforms; Versions
- Each implementation must interpret invalid HTML
- There are many arbitrary choices to make
- As a result, the HTML standard has been undermined
- HTML renders differently for most clients

A standard for Invalid HTML:
- The [[HTML Tidy]] tool tries to save the situation
- Invalid HTML is transformed to (almost) valid HTML
- Still many arbitrary choices, but now we agree
- HTML5 attempts to address this using similar approach

##### Limitations of HTML
- HTML is designed for [[Hypertext]] not for recipes
- Structure and presentation is intertwined
- HTML validation is less than recipe validation
- HTML standards have been undermined
- We need a special recipe markup language

##### Bytes vs Characters
- HTML files are represented as text files
- A text file is logically a sequence of characters but physically a sequence of bytes
- Several mappings exist:
	- [[ASCII]]
	- [[EBCDIC]]
	- [[Unicode]]
- [[Unicode]] aims to cover all characters in all past or present written languages
### [[Character Encodings in HTML]]
![[Character Encodings in HTML]]
### [[History of HTML]]
![[History of HTML]]
##### An HTML Element:
![[Pasted image 20220909110137.png]]
p = paragraph

##### Attributes Tell us More about Elements
![[Pasted image 20220909110424.png]]
```HTML
<html>
	<head>
		<title> This is a Title </title>
	</head>
	<body>
		<h1> This is the body of the page </h1>
		<p> Anyhting within the body is displayed in the
			main browser window </p>
	</body>
</html>
```
![[Pasted image 20220909110836.png]]

##### Writing Links
```html
<a href="http://www.imbd.com">IMBD</a>
```

##### Linking to Other Pages on the Same Site
```html
<a href="index.html">Home</a>
```

##### Linking to a specific part of the same page:
```html
<h1 id="top">
	Film-Making Terms</h1>

<a href="#prologue">Prolouge</a><br />

<h2 id="prologue">Prologue</h2>

<a href="#top">Top</a>
```
<br/> = line break

##### [[HTML Entities]]
Mechanism for writing special characters
- Those that are used for [[HTML]] syntax: <, >, =, ", &, #, ?
- Commonly used symbols
Begins with ampersand (&) and ends with semicolon (;)
- e.g. &lt; for <, &gt; for >, &copy; for ©
- &#num; for an [[Unicode]] character reference in decimal (or &#xnum; in hexdecimal)

![[HTML Forms]]

#### Examples:
- [[SE2202-TutLab1-MyPortfolio]]