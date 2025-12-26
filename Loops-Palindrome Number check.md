## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
num = int(input("Enter a number: "))

temp = num

rev = 0

while temp > 0:
    rev = (10 * rev) + (temp % 10)  # Append the last digit of temp to rev
    temp = temp // 10  # Remove the last digit from temp

if rev == num:
    print(f"{num} is a palindrome!")
else:
    print(f"{num} is not a palindrome.")
## Output
<img width="1018" height="382" alt="image" src="https://github.com/user-attachments/assets/d5947511-3b51-4454-bafe-e700be7ae1d5" />
<img width="1238" height="346" alt="{0F8EB7E8-4F36-405F-BDC9-550DF548395E}" src="https://github.com/user-attachments/assets/280f56ac-dde6-4ed9-9dc8-f57ca2bb0786" />



## Result
Hence, the code is written and executed successfully
