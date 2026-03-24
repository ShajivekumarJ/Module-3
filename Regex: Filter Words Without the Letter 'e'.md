# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
~~~
# Program to filter words without 'e' using regex

import re

l1 = []
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']

for i in items:
    if not re.search(r"e", i):
        l1.append(i)

print("Filtered list:", l1)
~~~
## Output

<img width="426" height="210" alt="Screenshot 2026-03-24 140825" src="https://github.com/user-attachments/assets/9e2b9e6c-4584-4603-ad1a-ac62d3d07cc4" />

## Result
Thus, the Python program to filter words that do not contain the letter 'e' using regular expressions was successfully executed and verified.
