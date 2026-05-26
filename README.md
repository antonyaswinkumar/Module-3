## Python Programming Module 3
## Name: Antony Aswin Kumar L
## Register Number: 212225040024

## Ex:1  List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program:

```
l=[23,45,67,90,34]

s=sum(l)
print("Sum is",s)
```

## Output:

<img width="285" height="150" alt="Screenshot 2026-05-26 192343" src="https://github.com/user-attachments/assets/3a0ffd09-e9fc-413d-ac0b-c91a4422b48c" />

## Result:
Thus the Python program that calculates the **sum of all elements** in a list is executed successfully.



## Ex:2  Regex in Python: Filter Words Without the Letter 'e'

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

## 🧾 Program:

```
import re
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']

l=[]
for i in items:
    if not re.search(r"e",i):
        l.append(i)

print(l)
```

## Output:

<img width="585" height="255" alt="image" src="https://github.com/user-attachments/assets/9dea9778-4321-482d-b091-3ddf80f8514e" />


## Result:
Thus the Python program that filters out and returns all elements from a list **that do not contain the letter 'e'**, using **regular expressions (regex)** is executed successfully.



## Ex:3  Strings-Remove Nth Index Character from a String

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

## 💻 Program:

```
def remove(s, n):
    a = ""  
    
    for i in range(len(s)):
        if i != n:
            a += s[i]
    
    return a
```

string = input("Enter a string: ")
n = int(input("Enter the index to remove: "))


result = remove(string, n)
print("Result:", result)

## Output:

<img width="656" height="461" alt="image" src="https://github.com/user-attachments/assets/b08deda3-c759-4aed-9c75-31795a7b8826" />


## Result:
Thus the Python program that accepts a string and removes the character at a specified index is executed successfully.


## Ex:4  Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program:

```
s="google"

if s==s[::-1]:
    print("The string is a PALINDROME")
else:
    print("The string is NOT PALINDROME")
```

## Output:

<img width="518" height="189" alt="image" src="https://github.com/user-attachments/assets/95fec1e5-8c84-4029-9bd9-28066b5420b6" />

## Result:
Thus the Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.


## Ex:5  Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program:

```
x=(4,'a',0,'n',9,6,'u','a')

check_n = 'n' in x
check_8 = 8 in x

print("Checking if 'n' is present in the tuple:")
print(check_n)

print("Checking if 8 is present in the tuple:")
print(check_8)
```

## Output:

<img width="617" height="338" alt="image" src="https://github.com/user-attachments/assets/d2f1145a-20a7-40c0-bbcd-53cc363fc027" />
