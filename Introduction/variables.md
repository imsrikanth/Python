# Variables
## What is Variable
When you develop a program, you need to manage values, a lot of them. To store values, you use variables.

In Python, a variable is a label that you can assign a value to it. And a variable is always associated with a value.

Example:
```python
message = 'Hello, World!'
print(message)
```
here message is a variable holding the string 'Hello, World!'

Multiple Assignment
```python
a,b,c = 1,45,'Hello'
print(a,b,c)
```
The variable message can hold various values at different times. And its value can change throughout the program.

## Creating Variable
To define a variable, you use the following syntax:
```python
variable_name = value
```
The = is the assignment operator. In this syntax, you assign a value to the variable_name.

The value can be anything like a number, a string, etc., that you assign to the variable.

## Naming variables
When you name a variable, you need to adhere to some rules. If you don’t, you’ll get an error.

### Rules to name the variables:
- Variable names can contain only letters, numbers, and underscores . They can start with a letter or an underscore , not with a number.  
- Variable names cannot contain spaces. To separate words in variables, you use underscores, for example sorted_list.  
- Variable names cannot the same as keywords, reserved words, and built-in functions in Python.  
### Guidelines to define good variable names:
- Variable names should be concise and descriptive. For example, the active_user variable is more descriptive than the au.   
- Use underscores _ to separate multiple words in the variable names.  
- The variable name can consist of alphabet letter(s), number(s) and underscore(s) only. For example, myVar, MyVar, _myVar, MyVar123 are valid variable names, but m*var, my-var, 1myVar are invalid variable names.  
- Variable names in Python are case sensitive. So, NAME, name, nAME, and nAmE are treated as different variable names.  
