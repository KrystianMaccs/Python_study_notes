# Python Data Types
________________________________________
# Built-in Data Types
In programming, data type is an important concept.
Variables can store data of different types, and different types can do different things.
Python has the following data types built-in by default, in these categories:
Text Type:	Str
Numeric Types:	int, float, complex
Sequence Types:	list, tuple, range
Mapping Type:	Dict
Set Types:	set, frozenset
Boolean Type:	Bool
Binary Types:	bytes, bytearray, memoryview
________________________________________
# Getting the Data Type
You can get the data type of any object by using the type() function:
Example
Print the data type of the variable x:
x = 5
print(type(x))

# Setting the Data Type
In Python, the data type is set when you assign a value to a variable:
Example	Data Type
x = "Hello World" --> str

x = 20 --> int

x = 20.5 --> float

x = 1j --> complex

x = ["apple", "banana", "cherry"] --> list	

x = ("apple", "banana", "cherry") --> tuple	

x = range(6)
x = {"name" : "John", "age" : 36}
x = {"apple", "banana", "cherry"}
x = frozenset({"apple", "banana", "cherry"})
x = True
x = b"Hello"
x = bytearray(5)
x = memoryview(bytes(5))	memoryview


________________________________________
# Setting the Specific Data Type
If you want to specify the data type, you can use the following constructor functions:
Example	Data Type
x = str("Hello World") --> str

x = int(20) --> int	

x = float(20.5) --> float
x = complex(1j) --> complex
x = list(("apple", "banana", "cherry")) --> list
x = tuple(("apple", "banana", "cherry")) --> tuple
x = range(6) --> range
x = dict(name="John", age=36) --> dict
x = set(("apple", "banana", "cherry")) --> set
x = frozenset(("apple", "banana", "cherry")) --> frozenset
x = bool(5) --> bool
x = bytes(5) --> bytes
x = bytearray(5) --> bytearray
x = memoryview(bytes(5)) --> memoryview
