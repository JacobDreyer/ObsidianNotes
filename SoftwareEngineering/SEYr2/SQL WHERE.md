- The WHERE clause can be used with the [[SQL SELECT]] statement to specify a search criteria
```sql
SELECT Columns FROM Table WHERE Criteria
SELECT * FROM Coffee WHERE Price > 12.00
SELECT * FROM Coffee WHERE Description = 'French Roast Dark'
SELECT * FROM Coffee WHERE Price > 10.00 AND Price < 14.00
SELECT * FROM Coffee WHERE Price < 10.00 OR Price > 14.00
```
- Only the rows that meet the search criteria are returned in the result set


