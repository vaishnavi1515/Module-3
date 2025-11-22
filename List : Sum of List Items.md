# Module-3
# Ex 3a:Strings-Convert string characters (upper/lower/number)

## Aim
To write a Python function that converts uppercase letters to lowercase, lowercase letters to uppercase, and replaces all digits with * using if–elif statements.
## Algorithm
1.Start the program.

2.Define a function convert(s).

3.For each character in the string:
      If it is uppercase → convert to lowercase.
      Else if it is lowercase → convert to uppercase.
      Else if it is a digit → replace with *.
      Else → keep the character unchanged.

4.Append the converted characters to a new string.

5.Return the final string.

6.End the program.
## Program
```
def convert(s):
    result = ""
    for char in s:
        if char.isupper():
            result += char.lower()
        elif char.islower():
            result += char.upper()
        elif char.isdigit():
            result += "*"
        else:
            result += char  # Leave symbols/punctuation unchanged
    print(result)
```

## Output
<img width="592" height="168" alt="image" src="https://github.com/user-attachments/assets/9268167c-94eb-4e01-a6f5-99e7c5648c58" />

## Result
Thus, the program successfully converts uppercase letters to lowercase, lowercase letters to uppercase, and replaces numbers with * using a function and if–elif statements.
