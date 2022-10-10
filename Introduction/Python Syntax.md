# Python Syntax

- Python was designed to for readability, and has some similarities to the English language with influence from mathematics.  
- Python uses new lines to complete a command, as opposed to other programming languages which often use semicolons or parentheses.  
- Python relies on indentation, using whitespace, to define scope; such as the scope of loops, functions and classes. Other programming languages often use curly-brackets for this purpose.
---
## Python Indentations
Where in other programming languages the indentation in code is for readability only, in Python the indentation is very important.

- Python uses indentation to indicate a block of code.
- Python will give you an error if you skip the indentation.

### Indentation Rules:
- Python statement ends within single line, It means each line in a Python script is a statement.
- Use the colon : to start a block and press Enter.
- All the lines in a block must use the same indentation, either space or a tab.
- Python recommends four spaces as indentation to make the code more readable. Do not mix space and tab in the same block.
- A block can have inner blocks with next level indentation.
---
## Comments
Python has commenting capability for the purpose of in-code documentation.

### Single Line Comment:
Comments start with a #, and Python will render the rest of the line as a comment:
``` python
#This is a comment.
print("Hello, World!")
#This is also a comment
```
### Multi Line Comment:  
Python doesn’t support multiline comments.
However, we can use multi-line docstrings as multiline comments.

---
## Docstrings
Python also has extended documentation capability, called docstrings.
Docstrings can be one line, or multiline. Docstrings are also comments:
Python uses triple quotes at the beginning and end of the docstring:

```python
""" This is a Singleline docstring """

""" This is a 
    multiline 
    docstring. """
    
print("Hello, World!")
```
---
## String literals
Python uses single quotes ('), double quotes ("), triple single quotes (''') and triple-double quotes (""") to denote a string literal.

The string literal need to be sourounding with the same type of quotes. For eample, if you use a single quote to start a string literal, you need to use the same single quote to end it.

The following shows some examples of string literals:

```python
s = 'This is a string' 
print(s) 
s = "Another string using double quotes" 
print(s) 
s = ''' string can span
        multiple line ''' 
print(s)
```
---
## Continuation of statements
Python uses a newline character to separate statements. It places each statement on one line.

However, a long statement can span multiple lines by using the backslash (\) character.

The following example illustrates how to use the backslash (\) character to continue a statement in the second line:
```python
if (a == True) and (b == False) and \    
(c == True):     
print("Continuation of statements")
```
