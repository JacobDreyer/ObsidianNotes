The `sleep(long milliseconds)` method puts the thread to sleep for the specified time in milliseconds

Because the sleep method may throw an Interrupted Exception, which is a [[checked exception]], we have to put it in a [[Try-Catch Block]]

```java
public void run(){
	...
	try{
		Thread.sleep(10)
	}
	catch (InterruptedException ex){
		
	}
}
```