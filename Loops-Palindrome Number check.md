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
<img width="1220" height="504" alt="Screenshot 2025-12-28 125500" src="https://github.com/user-attachments/assets/4bf3d21b-76ab-44a6-9f02-76a48cc15cf9" />

## Output
<img width="1181" height="243" alt="Screenshot 2025-12-28 125008" src="https://github.com/user-attachments/assets/54e3a70e-4b73-4727-b59e-08fbd90d7642" />

## Result
Thus the program is successfully executed.
