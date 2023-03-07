# Functions in Python
A function is a reusable block of code that performs a specific task. Functions are designed to take input arguments, process them, and then return a result. They are an essential part of modular programming and allow you to break down complex problems into smaller, more manageable parts. Here's my YouTube video tutorial: [Functions in Python](https://youtu.be/85yQ7wEIk9s).

<a href="https://www.youtube.com/watch?v=85yQ7wEIk9s" target="_blank">
  <img src="https://img.youtube.com/vi/85yQ7wEIk9s/0.jpg" alt="Functions in Python" width="560" height="315" border="0"/>
</a>

## Functions
Functions are defined using the `def` keyword, followed by the function name and a set of parentheses that may contain input parameters. The code that makes up the function is then indented beneath the `def` statement. So, let's get started by creating a simple function in Python. To do that, we start by using the `def` keyword, followed by the name of our function and any arguments it needs. Let's create a function called greet that takes in a name as an argument and prints out a greeting.

```python
def greeting_function(name):
    print("Hello " + name + "!")
```

Now that we've defined our function, we can call it from anywhere in our program. Let's call it and pass in a name to greeting_function:
```python
greeting_function("Sofia")
```

This will output `Hello Sofia!`.

We can also create functions with multiple arguments. Let's create a function that takes in two numbers and returns their sum:
```python
def sum_function(num1, num2):
    return num1+num2
```

Now we can call this function and pass in two numbers to add:
```python
result = sum_function(8, 7)
print(result)
```
This will output `15`.

Finally, it's worth noting that functions can also have default values for their arguments. This can be useful when you want to provide a default value that can be overridden if necessary. Let's modify our `greeting_function()` to have a default value of `"world"` for its name argument:
```python
def greeting_function(name="world"):
    print("Hello " + name + "!")
```

Now we can call this function with no arguments, and it will use the default value:
```python
greeting_function()
```

This will output `Hello world!`.

And that's it for this tutorial on creating functions in Python! I hope you found it helpful. Thanks for riding by. Happy coding!

