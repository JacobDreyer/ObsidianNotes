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