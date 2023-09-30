# Document Object Model

### Specifies How:
1. Browsers create a model of an HTML page
2. [[JavaScript]] accesses/updates an HTML page

#### Element Nodes
```html
<u1>
	<li></li>
	<li></li>
	<li></li>
	<li></li>
<\u1>
```
#### Text Nodes
```html
<u1>
	<li>Fresh figs</li>
	<li>pine nuts</li>
	<li>honey</li>
	<li>balsamic vinegar</li>
<\u1>
```
#### Attribute Nodes
```html
<u1>
	<li id="one" class="hot">Fresh figs</li>
	<li id="two" class="hot">pine nuts</li>
	<li id="three" class="hot">honey</li>
	<li id="four">balsamic vinegar</li>
<\u1>
```
![[Pasted image 20221017110027.png]]

#### DOM Queries
```js
document.getElementById('one');
document.getElementsByClassName('hot');
document.getElementsByTagName('li');

document.querySelector('#one');
document.querySelector('.hot');
document.querySelector('li');
document.querySelectorAll('li.hot')
```

##### NodeList
If a DOM query returns more than one element it is known as a NodeList. 
Items in a NodeList are numbered and selected like an Array
```js
var elements;
elements = getElementsByClassName('hot');
var firstItem = elements[0];

//check if there are elements:
if (elements.length >= 1){
	var firstItem = elements[0];
}
```

#### Traversing the DOM
```js
//accesses second li
let secondLi = document.querySelectorAll('li')[1];

secondLi.parentNode; //accesses u1 in diagram above
secondLi.previousElementSibling; //accesses first li
secondLi.nextElementSibling; //accesses third li

//acceses u1
let u1Element = document.querySelector('u1');

u1Element.firstElementChild; //accesses first li
u1Element.lastElementChild; //accesses last li

```

#### Working With Elements
Elements can Contain:
- Text Content
- Element Content
- Attributes
```html
<!-- Text + Attribute -->
<li id="one">figs</li>

<!-- Text + Attribute + Element w/Text -->
<li id="one"><em>Fresh</em> figs</li>

<!-- Text + Attribute + Element w/Text + Text -->
<li id="one">six <em>Fresh</em> figs</li>
```

##### How to Access their Content
```js
var el = document.getElementById('one');


el.firstElementChild.nextSibling.nodeValue;
//returns figs
document.getElementById('one').textContent;
//returns fresh figs
document.getElementById('one').innerHTML;
//returns <em>fresh</em> figs

createElement();
createTextNode();
appendChild();
```

#### DOM Events
An event is an occasion that is of importance

Event-Driven system involve having mechanisms for
- "event detection", thats a way to know that the event happened
- "notification", That's notifying whoever is interested that it happened
- "event-handling", that's to allow some code to be executed in response

##### User Interface Events
- load
- unload
- error
- resize
- scroll

##### Keyboard Events
- keydown
- keyup
- keypress

##### Mouse Events
- click
- dblclick
- mousedown
- mouseup
- mouseover
- mouseout

##### Focus Events
- focus / focusin
- blur / focusout

##### Form Events
- input
- change
- submit
- reset
- cut
- copy
- paste 
- select

#### How Events Trigger JS Code
1. Select the element node(s) the script should respond too
2. Indicate the event on the selected node(s) that will trigger a response
3. State the code you want to run when the event occurs

##### Binding an Event to an Element
There are three ways:
- HTML event handler attributes
- Traditional DOM event handlers
- DOM level 2 event listeners

```html
<!-- do not use this way (HTML Event Handler) -->
<input type="text" id="username" onblur="checkUsername()">
```

```js
//traditional DOM event handler
e1.onblur = checkUsername;
```

```js
//Event Listeners
e1.addEventListener('blur', checkUsername);

//or
//used to passarguments
e1.addEventListener('blur', function(){checkUsername(5);})
```

```js
function checkUsername(e){
	var target = e.target;
}

var el = document.getElementById(‘username’); 
el.addEventListener(‘blur’, checkUsername);
```

#### The Event Object
When an event occurs, the event object can tell you information about it and which  element it happned upon

Properties:
- target
	- element that received the event
- type
	- the type of the element

