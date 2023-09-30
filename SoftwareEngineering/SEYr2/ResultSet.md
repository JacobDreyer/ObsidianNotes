- first()
	- Moves the cursor to the first row
- last()
	- Moves the cursor to the last row
- next()
	- Moves the cursor to the next row
- previous()
	- Moves the cursor to the previous row

### ResultSet Scrolling Types
- ResultSet.TYPE_FORWARD_ONLY
	- Default Scrolling Type
	- Cursor only moves forward
- ResultSet.TYPE_SCROLL_INSENSITIVE
	- Cursor moves both forward and backward
	- changes made to the database do not appear
- ResultSet.TYPE_SCROLL_SENSITIVE
	- Cursor moves both forward and backward
	- Changes made to the database appear as soon as they are made

### ResultSet Concurrency Levels
- ResultSet.CONCUR_READ_ONLY
	- Default Concurrency level
	- Read-only version of data from the database
	- Cannot change database by altering result set
- ResultSet.CONCUR_UPDATEABLE
	- Result Set is updateable
	- Changes can be made to the result set and saved to the database
	- Uses methods that allow changes to be made to the database without issuing [[SQL]] Statements

### Navigation Methods
- relative(rows)
	- Moves the cursor the number specified by the rows argument relative to the current row
		- A positive rows value will move the cursor forwards
		- A negative value will move it back
- Aboslute(rows)
	- Moves the cursor to the row number specified by the rows argument
		- A rows value of 1 will move the cursor the the first row
		- A rows value of 2 will move the cursor the the second row
		- etc.

### ResultSet Metadata
- [[Metadata]] refers to data that describes other data
- A ResultSet object has metadata that describes a result set
- can be used to determine many things about a result set
	- Number of Columns
	- Column names
	- Column data types 
	- and much more
- Useful for submiting [[SQL]] queries in applications the getMetaData method of a ResultSet object returns a reference to a ResultSetMetaData object
```java
ResultSetMetaData meta = resultSet.getMetaData();
```

### [[ResultSetMetaData]]
![[ResultSetMetaData]]
