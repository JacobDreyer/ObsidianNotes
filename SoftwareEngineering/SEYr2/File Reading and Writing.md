```js
let fs = require('fs');
fs.writeFile('filePath.txt', message, ()=>{}); //calls the function after 
                       //finishes. will create the file if it isnt already

//importing JSON
let name = require('./fileName.json');
console.log(name.otherName);
```