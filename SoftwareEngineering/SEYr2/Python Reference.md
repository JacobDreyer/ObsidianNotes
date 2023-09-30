https://docs.python.org/3.11/index.html

### [[Print Statements]]
```python
print('Hello\nWorld')
#> Hello
#> World
print('''Hello
World''')
#> Hello
#> World

a = [10,9,8,7,6,5,4,3,2,1]
print(a[::-1])
#> [1,2,3,4,5,6,7,8,9,10]
print(a[5:]) #index 5 to end
print(a[3:8]) #index 3 to 8
```
### [[Python If Statements]]
```python
if grade > 80:
	print("stuff")
elif grade < 80 and grade > 70:
	print("other stuff")
elif grade < 50:
	print("something"); print("more stuff")
else
	print("things")
```

### [[Sequence Types]]
```python

#converting sequence types
list('abc')
#> ['a', 'b', 'c']
str([1,2,3])
#>'[1,2,3]'
tuple('abc')
#> ('a', 'b', 'c')

#other operations
myList = ['1','2','3']
"_".join(myList)
#> '1_2_3'

#Creating Sequence Types
#Range
range(stop)
range(start, stop[, step])
#List
myList = [1,2,True, [3,4], 'abc']
#Tuple
myTuple = ()
myTuple = 5,
myTuple = (5,)
notATuple = (5)
myTuple = 7,True,'abc',()
myTuple = (7,True,'abc',())
```

### [[Python Loops]]
```python
#While Loop:
i=0
while i<6:
	i+=1
	print(i)
else:
	print("Loop Finished")

#For Loops
fruits = ["apple", "banana", "cherry"]
for x in fruits:
	if x == "banana":
		continue
	print(x)

for index, MyPet in enumerate(pets):
	print(index, MyPet)
#> 0 cat
#> 1 dog
#> 2 fish

for x in range(6):
	print(x)
else:
	print("Loop Finished")
```

### [[Set Type]] and [[Mapping Type]]
```python
# Set Type:
setOne = {"abc", "xyz"}
anotherSet = {1,2,3,4}
setOne.update(anotherSet)
#> setOne == {1,2,3,4,"abc","xyz"}

#Dictionary:
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

### [[Python Function]]
```python
def add(a, b):
	c = a+b
	print(str(a) + " + " + str(b) + " = " + str(c))
	return c

def sum(*values):  # accepts any # of values
	#stuff

def otherAdd(a=0, b=0):
	return a+b

def multipleVars(**variables)
	print(variables) #> {'a' : 'A', 'b':5}

result = add(a, b)
result = otherAdd() #>0
result = otherAdd(5) #> 5+0 = 5
result = otherAdd(b=5) #> 0+5 = 5
multipleVars(a = 'A', b=5)

#lambda functions
add = lambda a,b : a+b
print(add(5,7))
```

### [[Exception Handling#Python]]
```python
#file handling
with open('file_path', 'w') as file:
	file.write('Hello World!')

try:
	print(y)
	z = y+1
except NameError:
	print("Error Message")
except
	raise Exception("something else went wrong")
else:
	print("Result is if passed:")
finally
	print("This always runs")
```

### [[Python Library - Copy]]
```python
import copy

c = [3,4]
d = copy.deepcopy(c)
```
### [[Python Library - Logging]]
```python
import logging

logging.basicConfig(level=logging.WARNING, format='%(asctime)s - %(filename)s[line:%(lineno)d] - %(levelname)s: %(message)s')

# using logging feature, by default the logging level is warning
logging.debug('This is loggging debug message')
logging.info('This is loggging info message')
logging.warning('This is loggging a warning message')
logging.error('This is an loggging error message')
logging.critical('This is loggging critical message')

#>WARNING:root:This is loggging a warning message
#>ERROR:root:This is an loggging error message
#>CRITICAL:root:This is loggging critical message

logger = logging.getLogger('my_logger')
  
logging.basicConfig(level=logging.DEBUG)

logging.debug('This WILL get logged')
#>DEBUG:root:This WILL get logged
```

### Misc
```python
a is b #when a and b share same memory

assert variable != None, "Text to display if it is None"
assert var2 > 0, "Text to display if num is 0 or -ve"
```
### [[Python Reusable Code Blocks]]
![[Python Reusable Code Blocks]]

