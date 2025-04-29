# Exp.No:17  
## Handling IndexError in Python using try-except


### AIM  

To write a Python program that avoids IndexError by using try-except and displays a custom message when accessing an invalid index in a list.

### ALGORITHM

1. Start the program.
2.Create a list with some elements.
3.Use a try block to access an index of the list.
4.If the index is valid, the element will be printed.
5.If the index is out of range, the except block catches the IndexError.
6.Display a custom message: "You're out of list range".
7.End the program.

### PROGRAM

```
lst=[5, 10, 20]
try:
    print(lst[5])
except:
    print("You're out of list range")

```

### OUTPUT
![image](https://github.com/user-attachments/assets/b6c70cfc-a38d-4767-bf56-3b51313a53ba)


### RESULT
Thus the Python program that avoids IndexError by using try-except is implemented and excecuted successfully.

