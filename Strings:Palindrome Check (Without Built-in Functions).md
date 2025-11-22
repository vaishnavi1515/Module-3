# Ex 3d:Tuple in Python: Tuple of multiples of 5 up to N

## Aim
To write a Python program that creates a tuple containing multiples of 5 up to a user-given number N.
## Algorithm
1.Start the program.

2.Read the value of N from the user.

3.Create an empty list.

4.Use a loop from 5 to N (exclusive), stepping by 5.

5.Append each multiple of 5 to the list.

6.Convert the list into a tuple.

7.Display the tuple.

8.End the program.
## Program
```
N = int(input())

multiples_of_5 = tuple(i for i in range(5, N, 5))

print(multiples_of_5)
```
## Output
<img width="790" height="167" alt="image" src="https://github.com/user-attachments/assets/8eb54ef6-9d05-4a57-b615-e111b2ee8699" />

## Result
Thus, the program successfully creates a tuple containing multiples of 5 up to the given number N.
