### Methods
```java
int getColumnCount()
```
- Returns the number of columns in the result set

```java
String getColumnName(int col)
```
- Returns the name of the column specified by the integer col. The first column is column 1

```java
String getColumnTypeName(int col)
```
- Returns the name of the data type of the column specified by the integer col. The data-type returned is the database-specific [[SQL]] data type

```java
int getColumnDisplaySize(int col)
```
- Returns the display width, in characters, of the column specified by the integer col

```java
String getTableName(int col)
```
- Returns the name of the table associated with column specified by the integer col