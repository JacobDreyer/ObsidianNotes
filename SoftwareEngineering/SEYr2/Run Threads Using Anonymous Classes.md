```java
Thread thread = new Thread(new Runnable(){
	@Override
	public void run(){
		...
	}
});

thread.start();

new Thread(new Runnable(){
	@Override
	public void run(){
		...
	}
}).start();

new Thread(()->{
	...
}).start();
```
