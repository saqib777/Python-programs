# Program to demonstrate working with tuples in Python

# Creating a tuple
numbers = (10, 20, 30, 40, 50)

print("Original Tuple:", numbers)

# Accessing elements using indexing
print("First element:", numbers[0])
print("Last element:", numbers[-1])

# Slicing a tuple
print("Sliced Tuple (index 1 to 3):", numbers[1:4])

# Finding length of tuple
print("Length of tuple:", len(numbers))

# Tuple with mixed data types
mixed_tuple = ("Python", 3.9, True, 100)
print("Mixed Tuple:", mixed_tuple)

# Nested tuple
nested_tuple = (numbers, mixed_tuple)
print("Nested Tuple:", nested_tuple)

# Iterating through a tuple
print("Elements in the tuple:")
for item in numbers:
    print(item)

# Checking if an element exists
if 30 in numbers:
    print("30 is present in the tuple")

# Tuple is immutable (demonstration using try-except)
try:
    numbers[0] = 99
except TypeError:
    print("Tuples are immutable, values cannot be changed")

# Tuple methods
print("Count of 20:", numbers.count(20))
print("Index of 40:", numbers.index(40))
