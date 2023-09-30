```python
import csv

filename = "Temp_Resources/countries.csv"
fields = [] #1D list of field names
rows = [] #2D list -> list of rows -> for each row: list of content

with open(filename, 'r') as csvfile:
    #create csv reader object which is iterable
    csvreader = csv.reader(csvfile)
    
    #extract field names from first row
    fields = next(csvreader)
    
    #extract data from each row
    for row in csvreader:
        rows.append(row)

print(fields) #1D list of field names
print(rows) #2D list -> list of rows -> for each row: list of content
```
