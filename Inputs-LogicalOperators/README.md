# Python Console Input and Logical Operators


In this tutorial, we'll be discusssing how to take input from the console in Python and what are different logical operators. Here's my YouTube video tutorial walking through these steps: [Python Console Input and Logical Operators](https://youtu.be/xszzagPyFmY).

<a href="https://www.youtube.com/watch?v=xszzagPyFmY" target="_blank">
  <img src="https://img.youtube.com/vi/xszzagPyFmY/0.jpg" alt="Getting Started with Python" width="560" height="315" border="0"/>
</a>

## How to Take Input from the Console

In this section of the code, we are taking input from the user through the console. The input function is used to prompt the user to enter a value, and the entered value is stored in a variable called `myinput`. The input is always a string, so it is important to remember to convert it to the desired data type later on if necessary. Finally, we print the value of the `myinput` variable to the console.
```python
myinput = input("Enter your name: ") # the input is always a string
print(myinput)
```

In the next few lines of code, we take input from the user for two numeric values, num1 and num2. We then convert these values to integers using the int function and add them together. The result of this calculation is then printed to the console.
```python
num1 = input("Enter your num1: ")
num2 = input("Enter your num2: ")
print(int(num1) + int(num2)) # converting to int
```

We repeat this process again, this time converting the values to floats instead of integers. Again, we print the result of the calculation to the console.
```python
num1 = input("Enter your num1: ")
num2 = input("Enter your num2: ")
print(float(num1) + float(num2)) # converting to float
```

## Logical Operators
In this section of the code, we demonstrate how logical operators can be used in Python. We start by assigning a value of 2000 to the variable `price_car`. We then use the logical operators or and and to compare this value to other values.
```python
price_car = 2000 # int
price_car_float = 2000.0 # float
print(price_car < 500 or price_car > 1000) # False or True = True
print(price_car < 500 and price_car > 1000) # False and True = False
```

It must be noted that although `price_car_float` is similar to `price_car` in terms of real-world value, it is fundamentally different in terms of python datatype and values. 

Next, we use a combination of `AND` and `OR` to create a more complex expression that evaluates to `True`/`False`. Finally, we use the type function to determine the data type of the price_car variable, and we use the `is` and `is not` operators to compare the type to data types.
```python
print(price_car < 500 and price_car > 1000 or price_car == 2000) # False and True or 
print(type(price_car) is int)
print(type(price_car) is not str)
```

Overall, this code provides a good introduction to the input function and logical operators in Python. By combining these concepts, we can create more complex programs and calculations that can be used for a variety of tasks.