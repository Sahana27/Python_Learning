# Python Lists

There are four collection data types :  
* **List** :  
  - Collection which is ordered and changeable.  
  - Allows duplicate members.

* **Tuple** :  
  - Collection which is ordered and unchangeable.  
  - Allows duplicate members. 
  
* **Set** :  
  - Collection which is unordered and unindexed.   
  - No duplicate members.  

* **Dictionary** :  
  - Collection which is unordered, changeable and indexed.  
  - No duplicate members.  
  
Choosing right type of collection , would increase in efficiency or security.

### **List**
* List are written in Square braces.
* List is ordered and changeable.

```Example
thislist = ["apple", "banana", "cherry"]
print(thislist)
```

**Access Items**
* Can access the element using index number
```python
print(thislist[1])
```

**Change Item Value**
* To change the value of a specific item, refer using the index
```python
thislist[1] = "blackcurrant"
print(thislist)
```

**Loop through a List**
* Looping through list can be done using list
```python
thislist = ["apple", "banana", "cherry"]
for x in thislist:
  print(x)
```

**Check if Item Exists**
We can determine if a specified item is present in a list use the in keyword:
```python
thislist = ["apple", "banana", "cherry"]
if "apple" in thislist:
  print("Yes, 'apple' is in the fruit list")
```  

**List length**
* **len()** method is used to get the count of elements in the list
```python
thislist = ["apple", "banana", "cherry"]
print(len(thislist))
```

**Add Items**
* Add item to the end of list, using **append()** method
```python
thislist =["apple", "banana" , "cherry"]
thislist.append("orange")
print(thislist)
```

* To add element at particular index, use the insert() method:
```python
thislist.insert(2, "blackcurrent")
print(thislist)
```
