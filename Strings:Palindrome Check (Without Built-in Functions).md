# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program

```
s = "google"
rev = s[::-1]

if s == rev:
    print("The string is a palindrome")
else:
    print("The string is not a palindrome")
```
## Output


<img width="384" height="225" alt="image" src="https://github.com/user-attachments/assets/71c71fec-745e-4230-8d0e-9c426bc84b6b" />

## Result

Thus, the Python program checks whether the string "google" is a palindrome without using any built-in palindrome checking functions and displays the correct result.
