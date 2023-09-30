- In [[SQL]] the LIKE operator can be used to search for a substring
```sql
SELECT * From Coffee WHERE Description LIKE '%Decaf%'
SELECT * FROM Coffee WHERE ProdNum LIKE '2_-00_'
SELECT * FROM Coffee WHERE Description NOT LIKE '%Decaf%'
```
- The % symbol is used as a wildcard for multiple characters
- The _ is used as a wildcard for a single character
- The NOT opertor is used to disqualify the search criteria

