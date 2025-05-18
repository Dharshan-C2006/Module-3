# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
```python
a=eval(input())
s=0
for i in a:
    if i%10==2:
        s+=i
print(f"Sum= {s}")
```
## Output

![442899577-17c49830-c1a2-4847-8841-ab1ebc92f337](https://github.com/user-attachments/assets/834b612d-de20-47e4-aba2-54a52c7e3913)



## Result

The program successfully calculates and prints the sum of all elements in the list using the built-in sum() function.


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
```python
import re
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
words_with_e = [word for word in items if re.search(r"e", word)]
print(words_with_e)

```
## Output
![442900402-bbcf0204-6f57-4d47-a0ad-f1675988233c](https://github.com/user-attachments/assets/38cfcf36-e069-482a-a437-f61de7307401)



## Result

The program successfully filters out and returns all elements from the list that do not contain the letter 'e' using regular expressions.


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
```python
n=int(input())
def remove(a):
    for i in range(0,len(a)):
        if(i!=n):
            print(a[i],end='')
```

## Output

![442902405-2f843a57-93b2-4690-b19e-86b3c02f2d80](https://github.com/user-attachments/assets/ebc69bea-bd6f-49b5-93e5-b30f0fd60c81)



## Result

The program successfully removes the character at the specified index from the input string and returns the modified result.

# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
```python
string = input()
reversed_string = string[::-1]
if string == reversed_string:
    print("The string is a palindrome.")
else:
    print("The string is not a palindrome.")

```

## Output

![442903684-e8584434-8e75-4662-ada4-4d10d622f322](https://github.com/user-attachments/assets/d10f4657-2b86-4fd3-8cc6-eaa2ddd9ce5e)



## Result

The program successfully checks if the string "google" is a palindrome by reversing it and comparing it to the original string.


# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
```python
x=eval(input())
print('52' in x)
print('12' in x)
```

## Output


![442905151-f7900f1e-e734-4e3c-9976-9c86d4a8b79a](https://github.com/user-attachments/assets/2c36abd9-7350-449c-bf9d-d62989645a32)


## Result

The program successfully checks for the existence of both 'n' and 8 in the tuple and prints the results.
