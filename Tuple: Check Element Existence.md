# Ex 3e:List-Create a list from user input

## Aim
To write a Python program that reads the size of a list and then accepts elements from the user to create the list.

## Algorithm
1.Start the program.

2.Read the number of elements (n) from the user.

3.Create an empty list.

4.Repeat n times:
     Read an element as input.
     Append it to the list.

5.Display the final list.

6.End the program.
## Program
```
def convert(s):
size = int(input())

user_list = []

for i in range(size):
    element = input()
    user_list.append(element)

print(user_list)
```

## Output
<img width="954" height="338" alt="image" src="https://github.com/user-attachments/assets/18ae1dd2-3023-42b2-9669-84e1ac611032" />

## Result
Thus, the program successfully creates a list using the size and elements entered by the user.
