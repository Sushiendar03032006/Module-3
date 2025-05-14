![image](https://github.com/user-attachments/assets/bc4a0d38-de03-4c43-a20c-db80704411a5)# Module-3
# Strings-Remove Nth Index Character from a String

## Aim
To write a Python program that accepts a string and removes the character at a specified index

## Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## Program:

```
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
```



## Output:
![image](https://github.com/user-attachments/assets/39f6740d-53e3-4760-8a4e-9c4997769b0c)




## Result:
Python program that accepts a string and removes the character at a specified index is successfully executed.

