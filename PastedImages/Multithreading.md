![[Pasted image 20230201123609.png]]

```java
public class TaskClass implements Runnable {
	public TaskClass(...){
		...
	}

	public void run(){
		//tell system how to run custom thread
		...
	}
}

//client class
public class Client {
	public void someMethod(){
		//create instance
		TaskClass task = new TaskClass(...);
		//create a thread
		Thread thread = new Thread(task);
		//start Thread
		thread.start();
	}
}
```

### [[The Thread Class]]
![[The Thread Class]]