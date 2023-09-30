- Radio Buttons normally appear in groups of two or more and allow the user to select one the several possible outcomes

### Creating a Radio Button
- To create a radio button simply drag it from the library panel and drop it onto the content panel.
- Found in the controls section of the library panel
- Radiobuttons have a text property that determines the text they display
- Radio buttons are normally in a toggle group

##### Adding Radio Buttons to a Toggle Group
- Create the first RadioButton component in the content panel
- Open the properties section of the inspector panel and find the toggle group property
- Enter the name you wish to give the toggle group
- Create the next radio button
- For its Toggle Group property, you shouls be able to click the down-arrrow and select the toggle group that you created for the first Radio button
- Repeat this for each susequent RadioButton that you want in the same toggle group

##### Determining if a RadioButton is Selected
- In the controller class you can use the RadioButton's isSelected method to determine whether the RadioButton is selected or not
	- Returns a boolean value
```java
if(radio.isSelected()){
	//code executes if button is selected
}
```

##### Responding to RadioButton Events
- In many situtations you want an action to take place at the time the user clicks a RadioButton
	- You must write an event listener method in the controller class for each RadioButton
	- and then select the appropriate method as the event listener in scene builder