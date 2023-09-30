### [[Control Statements]]
```java
if(true){
	//execute if aboce is true
} else if(true){
	//execute if true and previous if statement(s) were false
} else{
	//execute if passed through everything else
}

switch (variable){
	case 1:
		//execute if case matches variable value
		break; //so it doesnt execute folllowing just cause this 
               //passed
    case 2:
	    //execute if case matches
	    //no break means next case will execute regardless of truth
	case "string":
		//execute if case matches variable or if previous case
		//matches variable
		break;
	default:
		//execute if no other case matches
		break;
}

for(int i=start; i<end; i += increase){
	//runs internal code end-start times
	//starts at start ends at end increasing by increase
}

for(int listValue : list){
	//runs list size times going through each element of list
	//and assigning that value to listValue
}

while(statement){
	//runs while statement evaluates to true
}

do{
	//runs once before checking if statement is true
} while(statement)
```

### [[Functions]] and [[JavaScript Methods]]
```java
//driver method
public static void main(String[] args){

}

private int func(int arg1, char arg2){
	//has to return an int cause its an int functio
	int ret;
	return ret;
}

//overloaded functions
public void func1(){
	//stuff1
}
public void func1(int x){
	//stuff2
}
func1() //refers to first
func1(5)//refers to second
```

### [[Classes]] and [[Interfaces]]
```java
public class ClassName {
	private String var1 = "";

	public ClassName(){
		//constructor
		//called when object is created
		//can be overloaded
	}
	public ClassName(int x){
	}
}

public interface InterfaceName{
	
}

public class SubClassName extends ClassName {

}
public class OtherClassName implements InterfaceName {

}
public class SomeClassName extends SubClassName implements 
 InterfaceName{
 }

ClassName cls = new ClassName();
ClassName cls2 = new ClassName(5);
ArrayList<ClassName> arrList = new ArrayList();

///////////////////////////////////Generics/////////////////////////////////

public class MyClass <T>{
	private T fir, sec;
	public MyClass(T first, T second){
		fir = first;
		sec = second;
	}
	public void setFirst(T first){
		fir = first
	}
	public T getFirst(){
		return fir;
	}
}

public interface Pairable <S>{
	public void setPair(S firstItem, S secondItem);
}

Integer x = 5, y = 3;
MyClass <String>cls = new MyClass<String>("Stuff", "More Stuff")
MyClass <Integer>cls2 = new MyClass<Integer>(x,y);

//Bounded/Unbounded Generics
<T extends Circle> //T is a subtype of Circle Class
<? extends T> //T or any subtype of T
<? super T> //T or any super-type of T
```

### [[Variable]]s
```java
int x=0;
double x = 0.0;
char x='0';
String x = "00";
ArrayList<Integer> listName = new ArrayList<>(startSize);//must be wrapper 
                                                //class not primitive
varType[] arrName = new varType[size];

//related functions
listName.size();
arrName.length;
```

### [[String Methods]]
```java
strName.split("-"); //split at dashes. returns string array of pieces
```

### [[Scanner]] and [[Print Statements]]
```java
//Scanner
import java.util.Scanner;

Scanner scnerName = new Scanner(System.in);
Scanner scnerName = new Scanner(file);

scnerName.nextInt();
scnerName.nextDouble();
scnerName.next().charAt(0); //get character
scnerName.nextLine();
scnerName.nextBoolean();

```

### [[Exception]]s
```java
try{
	//dangerous statement
	//throws Exceptions
	if(true)
		throw new IndexOutofBoundsException;
	else if (true)
		throw new IllegalArgumentException;
} catch(IndexOutOfBoundsException ex){
	//does something
} catch(Exception ex){
	//does something
} finally{
	//does regardless of exception thrown or not
}
```

### [[Files]]
```java
import java.io.File;

File file = new File("fileName.txt");
```

### [[Math.]]
```java
Math.sqrt(num);
Math.abs(num); //absolute value
Math.max(num1, num2);
Math.min(num1, num2);
Math.cbrt(num) //cube root
Math.pow(base, power);
Math.signum(num); //find sign of num
Math.random();    //random # between 0 and 1
Math.sin(num);
Math.cos(num);
Math.tan(num);
Math.toDegrees(num); //convert radians to degrees
Math.toRadians(num); //convert degress to radians
```

### System.
```java
System.arraycopy(sourceArr, startSourcePos, destArr, startDestPos, 
 numToBeCopied);
```

### [[Map ADT]]s

### [[Object Class]] Methods
```java
var.hashCode(); //returns hashCode for var
```

### [[JavaFX]]
```java
//controller:
public class Controller {
	@FXML  
	private ElementType ElementName;

    public void initialize(URL url, ResourceBundle resourceBundle){  
          
    }  
}

//application
public class HelloApplication extends Application {  
    @Override  
    public void start(Stage stage) throws IOException {  
        FXMLLoader fxmlLoader = new   XMLLoader(HelloApplication.class.getResource("SortingHub-view.fxml"));  
        Scene scene = new Scene(fxmlLoader.load(), 320, 240);  
        stage.setTitle("Sorting Hub");  
        stage.setScene(scene);  
        stage.show();  
    }  
  
    public static void main(String[] args) {  
        launch();  
    }  
}
```

### [[Multithreading]]
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

//yield method:
public void run(){ 
	... 
	Thread.yield(); 
}

//sleep method:
public void run(){ 
	... 
	try{ 
		Thread.sleep(10) 
	} catch (InterruptedException ex){ 
	
	} 
}

//join method:
try { 
	thread1.join(); 
} catch (InterruptedException ex){ 

}

//anonymous classes
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