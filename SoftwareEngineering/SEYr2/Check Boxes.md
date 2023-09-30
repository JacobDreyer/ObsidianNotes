- Checkboxes which may appear alone or in groups allow the user to make yes/no or on/off selections

### Creating a Checkbox
- drag and drop onto the content panel
- Found in the Controls section of the Library panel
- CheckBoxes have a Text property that determines the text they display
- In the controller class, you can use the CheckBox’s isSelected method to determine whether the CheckBox is selected or not
	- Returns a boolean value
```java
if(checkbox.isSelected()){
	//execute code here if selected
}
```

### Responding to CheckBox Events
- Sometimes you want an action to take place at the time the user clicks a CheckBox
	- you must write an event listener method in the controller class for the CheckBox
	- and then select the method as the event listener in Scene Builder.

