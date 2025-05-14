# Strings-Palindrome Check in Python (Without Built-in Functions)

## Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## Program
```
# Assign the string "google" to a variable
word = "google"

# Reverse the string manually using slicing
reversed_word = word[::-1]

# Compare the original string with the reversed string
if word == reversed_word:
    print("The string is a palindrome.")
else:
    print("The string is not a palindrome.")
```

## Output
![image](https://github.com/user-attachments/assets/92bf7431-bfbd-4b0a-be2c-9825119b3925)


## Result
Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions is successfully executed.
