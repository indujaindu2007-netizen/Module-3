Module-3
🧹 Strings-Remove Nth Index Character from a String
🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

🧠 Algorithm
Define a function named remove that takes the input string as an argument.
Read the index n from the user input.
Initialize an empty string a to store the new string.
Iterate over each index of the string using a for loop.
Check if the current index i is not equal to n.
If i != n, append the character at index i to string a.
After the loop, return the modified string a.
Print the final result.
💻 Program
```
def remove(s, n):
    a = ""
    for i in range(len(s)):
        if i != n:
            a = a + s[i]
    return a

s = input("Enter a string: ")
n = int(input("Enter index to remove: "))

print("Result:", remove(s, n))
```
Output


<img width="377" height="232" alt="image" src="https://github.com/user-attachments/assets/f22259a9-4962-41a8-b79e-6bb14d0677ec" />

Result
Thus, the Python program successfully removes the character at the specified index from the given string and prints the modified string.


