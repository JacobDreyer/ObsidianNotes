You can use the `join()` method to force one thread to wait for another thread to finish

For Example:
```java
try {
	thread1.join();
}
catch (InterruptedException ex){
}
```