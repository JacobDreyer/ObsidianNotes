```js
let arrayName = [1,2,3,4];

arrayName.forEach(element => {console.log(element); element+=5; 
 console.log(element)}) //arrayName is still [1,2,3,4] we only change elmnt

filteredArr = arrayName.filter(test); //test is a function. if test 
                              //returns true for a element in the array; 
                              //it is added to an array which is returned
							  //test must accept a value(the val to test)

transformedArr = arrayName.map(transform); //transform changes each 
                 //element which is then added to array which is returned

reducedArr = arrayName.reduce(reduceTo); //reduces array to one element
									//functionality dictated by reduceTo()
reducedArr = arrayName.reduce(reduceTo, startPoint); //can set start point


```

- When a function does not modify an array it is called pure