A promise is an attempt to execute a blocking code
- When a promise is fulfilled its status will be resolved (a resolve function was called)
- When a promise is not fulfilled its status will be rejected (a reject function was called)

To use it we create an instance of the Promise Class:
```js
let somePromise = new Promise(function(resolve, reject){
	//perform some asynchronous operation then:
	//resolve(value) if the operation succeeded, or
		//resolve basically calls the "then" function
	//reject(error) if the operation failed
});

somePromise.then(function(value){
	//handle successfull operation
	//called when asynchronous operation finishes
}).catch(function(error){
	//handle failed operation
})
```