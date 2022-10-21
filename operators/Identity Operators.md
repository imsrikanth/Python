# Identity Operators
```is, is not```

Identity operators are used to compare the objects, not if they are equal, but if they are actually the same object, with the same memory location

### Same as (is)
Returns True if both variables are identical
x is y

### Not the same as (is not)
Returns True if both variables are not identical
x is not y

### Examples
```python
a = 10
b = 20
c = a

print(a is not b)
print(a is c)
```
