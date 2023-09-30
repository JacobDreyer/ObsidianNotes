```js
//private members

//JS is still object based so its better to follow convention and surround
//variables meant to be private with double underscores

//closures

let functionName = function(x){
    let xInFunction = x;              //xInFunction is private
    let getXInFunction = function(){
        return xInFunction;
    }
    return getXInFunction;
};
let functionRepresentingX = functionName(5);
console.log(functionRepresentingX()); //prints 5

//class
class ClassName{
    constructor(x){
        let xInClass = x;                //xInClass is only availible in
        this.funcGetVarX = function(){   //the constructor. so its private
            return xInClass;
        }
    }
}
let theClass = new ClassName(5);
console.log(theClass.funcGetVarX());
```

## \# Syntax
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes/Private_class_fields

```js
//# syntax
class ClassWithPrivateFields {
    #x;
    constructor(x){
        this.#x = x;
    }
    get getX(){
        return this.#x;
    }
    #calculateDouble(){
        return this.#x*2;
    }
}  
let theClass = new ClassWithPrivateFields(5);
console.log(theClass.getX);
```

