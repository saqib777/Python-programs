## Started the program to test if I remember everything!

Start Time: 02:30 PM

Date: 07/01/2026

Structured the code 15 mins:

```
While True:
  if option 1 selected:
      note1 = input(str("Add you notes"))
  if option 2 is selected:
      print(note1)
  if option 3 is selected:
      Return
```

Attempt 2:

four fixed phases, always in this order:

1. Show options
2. Ask for a choice
3. Decide what that choice means
4. Act

```
Print("Welcome to NotePad!")
o1= print("option 1 = Add Notes")
o2 = print("option 2 = view Notes")
o3 = print("option 3 = Exit") userinput = input("Select any option")

While True:
  If userinput is o1
      Note1 = Input(str("Enter your notes here"))
  if userinput is o2
      print(Note1)
  if userinput is o3
      Exit

```

True Code:

```
print = ("Welcome to NotePad!")

while True:
    print("\nMenu:")
    print("1. Add Note")
    print("2. View Notes")
    print("3. Exit")

    user_input = input("Select an option (1/2/3): ")

    if user_input == "1":
        print("Add note feature coming soon")

    elif user_input == "2":
        print("View notes feature coming soon")

    elif user_input == "3":
        print("Exiting the app. Goodbye!")
        break

    else:
        print("Invalid option. Please try again.")
```

<img width="737" height="242" alt="image" src="https://github.com/user-attachments/assets/e0b50a3e-83cf-4a4c-86f0-5b4b02a21f52" />

Time: 03:22 PM

### Error

<img width="1092" height="177" alt="image" src="https://github.com/user-attachments/assets/ab38bf0e-278a-4e02-a3c3-71c2c573e5a7" />

Cause: overwrote Python’s built-in print function

Correct & Final True Code:

```

print("Welcome to NotePad!")

while True:
    print("\nMenu:")
    print("1. Add Note")
    print("2. View Notes")
    print("3. Exit")

    user_input = input("Select an option (1/2/3): ")

    if user_input == "1":
        print("Add note feature coming soon")

    elif user_input == "2":
        print("View notes feature coming soon")

    elif user_input == "3":
        print("Exiting the app. Goodbye!")
        break

    else:
        print("Invalid option. Please try again.")
```

Day - 02 

Timme - 02:48 PM

Date: 08/01/2026

