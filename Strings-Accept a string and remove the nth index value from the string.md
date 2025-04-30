# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program:


def remove(s):
    # 2. Read the index `n` from the user input.
    n = int(input())

    # 3. Initialize an empty string `a` to store the new string.
    a = ""

    # 4. Iterate over each index of the string using a `for` loop.
    for i in range(len(s)):
        # 5. Check if the current index `i` is not equal to `n`.
        if i != n:
            # 6. If `i != n`, append the character at index `i` to string `a`.
            a += s[i]

    # 7. After the loop, return the modified string `a`.
    return a


input_str = input()


print(remove(input_str))



## Output:
![Screenshot 2025-04-30 232550](https://github.com/user-attachments/assets/f998e4bf-ef27-40c8-8b1c-b01357e2da27)


## Result:
Python program that accepts a string and removes the character at a specified index is successfully executed.

