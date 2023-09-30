- In [[SQL]], the INSERT statement inserts a row into a table
```sql
INSERT INTO TableName VALUES (Value1, Value2, ...)
```
- TableName is the name of the database table
- Value1, Value2, ... is a list of column values
- If column order is uncertain:
```sql
INSERT INTO TableName (ColumnName1, ColumnName2, ...) VALUES (Value1, Value2, ...)
```
