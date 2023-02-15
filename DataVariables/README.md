# Python Data Variables
In Python, data types refer to the types of values that can be assigned to variables. There are several built-in data types in Python, including strings, integers, and floating-point numbers. Understanding data types is important for writing code that performs operations and manipulations on data.

## Data Types
### Strings (str)
Strings are a type of data that represents text. They are defined by enclosing the text in quotation marks, either single ('') or double (""). Strings can be manipulated and combined using string methods such as concatenation, slicing, and formatting. For example:

```
name = "Bob"  # string (str)
print(name)
```

This will output the string "Bob" to the console.

### Integers (int)
Integers are a type of data that represent whole numbers. They can be positive, negative, or zero. Integers can be used in mathematical operations such as addition, subtraction, multiplication, and division. For example:

```
year = 2000  # integer (int)
print(year)
```

This will output the integer value 2000 to the console.

### Floating-Point Numbers (float)
Floating-point numbers, or floats, are a type of data that represent decimal numbers. They can be used in the same mathematical operations as integers, as well as more advanced mathematical functions such as trigonometric functions and logarithms. For example:

```
height = 175.8  # float (float)
print(height)
```
This will output the floating-point number 175.8 to the console.

## Data Structures
In addition to basic data types, Python also includes several data structures for organizing and manipulating data. These include lists, tuples, and dictionaries.

### Lists
Lists are a type of data structure that can contain multiple values, including values of different data types. They are defined by enclosing the values in square brackets, separated by commas. Lists are mutable, meaning that their contents can be changed. For example:
```
mylist = ['Anna', 2002, 180]  # list - mutable
```

This will create a list containing a string, an integer, and a floating-point number.

### Tuples
Tuples are similar to lists in that they can contain multiple values of different data types. However, tuples are immutable, meaning that their contents cannot be changed after they are created. Tuples are defined by enclosing the values in parentheses, separated by commas. For example:

```
mytuple = ('Sofia', 2002, 180)  # tuple - immutable
```

This will create a tuple containing a string, an integer, and a floating-point number.

### Dictionaries
Dictionaries are a type of data structure that contain key-value pairs. Each key in the dictionary corresponds to a value, which can be of any data type. Dictionaries are mutable, meaning that their contents can be changed. Dictionaries are defined by enclosing the key-value pairs in curly braces, separated by commas. For example:

```
mydictionary = {"name": "Ava Max", "age": 20, "year": 2002}  # dictionary: key-value pair
```
This will create a dictionary containing three key-value pairs.

Example Script
Here's an example script that demonstrates the use of the data types and data structures described above:

```
#
# https://youtube.com/@AIwithMuzammil/
#

name = "Bob" # string (str)
print(name)

year = 2000 # integer (int)
print(year)

height = 175.8 # float (float)
print(height)

print("The name is " + name + ", the birth year is " + str(year) + ", and the height is " + str(height)) # accepts string only when printing multiple datatypes

# data structures: list, tuple, dictionary
mylist = ['Anna', 2002, 180] # list - mutable
mytuple = ('Sofia', 2002, 180) # tuple - immutable
mydictionary = {"name": "Ava Max", "age": 20, "year": 2002} # dictionary: key-value pair

mydictionary = {"names": ['Anna', 'Sofia', 'Irfan'], "age": [20, 18, 45]}
print(mydictionary)
```








