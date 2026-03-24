# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
~~~
# Program to remove nth index character from a string

def remove(s):
    n = int(input("Enter index to remove: "))
    a = ""
    
    for i in range(len(s)):
        if i != n:
            a += s[i]
    
    return a

# Input string
s = input("Enter a string: ")

# Function call
result = remove(s)

# Output
print("Modified string:", result)
~~~
## Output

<img width="409" height="233" alt="Screenshot 2026-03-24 141048" src="https://github.com/user-attachments/assets/255cd729-730d-4a7d-bd4b-07721e499304" />


## Result
Thus, the Python program to remove the character at a specified index from a string was successfully executed and verified.
