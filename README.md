# Python-Learning

## Getting Started
Variables are reserved memory locations that store values. In various other coding languages you would need to declare what the variable is, but in python the variables are declared automatically when you assign a value to them. 

Python has five standard data types
- Numbers
- String
- List
- Tuple
- Dictionary

### Numbers
There are numbers you can store like integers, longs, floats, and complex numbers. In earlier version of python you need to declare if a number was a long or not, but in Python 3.0 the numbers can be as big as necessary so you don't need to. 
- int _e.g.(1, 10, 25, 30)_
- long _e.g.(0122L, 1234817241132L)_
- float _e.g.(1.5, 10.0, 25.12)_
- complex _e.g.(15j, 15e-10j)_
```
    sampleInt = 10
    sampleFloat = 50.21
```

### Strings
Strings are essentially a list of characters. They can be assigned in double quotes `("Hello World")` or single quotes `('Hello World')`
```
    doubleQuotes = "Hello World"
    singleQuotes = 'Hello World'
```

### List
A list is used to store a bunch of different items. For example you can store strings and numbers in one list like 
```
    list = ["This is a List", 125, 2.31]
```
### Tuple
A tuple is similar to a list, but instead of using [] you would use (). Once a tuple has been declared it cannot be updated. It can only be read.
```
    list = ("This is a Tuple", 125, 2.31)
```
### Dictionary
A dictionary can be thought of as a hash table. Dictionaries have keys and values. A key is used to identify an object, while the value is the value of the object.
```
    exampleDictionary = {'myName':'Waltbo', 'favoriteColor':'Green', 'favoriteNum':215}
```
## Module One
In this module you should learn how to code simple math functions, learn how to create methods, and pass in method arguments. If you open `module_one.py` you will see there is already some code written for you. First you will see a simple function. A function is defined using the `def` keyword. 
After that there is the function name. In this case the function name is `add_numbers`. Afterwards there are arguments `(num1, num2)`. This is helpful for passing data into functions from other functions. This function here adds together two different numbers and uses the `return` statement to return the sum to where it was originally called from which was from the `run_me.py` file.
Math in python uses real world operators. Here is the list of operators
- \+ Addition
- \- Subtraction
- \* Multiplication
- / Division
- % Modulus
- ** Exponent

Since I created the first function to add, try creating the rest of the functions that utilizes the other operators in a similar fashion to how the addition function was made. 
If you check the `run_me.py` file you can see what the name of the methods are supposed to be. To test if your function is correct simply run the `run_me.py` file.
