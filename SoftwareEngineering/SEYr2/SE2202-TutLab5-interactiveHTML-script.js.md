Parent File: [[SE2202-TutLab5-InteractiveHTML]]
```js
var clearLabel = document.getElementById('btnClear');
var digitButtons = document.getElementsByClassName('digit');
var operationButtons = document.getElementsByClassName('operation');

for(let i=0; i<digitButtons.length; i++){
    digitButtons[i].addEventListener('click', displayDigit);
}

for(let i=0; i<operationButtons.length;i++){
    operationButtons[i].addEventListener('click', operationClicked);
}

function displayDigit(e){
    var target = e.target;
    let num = target.textContent;
    let sNum = num.toString();

    document.getElementById('display').textContent += sNum;
}

clearLabel.addEventListener('click', function(){
    document.getElementById('display').textContent = "";
});

let firstValue, secondValue, operation;

function operationClicked(e){
    displayLabel = document.getElementById('display').textContent;
    firstValue = parseInt(displayLabel);
    operation = e.target.textContent;
    document.getElementById('display').textContent = "";
}

var equalsLabel = document.getElementById('btnEqual');
equalsLabel.addEventListener('click', equalClicked);

function equalClicked(){
    console.log("reached =");
    secondValue=parseInt(document.getElementById('display').textContent);
    if(operation == "+"){
	    document.getElementById('display').textContent=
     firstValue+secondValue;
    } else if(operation == "-"){
        document.getElementById('display').textContent = firstValue - 
         secondValue;
    } else if(operation == "*"){
        document.getElementById('display').textContent = firstValue * 
         secondValue;
    } else {
        document.getElementById('display').textContent = firstValue / 
         secondValue;
    }
}
```