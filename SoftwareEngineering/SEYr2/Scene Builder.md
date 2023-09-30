- Scene buildier is a free design-tool from Oracle for visually creating GUIs
- How it Works:
	- Use SceneBuilder to construct a GUI by dragging and dropping the components that you need onto a blank window
	- Visuaaly arragnge the components on the window and set various component properties to create the appearence that you want for the GUI.
	- Save the GUI to an FXML file
- FXML is a markup language that describes the components in a javaFX scene graph
- FXML uses tags to organize data, in a manner similar to the way that HTML uses tags to format text in a web browser
- Visually creating a GUI with scne builder is only part of the process
- Once you save a GUI's scne graph to an FXML file the next step is to write java code that reads the FXML file and displays the GUI on the screen and handles and events that occur while the application is running

### A Brief Summary:
- Menu Bar
	- Scene Builder's commands are located on the menus that access the menu bar at the top of the main window
- Library panel 
	- The library panel provides a list of JavaFX components that you can use in an application
	- To place a component in a GUI, you simply drag it from the library panel and drop it into the content panel
- Content Panel
	- The content Panel is where you visually design an Application's GUI
	- It initially shows an AnchorPane as the GUI's Root node
	- you create other components in the GUI by dragging them from the library panel and dropping them onto the root node component
- Hierarchy Panel
	- The Heirarchy Panel shows the GUI's scene graph 
	- As you add components to the control panel Nodes appear in the Hierarchy Panel
	- You can use the Hierarchy Panel to select nodes that you want to edit
- Selection bar
	- This area of the screen show the heirarchial path of the currently selected node in the scene graph
- Inspector Panel
	- The inspector panel is divided into 3 sections:
		- Properties
			- Allows you to view and edit the values of the selected component's properties, which are values that determine the component's appearence
		- Layout
			- Lets you specify values that control the way the component is displayed when the GUI's window is resized
		- Code
			- allows you to assign an fx:id to a component, which is similar to assigning a variable name to the component
			- Also allows you to designate event handlers to execute when specific events happen to the selected component

### Writing the Application Code
A simple JavaFX application uses:
- a main application class
- a controller class

##### The Main Application Class
Once you have created a GUI with scene builder, and saved it to an FXML file you need to write a Java Class that performs the following: 
- Loads the FXML file
- Builds the scene graph in memory
- Displays the GUI

##### The Controller Class
The controller class is responsible for handling events that occur while the application is running

It contains the following:
- The necessary import statements
- Private variables to reference the components that have fx:id in the scene graph
- an initialzie method that is automatically called after the FXML file is loaded
- Event Listener Methods

##### Sample Controller Skeleton:
- An alternative for manually typing the code for the controller class, scene builder can provide a sample "skeleton" for the controller class
- To see the sample controller skeleton, click the View menu, then click Show Sample Controller Skeleton
- You can click the copy button to copy the sample code to the clipboard, and then paste it into an editing window in your IDE
- The obvious benefit of using the sample skeleton controller is that a lot of the code is written for you
- The skeleton has all the necessary import statements, and the class already has private field declarations for all the components that have an fx:id
- You just need to change the name of the class, and write the code for the event listener methods

## Summary
- Use Scene Builder to design the GUI. Be sure to give an fx:id to all of the components that you plan to access in your Java code. Save the GUI as an FXML file.
- Write the code for the main application class, which loads the FXML file and launches the application. Save and compile the code in the same location as the FXML file.
- Write the code for the controller class, which contains the event handler methods for the GUI. Save and compile the code in the same location as the FXML file.
- In Scene Builder, register the controller class, then register an event handler method for each component that needs to respond to events. Save the FXML file again.

