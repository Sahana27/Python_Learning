# Python Strings

### String Literals
* String literal are surrounded by either single quotation marks or double quotation marks. 
* String can be outputted to screen using print function.

```python
print("hello")
```

* String is array of bytes representing unicode characters.
* Python does not have character datatype
* Square bracket can be used to access elements of the string. 

**Get the character at position 1 : FIrst character is at position 0**
```python
a = "Hello World"
print(a[1])
```

**Substring : Get the characters from position 2 to position 5 **
```python
b = 'Hello, World!"
print(b[2:5])
```

**Strip() method removes any whitespace from the beginning or the end**
```python
a = " Hello,World! "
print(a.strip())
```

**len(): Returns the length of a string**
```python
a = "Hello, World"
print(len(a))
```

**lower() method returns string in lowercase**
```python
a = 'Hello, World!'
print(a.lower())
```

**upper() method returns string in uppercase**
```python
a = 'Hello, World'
print(a.upper())
```

**replace() method replaces a string with another string**
```python
a = 'Hello, World!'
print(a.replace("H", "J"))
```

**split() Splits splits string into substring if it finds instances of the separator**
```python
a = "Hello, World!"
print(a.split(",")) # returns ['Hello', ' World!']
```

### Command-line String Input
* Allows for command line input
* Able to ask user for input.

Example : Asks user for username
```python
print("Enter your name")
x = input()
print("Hello, "+x)
```
