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
def remove(str):
   new_str = ""
   print(str)
   n = int(input("Enter the specified index of the character to remove:"))
   for i in str :
        if i != str[n] :
             new_str = new_str + i
   print(new_str)
str = input("Enter a string :")
remove(str)
```

## Output
<img width="357" height="159" alt="image" src="https://github.com/user-attachments/assets/8af6bb86-797d-4fa0-84df-018557b972c6" />

## Result
Thus, The Python program that accepts a string and removes the character at a specified index was executed successfully.
