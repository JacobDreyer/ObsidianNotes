javaFX is a java library for developing rich applications that employ graphics 

You can use it to create:
- GUI applications as well as applications that display 2D and 3D graphics
- standalone graphics applications that run on your local computer
- applications that run from a remote server
- apllications that are embedded in a web page

JavaFX uses a theater metaphor to describe the structure of a GUI

a theater has a stage

on the stage a scene is performed by actors

in JavaFX, the stage is an empty window

The scene is a collection of GUI objects (controls) that are contained within the window

You can think of GUI objects as the actors that make up the scene

In memory the GUI objects in a scene are organized as nodes in a scene graph, which is a tree-like heirarchical structure

### [[Scene Graphs]]:
A scene graph can have 3 types of nodes:
- Root Node
	- The scene graph can have only 1 root node
	- It is the parent of all other nodes in the scene graph
	- It is the first node in the structure
- Branch node
	- A branch node can have other nodes as children
- Leaf Node:
	- A leaf node cannot have children

In JavaFX a node that can have children is a container

A container is a component that can hold other components inside of it

The JavaFX library provides several different types of containers

The AnchorPane container is commonly used as a GUI's root node

A branch node is a container that is placed inside the root node or inside another branch node

A leaf node is a component that is not a container

### The Application Class
- An abstract class that is the foundation of all JavaFX applications
- JavaFX applications must extend the Application class
- The Application class has an abstract method named start, which is the entry point for the application
- Because the start method is abstract you must override it 

### General Layout
- Various import statements
- A class that extends the Application Class
- A start method
- a main method

##### Ex:
```java
import javafx.application.Application;
import javafx.stage.Stage;
import javafx.scene.Scene;

public class ClassName extends Application{
	public static void main(String[] args){
		//launch the application
		launch(args);
	}

	@Override
	public void start(Stage primaryStage){
		//insert startup code here
		//Set the Window's Title
		primaryStage.setTitle("My First GUI Application");

		//Show the Window
		primaryStage.show();
	}
}
```

### [[Event-Driven Programming]]
![[Event-Driven Programming]]

### [[Specific JavaFX Controls]]
![[Specific JavaFX Controls]]
