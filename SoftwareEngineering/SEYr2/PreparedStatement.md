```java
String sqlStatement = "...";
PreparedStatement stmt = connection.prepareStatement(sqlStatement);

stmt.setInt(1, score);
stmt.setString(2, teamName);

stmt.executeUpdate();
```