
# max of two

## The problem
Find the max number of two numbers.

## Hints
Ask the user to enter two numbers. 

Then, you can run a comparison to compare which one is larger. 

Think about it and try yourself first. 

## Solution
```python
num1 = int(input("First number: "))
num2 = int(input("Second number: "))
if (num2 >= num1):
    largest = num2
else:
    largest = num1
print("Largest number you entered is: ", largest)
```

## Shortcut
Another simple and alternative solution is to send the numbers to the max function.
```python
num1 = int(input("First number: "))
num2 = int(input("Second number: "))
largest = max(num1, num2)
print("Largest number you entered is: ", largest)
```

## Alternative Solution
Another alternative approach is to use the floor method from the math module. If you pass a number with a fraction to the math.floor function, it will return you the integer part of the number. 

For example, 
```python
import math
result = math.floor(3.4)
print(result)
```
