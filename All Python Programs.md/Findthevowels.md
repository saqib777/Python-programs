```
user = input("Enter a string:")
vowels = "aeiouAEIOU"
count = 0
for char in user:
    if char in vowels:
        count += 1
        print(f"vowels found: {char}")
print("Total number of vowels in the given string is:", count)

```
