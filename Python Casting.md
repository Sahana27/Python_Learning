# Python Casting

### Specify a Variable Type 
* Type to a variable can be assigned by **casting**
* Casting in python is done using constructor functions :
  - **int()**
    Constructs an integer number from an integer literal.
    float literal to integer is done by rounding down to the previous number
    string literal to integer takes the whole number.

    Example 
    ```python
    x = int(1)   # x will be 1
    y = int(2.8) # y will be 2
    z = int("3") # z will be 3
    ```

  - **float()**
    constructs a float number from an integer literal
    float literal or string literal
    
    Example 
    ```python
    x = float(1)     # x will be 1.0
    y = float(2.8)   # y will be 2.8
    z = float("3")   # z will be 3.0
    w = float("4.2") # w will be 4.2
    ```
  
  - **str()**
    constructs from a wide variety of data types.
    including strings, integer literals and float literals
    
    Example
    ```python
    x = str("s1") # x will be 's1'
    y = str(2)    # y will be '2'
    z = str(3.0)  # z will be '3.0'
    ```
