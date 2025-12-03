```
String1 = "Mohammed Saqib"
reversed_string = "biqas demmahoM"
def reverse_string(s):
    reversed_s = ""
    for char in s:
        reversed_s = char + reversed_s
    return reversed_s
print(reverse_string(String1))  # Output: biqas demmahoM
print(reversed_string)  # Output: biqas demmahoM
print("Reversed String matches expected:", reverse_string(String1) == reversed_string)

'''
def reverse_string(s):
    reversed_s = ""
    for char in s:
        reversed_s = char + reversed_s
    return reversed_s
Let’s see how it works for "abc":

Start with reversed_s = ""

First loop: char = 'a' → reversed_s = 'a'

Second loop: char = 'b' → reversed_s = 'b' + 'a' → 'ba'

Third loop: char = 'c' → reversed_s = 'c' + 'ba' → 'cba'

So the final reversed string is 'cba'.
'''
```
