# Lesson 01: Python - Homework

Resource for reference:

* [Python documentation](https://docs.python.org/3.10/)

## Assignment 1 (1 pt)

Write a function `is_triangle` to check the validity of a triangle. This function should receive 3 parameters corresponding to the length of 3 edges. It should return boolean `True` if all 3 edges can form a triangle, else it returns `False`.

```
def is_triangle(a, b, c):
    # Write your code here.
    pass  # Remove this line

print(is_triangle(1, 2, 3))  # Expected output: False
print(is_triangle(2, 2, 3))  # Expected output: True
```

## Assignment 2 (1 pt)

Print odd numbers from 1 to 10 using `for` loop and `range`.

Expected output:
```
1
3
5
7
9
```

## Assignment 3 (1 pt)

Write a function `get_reverse` that return a reversed string.

Input: `Kenya`

Output: `ayneK`

```
def get_reverse(text):
    # Write your code here
    pass  # Remove this line
```

## Assignment 4 (1 pt)

Write a function that return a new set that contains elements that are either in set `a` or `b` but not both.

```
set1 = {10, 20, 30, 40, 50}
set2 = {30, 40, 50, 60, 70}

# Write your code here


# Expected output: {10, 20, 60, 70}
```

## Assignment 5 (1 pt)

Write a function `remove_from_list` that remove all occurrances of a value from a list.

```
def remove_from_list(input_list, value):
    # Write your code here
    pass  # Remove this line

a = [10, 20, 10, 30, 40, 50, 10, 0]
remove_from_list(a, 10)
print(a)  # Expected output: [20, 30, 40, 50, 0]
```

## Assignment 6 (1 pt)

Complete the following class by: (1 pt)

* Write code that assign `name` and `score` to the object.
* Write method `get_score` that return `score` attribute of the object.
* Write method `describe` that print `<student name>: <student score>`.

```
class Student:
    def __init__(self, name, score):
        # Write your code here
        pass  # Remove this line

    def get_score(self):
        # Write your code here
        pass  # Remove this line
    
    def describe(self):
        # Write your code here
        pass  # Remove this line

student = Student("John", 85)
print(student.get_score())  # Expected output: 85
student.describe()  # Expected output: "John: 85"
```

## Assignment 7 (1 pt)

Complete the `Employee` class by:

* Write code that calls the `__init__` method of the base class to initialize attributes.
* Write a `speak` method that receives a word as its parameter and outputs `"Employee <employee name> spoke <word>"`

```
class Person:
    def __init__(self, name):
        self.name = name

    def speak(self):
        return "Person " + self.name + " spoke something."

class Employee(Person):
    def __init__(self, name):
        # Write your code here
        pass  # Remove this line

    def speak(self, word):
        # Write your code here
        pass

employee = Employee("David")
print(employee.speak("hello"))  # Expected output: "Employee David spoke hello"
```

## Assignment 8 (1 pt)

Print all the key-value pairs of a dictionary using `for` loop. Each line is a key-value pair.

Hint: to get all the keys of a dictionary, use `.keys()`.

```
country_capital = {
    "japan": "tokyo",
    "vietnam": "hanoi",
    "france": "paris"
}

# Write your code here.


# Expected output:
"""
japan - tokyo
vietnam - hanoi
france - paris
"""
```

## Assignment 9 (2 pt)

Write a function `solve_equation` to solve equation ax^2 + bx + c = 0. (1 pt)

* If equation has no solutions, print `No solution`.
* If equation has one solution, print `Equation has one solution <x>` (`<x>` is the value of the solution)
* If equation has two solutions, print `Equation has two solutions <x1> and <x2>` (`<x1>` and `<x2>` are the values of the solution)


```
def solve_equation(a, b, c):
    # Write your code here
    pass
```