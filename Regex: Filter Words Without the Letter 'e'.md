# Regex in Python: Filter Words Without the Letter 'e'

## Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## Program
```
import re

# Initialize an empty list to store results
l1 = []

# Define a list of words
items = eval(input())

# Iterate through each word in the list
for i in items:
    # Use re.search to check if the word contains 'e'
    if not re.search(r"e", i):
        l1.append(i)

# Print the final filtered list
print("Words without the letter 'e':", l1)


```
## Output
![image](https://github.com/user-attachments/assets/fee79157-48e5-4cbb-8745-ee087c9d7923)



## Result
Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using regular expressions (regex) is successfully executed.
