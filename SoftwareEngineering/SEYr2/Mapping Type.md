A mapping object maps hashable values to arbitrary objects

Mappings are [[Mutable Objects]]

There is currently only one standard mapping type the dictionary (dict)

The elements of a dictionary are key:value pairs surrounded by curly brackets and seperated by commas
```python
numMap = {1:"one", 2:"two", 3:"three"}
listMap = {"odd":[1,3,5], "even":[2,4,6]}
tupleMap = {(1,3,5):"odd", (2,4,6): "even"}

numMap.keys()
#>[1,2,3]
numMap.items()
#>[(1,"one"), (2, "two"), (3,"three")]
numMap.values()
#> ["one", "two", "three"]

# other ways to create dictionaries:
a = dict(one=1, two=2, three=3)
b = dict(zip(["one", "two", "three"], [1,2,3]))
c = dict([("two", 2), ("three", 3)])

```