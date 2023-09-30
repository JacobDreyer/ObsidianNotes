```ad-note
title: Definition

Database Management Systems ([[DBMS]]) is a specialized software designed for the creation, retrieval, updating, and management of [[Database]]s

It serves as an interface between the [[Database]] and the users or application programs, ensuring that the data is consistently organized and remains easily accessible
```

- Storing data in traditional text or binary files has its limits
	- Well suited for applications that only store a small amount of data
	- Not practical for applications that must store a large amount of data
	- Simple operations like search and modify become hard and inefficient as data increases
- A database management system ([[DBMS]]) is a software that is specifically designed to work with large amounts of data in an efficient and organized manner
	- Data is stored using the database management system
	- Applications written in [[Java]] or other languages communicate with the DBMS rather than manipulate the data directly
	- DBMS carries out instructions and sends the results back to the application
![[Pasted image 20230314142237.png]]
### Advantages
- Control of data redundancy
- Data consistency
- More information from the same amount of data
- Sharing of data
- Improved data integrity
- Improved security
- Enforcement of standards
- Economy of scale
- Balanced conflicting requirements
- Improved data accessibility and responsiveness
- Increased productivity
- Improved maintenance through data independence
- Increased concurrency
- Improved backup and recovery services
### Disadvantages
- Complexity
- Size
- Cost
- Additional hardware costs
- Cost of conversion
- Performance 
- Higher impact of a failure
### [[DBMS Services]]
![[DBMS Services]]
### [[DBMS Environment]]
![[DBMS Environment]]
### [[JDBC]]
![[JDBC]]

### [[SQL]]
![[SQL]]

### Using a [[DBMS]]
- To use [[JDBC]] wo work with a database you will need a DBMS
	- [[Oracle]]
	- [[Microsoft SQL Server]]
	- [[DB2]]
	- [[MySQL]]
	- [[Java DB]]

### Tables, Rows, and Columns
- A database management system stores data in a [[Database]]
- A database is organized into one or more tables
- Each table holds a collection of related data, organized into rows and columns
- A row is a complete set of information about a single item, divided into columns
- Each column is an individual piece of information about the item

### Column Data Types
[[SQL]] Data Type:
- INTEGER or INT
	- An integer number
	- int (in [[Java]])
- CHARACTER (n) or CHAR (n)
	- A fixed length string with a length of n characters
	- String
- VARCHAR (n)
	- A variable-length string with a maximum length of n characters
- REAL
	- A single precision floating point number
	- float
- DOUBLE
	- A double-precision floating point number
	- double
- DECIMAL(t, d)
	- A decimal value with t total digits and d digits appearing after the decimal point
	- java.math.BigDecimal
- DATE
	- a date
	- java.sql.Date

### Primary Keys 
- A primary key is a column that holds a unique value for each row in a database table
- A primary key can be a combination of several columns in a table

### Connecting to the [[Database]]
- The static DriverManager.getConnection method is used to get a connection to the data base
```java
DriverManager.getConnection(DatabaseURL)l
```
- [[URL]] stands for [[Uniform Resource Locator]]

### Passing an [[SQL]] Statement to the [[DBMS]]
1. Once the connection to the database is established, you will get a reference to a Statement object to be used to issue SQL statements to the DBMS
	- A [[Statement Object]] has an [[executeQuery]] method that returns a reference to a [[ResultSet]] object
	- A ResultSet Object contains the results of the query
```java
Statement stmt = conn.createStatement();
String sqlStatement = "SELECT Description FROM Coffee";
ResultSet result = stmt.executeQuery(sqlStatement);
```

##### [[SQL INSERT]] Statement
```java
Statement stmt = conn.createStatement();
String sqlStatement = "INSERT INTO TableName (ColumnName1, ColumnName2, ...) VALUES (Value1, Value2, ...)";
int rows = stmt.executeUpdate(sqlStatement);
```
- rows should contain the value 1, indicating that 1 row was inserted

### [[ResultSet]] Object
##### next()
- A ResultSet object has an internal cursor
	- Points to a specific row in the ResultSet
	- The row it points to is the current row
	- Inititally positioned just before the first row
	- Can be moved from row to row to examine all rows
- A ResultSet object's next method moves the cursor to the next row in the ResultSet
```java
result.next();
```
- Moves to first row in a newly created ResultSet
- moves to the next row each time its called
- next() returns a boolean value
	- true if successfully moved to next row
	- false if there are no more rows
- A while loop can be used to move through all the rows of a newly created result set

##### get()
- You use one of ResultSet object's get methods to retrieve the contents of a specific column in the current row
- Can pass an argument for either the column number or the column name
```java
System.out.println(result.getString(1));

System.out.println(result.getDouble("Price"));
```

