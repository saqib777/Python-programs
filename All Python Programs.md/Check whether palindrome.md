```
user = input("Enter your string to check  if it is palindrome:")
def is_palindrome(s): 
    reversed_s = ""
    for char in s:
        reversed_s = char + reversed_s
    return s == reversed_s
if is_palindrome(user):
    print(f'"{user}" is a palindrome.') 
else:
    print(f'"{user}" is not a palindrome.')

```
