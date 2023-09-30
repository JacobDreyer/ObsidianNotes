An object of a set type is an unordered collection of distinct hashable objects

Common uses include membership testing, removing duplicates from a sequence, and computing mathematical operations such as intersection, union, difference, and symmetric difference

Set is a Mutable set type

frozenset is an immutable set type

Sets are iterables so can be iterated over in a loop and can be used to create other types of iterables

Documentation to learn more about the possible operations:
https://docs.python.org/3.9/library/stdtypes.html?highlight=frozenset#set-types-set-frozenset

### The Mutable Set:
A comma sperated elements surrounded by curly brackets

The order of elements has no meaning

```python
setOne = {"abc", "xyz"}
anotherSet = {1,2,3,4}
setOne.update(anotherSet)
#> setOne == {1,2,3,4,"abc","xyz"}
```