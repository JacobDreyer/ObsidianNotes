- You can use the ImageView component to display images in an application's GUI
- You simply drag the component from the library panel (controls section) and drop it onto the content panel
- Once you have created a ImageView Component, you use its image property to specify the image that will display
- Sometimes you may need to write code that will change the image being displayed in an ImageView component, as the application is running
- In your controller class, you can call the ImageView component's setImage method to do this

### Displaying an Image with Code
- First you must create an instance of the Image Class, which can read the contents of an image file
- The image class is in the javafx.scene.image package
- The image class contructor accepts a String argument that is the name of an image file
```java
Image myImage = new Image("Dog.jpg");
Image myImage = new Image("file:src/exercise3/Rose.gif");
```

- Once you have created an Image Object, you pass a reference to that object to the ImageView Component's setImage method
```java
myImageView.setImage(myImage);
```