# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
```
# Read number of rows
n = int(input("Enter number of rows: "))

for i in range(n):
    # Print spaces for triangle shape
    for space in range(n - i - 1):
        print(" ", end="")

    value = 1
    for k in range(i + 1):
        print(value, end=" ")
        value = value * (i - k) // (k + 1)

    print()  # Move to next line
```

## Sample Output
<img width="1076" height="419" alt="image" src="https://github.com/user-attachments/assets/c4fc9e7a-a003-4e1e-8315-b14a65835737" />
<img width="1370" height="347" alt="{6DA51891-89EF-459D-A217-501C49E0B8DA}" src="https://github.com/user-attachments/assets/7b682015-d57e-475e-9852-dd18c05b34ae" />



## Result
hence, the code is written and executed
