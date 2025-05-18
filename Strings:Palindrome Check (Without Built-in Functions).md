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
