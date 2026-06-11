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
```
def remove(s):
    n = int(input("Enter the index to remove: "))
    a = ""

    for i in range(len(s)):
        if i != n:
            a = a + s[i]

    return a

# Read the input string
s = input("Enter a string: ")

# Display the modified string
print("String after removing the character:", remove(s))
```

## Output
<img width="575" height="226" alt="image" src="https://github.com/user-attachments/assets/3cdbdb9b-f91f-4dff-a9e1-735a26899142" />


## Result
The above program has been executed successfully.
