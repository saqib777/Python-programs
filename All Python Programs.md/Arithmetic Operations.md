```
# Program to perform basic arithmetic operations

# Taking input from the user
num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))

# Performing arithmetic operations
addition = num1 + num2
subtraction = num1 - num2
multiplication = num1 * num2

# To avoid division by zero error
if num2 != 0:
    division = num1 / num2
    modulus = num1 % num2
else:
    division = "Undefined (division by zero)"
    modulus = "Undefined (division by zero)"

# Displaying results
print("\nArithmetic Operations Results:")
print("Addition:", addition)
print("Subtraction:", subtraction)
print("Multiplication:", multiplication)
print("Division:", division)
print("Modulus:", modulus)
```

```
Output: 

Arithmetic Operations Results:
Addition: 90.0
Subtraction: 0.0
Multiplication: 2025.0
Division: 1.0
Modulus: 0.0
```
