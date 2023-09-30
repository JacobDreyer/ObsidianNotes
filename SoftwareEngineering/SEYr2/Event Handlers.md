- Event Handlers are objects 
- You write event handler classes that implement the EventHandler interface (from the javafx.event package)
- The EventHandler Interface specifices a void method named handle that has a parameter of the Event Class (or one of its subclasses)

```java
class ButtonClickHandler implements EventHandler<ActionEvent>{
	@Override
	void handle(ActionEvent event){
		//Write event handling code here
	}
}
```

### Registering an Event Handler
- The process of connecting an event handler object to a control is called registering the event
- Button controls have a method named setOnAction that registers an event Handler:
```java
mybutton.setOnAction(new ButtonClickHandler());
```
- When the user clicks the button, the event handler object's handle method will be executed