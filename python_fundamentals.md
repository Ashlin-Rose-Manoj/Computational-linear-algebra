# **Python Fundamentals**

Python is a high-level, interpreted programming language that was created by Guido van Rossum and first released in 1991. Its design philosophy emphasizes code readability and simplicity, making it an excellent choice for both beginners and experienced developers. Over the years, Python has undergone significant development and improvement, with major releases adding new features and optimizations. The language’s versatility and ease of use have made it popular in various domains, including web development, data science, artificial intelligence, scientific computing, automation, and more. Python’s extensive standard library and active community contribute to its widespread adoption, making it one of the most popular programming languages in the world today.

# Printing text
print("Hello, World!")

# Printing multiple values
x = 5
y = 10
print("The value of x is:", x, "and the value of y is:", y)

# Assigning values to variables
a = 10
b = 20.5
name = "Alice"

# Printing the values
print("Values Stored in the Variables:")
print(a)
print(b)
print(name)

# Taking input from the user
name = input("Enter usr name: ")

 Python Programming Style
 Indentation
 if a > b:
    print("a is greater than b")
else:
    print("b is greater than or equal to a")                         
print("Hello, " + name + "!")

# Taking numerical input
age = int(input("Enter usr age: "))
print("us are", age, "years old.")

# Program to calculate the sum of two numbers
num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))

# Calculate sum
sum = num1 + num2

# Display the result
print("The sum of", num1, "and", num2, "is", sum)
student_name = "John"
total_score = 95
# Creating strings with different types of quotes
single_quoted = 'Hello, World!'
double_quoted = "Hello, World!"
multiline_string = """This is a
multiline string"""

# Accessing the first item
first_fruit = fruits[0]  # Output: "apple"

# Accessing the last item
last_fruit = fruits[-1]  # Output: "cherry"
# Using list methods
numbers = [5, 2, 9, 1]

numbers.append(4)     # numbers is now [5, 2, 9, 1, 4]
numbers.sort()        # numbers is now [1, 2, 4, 5, 9]
numbers.reverse()     # numbers is now [9, 5, 4, 2, 1]
first_number = numbers.pop(0)  # first_number is 9, numbers is now [5, 4, 2, 1]

# Using tuple methods
numbers = (1, 2, 3, 1, 2, 1)

# Counting occurrences of an item
count_1 = numbers.count(1)  # Result: 3

# Finding the index of an item
index_2 = numbers.index(2)  # Result: 1
# Using dictionary methods
keys = student.keys()        # Result: dict_keys(['name', 'age', 'graduation_year'])
values = student.values()    # Result: dict_values(['Alice', 22, 2024])
items = student.items()      # Result: dict_items([('name', 'Alice'), ('age', 22), ('graduation_year', 2024)])
name = student.get("name")  # Result: "Alice"
age = student.pop("age")    # Result: 22
# Checking membership
has_apple = "apple" in fruits  # Output: True

# Since frozenset is immutable, us cannot use add() or remove() methods
# Using frozen set methods
set1 = frozenset([1, 2, 3])
set2 = frozenset([3, 4, 5])

# Getting the difference
difference = set1.difference(set2)  # Result: frozenset({1, 2})

# Getting the intersection
intersection = set1.intersection(set2)  # Result: frozenset({3})

# Getting the union
union = set1.union(set2)  # Result: frozenset({1, 2, 3, 4, 5})

# Getting the symmetric difference
symmetric_difference = set1.symmetric_difference(set2)  # Result: frozenset({1, 2, 4, 5})

Control Structures in Python
 Conditional Statements
 age = 20

if age < 18:
    print("us are a minor.")
elif age < 65:
    print("us are an adult.")
else:
    print("us are a senior citizen.")
while condition:
    # Code block to execute while condition is True
    for i in range(5):
    if i == 2:
        continue
    print(i) 
# Output: 0 1 3 4
for i in range(5):
    if i == 3:
        pass  # Placeholder for future code
    else:
        print(i)
# Output: 0 1 2 4
 Functions in Python Programming

 def greet(name):
    """
    Returns a greeting message for the given name.
    """
    return f"Hello, {name}!"
    # main.py

import my_library

result_sum = my_library.add(5, 3)
result_product = my_library.multiply(5, 3)

print(f"Sum: {result_sum}")
print(f"Product: {result_product}")
# main.py

import my_library

result_sum = my_library.add(5, 3)
result_product = my_library.multiply(5, 3)

print(f"Sum: {result_sum}")
print(f"Product: {result_product}")
