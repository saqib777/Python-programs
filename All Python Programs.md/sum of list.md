```
user_input = input("Enter numbers separated by spaces: ")

# Split into list of strings
user_list = user_input.split()

# Convert each item to integer
int_list = [int(num) for num in user_list]

# Calculate sum
sum_list = sum(int_list)

print("The sum of the list is:", sum_list)
```
