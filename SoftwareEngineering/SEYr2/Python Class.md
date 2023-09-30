```python
class MyClass:
	name = ''
	num = 0;

	def __init__(self):
		self.num = 1

class OtherClass(MyClass):
	def __init__(self, name, otherNum)
		super().__init__()
		self.otherNum = otherNum
		self.name = name

	def aNewFunction(self, multiply)
		self.otherNum = self.otherNum*multiply

clas = MyClass()
clas.name = "stuff"
del clas.name  #resets name

myOtherClass = OtherClass("stuff", 5)

myOtherClass.aNewFunction(2)
```