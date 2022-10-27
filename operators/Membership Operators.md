# Membership Operators
```in, not in```

Membership operators are used to test if a sequence is presented in an object

### in 
Returns True if a sequence with the specified value is present in the object
x in y

### not in
Returns True if a sequence with the specified value is not present in the object
x not in y

### Example
```python
# Python program to illustrate
# not 'in' 'not in' operators
x = 24
y = 20
list1 = [10, 20, 30, 40, 50]

if (x not in list1):
	print("x is NOT present in given list1")
else:
	print("x is present in given list1")

if (y in list1):
	print("y is present in given list1")
else:
	print("y is NOT present in given list1")
```
