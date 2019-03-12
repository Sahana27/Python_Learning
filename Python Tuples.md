# Python Tuples

Collection which is ordered and unchangeable.In python, tuples are written with round brackets

### **Create Tuples**
```
thistuple = ("apple", "banana", "cherry")
print(thistuple)
```

### **Access Tuple Items**
Can access tuple item by referring to index number, inside square braces
```
print(thistuple([1])
```

### **Change tuple Values**
Once tuple is created, we cannot change values. 
```
thistuple[1] = "blackcurrant"
# The values will remain the same:
print(thistuple)
```

### **Loop through Tuple**
We can loop through tuple item using for loop
```
for x in thistuple:
  print(x)
```

### **Check if Item Exists**
If a specified item is present in a tuple use the keyword **in**
```
if "apple" in thistuple:
  print("Yes, 'apple'is in the fruit tuple")
```

### **Tuple Length**
**len()** determines number of items are in tuple
```
print(len(thistuple))
```

### **Add Items**
Tuples are unchangeable, once tuple is created, we cannot add an item.
```
thistuple[3] = "banana"
print(thistuple)
```

### **Remove Items**
Tuples are unchangeable, hence we cannot remove items from tuple.

To delete tuple completely
```
del thistuple
```

### **tuple() constructor**
Use **tuple()** constructor to make tuple
```
thistuple = tuple(("apple", "banana", "cherry"))
print(thistuple)
```

### **Tuple Methods**  
Following are built in Tuple Methods 

|Method|Description|
|------|------------|
|count()|Returns the number of times a specified value occurs in a tuple |
|index() | Searches the tuple for a specified value and returns the position of where it was found|


