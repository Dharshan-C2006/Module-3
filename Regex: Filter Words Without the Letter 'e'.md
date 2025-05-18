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
