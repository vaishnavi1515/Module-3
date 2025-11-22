# Ex 3c:List Operations in Python: Create a list from user-entered elements

## Aim
To write a Python program that reads the size of a list and then accepts elements from the user using eval() to create a list.
## Algorithm
1.Start the program.

2.Read the size of the list (n) from the user.

3.Create an empty list.

4.Repeat n times:
     Read an element using eval() and append it to the list.

5.Display the final list.

6.End the program.

## Program

```
n = int(input())
mylist = []

for i in range(n):
    element = eval(input())
    mylist.append(element)

print(mylist)
```
## Output
<img width="1061" height="328" alt="image" src="https://github.com/user-attachments/assets/60f71146-320c-4b0d-af3a-1f8f36e6159b" />

## Result
Thus, the program successfully creates a list by taking the size and elements from the user using eval()
