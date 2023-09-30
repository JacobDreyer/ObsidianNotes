You can use the `yield()` method to temporarily release time for other threads
```java
public void run(){
	...
	Thread.yield();
}
```
