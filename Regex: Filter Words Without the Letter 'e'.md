# Ex 3b:Regex in Python: Replace digit 5 with “five” in a string

## Aim
To write a Python program that replaces all occurrences of the digit 5 with the word "five" in a given string.
## Algorithm
1.Start the program.

2.Read a string from the user.

3.Use the string replace() function to replace "5" with "five".

4.Display the modified string.

5.End the program.

## Program
```
def replace_5_with_five(text):
    return text.replace("5", "five")

# Get input from user
user_input = input()
result = replace_5_with_five(user_input)
print(result)
```
## Output
<img width="1160" height="171" alt="image" src="https://github.com/user-attachments/assets/802cf2ca-2fba-4022-9ef3-52467f24a145" />

## Result
Thus, the program successfully replaces all occurrences of the digit 5 with the word "five" in the given string.
