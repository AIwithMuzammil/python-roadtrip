# Conditional Statements and Loops in Python
Conditional Statements and Loops are programming constructs that are used in Python, and in other programming languages, to control the flow of a program. In Python, the most commonly used conditional statements are the `if/else` statements, which check a condition and execute a block of code if the condition is true, and another block of code if the condition is false. There are also elif statements that can be used to add additional conditions to check. A Loop is a construct that allows the program to repeat a block of code multiple times until a certain condition is met. In Python, there are two commonly used loops: `while` and `for`. Both conditional statements and loops are important programming constructs that allow developers to write more complex programs and automate repetitive tasks. Here's my YouTube video tutorial: [Conditional Statements and Loops in Python](https://youtu.be/lOSVsPTC2io).

<a href="https://www.youtube.com/watch?v=lOSVsPTC2io" target="_blank">
  <img src="https://img.youtube.com/vi/lOSVsPTC2io/0.jpg" alt="Conditional Statements and Loops in Python" width="560" height="315" border="0"/>
</a>

## Conditional Statements

Conditional statements are used to perform different actions based on different conditions. The `if/else` statements are the most commonly used conditional statements in Python.

Here's an example code that uses `if/else` statements to check the temperature and print a message based on the temperature:

```python
temperature = -12

if temperature > 30:
    print("It is hot today!")
elif temperature < 30 and temperature > 20:
    print("It is pretty ok today!")
elif temperature < 20 and temperature > 5:
    print("It is cold today")
else: # temperature <= 5
    print("It is freezing today!")
```

In this code, the `if` statement checks whether the temperature is greater than 30. If it is, it prints the message `"It is hot today!"`. If the temperature is not greater than 30, the code moves to the next `elif` statement and checks whether the temperature is between 20 and 30. If it is, it prints the message `"It is pretty ok today!"`. The code continues to check the remaining conditions and prints the corresponding messages.


## Loops
Loops are used to repeat a block of code for a specified number of times or until a certain condition is met. The two most commonly used loops in Python are the while loop and the for loop.

### `while` Loop
The while loop in Python continues to execute a block of code as long as a certain condition is true. It checks the condition at the beginning of each iteration and stops when the condition becomes false.

In the following code block, we initialize a variable `max_iterations` to 5 and a variable iter to 0. We then use a while loop to print the message `"I am okay!"` five times:

```python
max_iterations = 5
iter = 0
while iter < max_iterations:
    print("I am okay!")
    iter = iter + 1
```

The output of the above code will be:

```sh
I am okay!
I am okay!
I am okay!
I am okay!
I am okay!
```

### `for` Loop

The for loop in Python is used to iterate over a sequence of items, such as a list or a string. It executes a block of code for each item in the sequence.

In the following code block, we use a for loop to print the numbers from 0 to 4:

```python
for iter in range(5):
    print(iter)
```

The `range()` function is used to generate a sequence of numbers from 0 to 4. By default, `range()` starts from 0, so we don't need to specify the start parameter. The output of the above code will be:

```sh
0
1
2
3
4
```

In the next example, we create a list of names and use a for loop to print each name in the list:

```python
names = ['Sofia', 'Ava Max', 'Sara']
for name in names:
    print(name)
```

The output of the above code will be:

```sh
Sofia
Ava Max
Sara
```

Finally, we add a name `Irfan` to the list of names and use a for loop to print a message if the name `Irfan` is found in the list:

```python
names = ['Sofia', 'Ava Max', 'Sara', 'Irfan']
for name in names:
    if name == "Irfan":
        print("Wow, he is also in the list!")
```

The output of the above code will be:

```
Wow, he is also in the list!
```

That's it! You can copy and paste this code into your Python environment to try it out yourself. Happy coding!

