- extends [[Hash Map]] with a linked list implementation that supports an ordering of the entries in the map.
- The entries in [[Hash Map]] are not ordered, but the entries in a LinkedHashMap can be retreived in the order in which they were inserted into the map, or the order in which they were accessed. From first accessed to most recently accessed
- To construct a LinkedHashMap use the true flag
```java
LinkedHashMap(initialCapacity, loadFactor, true);
```


