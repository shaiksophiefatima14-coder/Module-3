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
```
import re

# Initialize an empty list
l1 = []

# Define the list of words
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']

# Iterate through each word in the list
for i in items:
    # Check if the word does not contain the letter 'e'
    if not re.search(r"e", i):
        l1.append(i)

# Print the filtered list
print(l1)
```
## Output
<img width="475" height="180" alt="image" src="https://github.com/user-attachments/assets/b0037d6c-216b-430a-add0-e353a484495c" />


## Result
The above Program has been executed successfully.
