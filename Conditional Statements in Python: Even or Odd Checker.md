# Conditional Statements in Python: Even or Odd Checker

## 🎯 Aim
To write a Python program to check whether the given number is **even** or **odd** using `if...else` statements.

## 🧠 Algorithm
1. Get an input from the user.
2. Convert the input to an integer and store it in a variable `a`.
3. Use the modulo operator `%` to check if `a % 2 == 0`.
   - If true, print `"EVEN"`.
   - Else, print `"ODD"`.
4. End the program.

## 🧾 Program
```
#To write a Python program to check whether the given number is **even** or **odd** using `if...else` statements.
a=int(input("Enter the number which you want check whether it is even or odd number"))
if (a%2==0):
    print(a," is even")
else:
    print(a," is odd")
```
## Output
![Screenshot 2025-05-03 085808](https://github.com/user-attachments/assets/0ed7cf41-282c-43c6-95c6-6b013c2c9218)
![Screenshot 2025-05-03 085823](https://github.com/user-attachments/assets/c456713a-d3f4-42d8-b5a9-20373e129129)

## Result
Enter the number which you want check whether it is even or odd number 22
22  is even
