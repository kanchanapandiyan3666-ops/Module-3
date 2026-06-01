## List Operations in Python: Sum of List Items
## Aim
To write a Python program that calculates the sum of all elements in a list.

## Algorithm
Define a list of numbers.
Use Python’s built-in sum() function to calculate the total.
Print the result.
## Program
```
items=[153,147,124,102]
print(sum(items))
```
## Output
<img width="1199" height="195" alt="Screenshot 2026-06-01 174024" src="https://github.com/user-attachments/assets/d59c0f48-b2ce-4105-8cd8-3a22b68c9889" />
## Result
Thus ,the program has been executed successfully.

## Regex in Python: Filter Words Without the Letter 'e'
## Aim
To write a Python program that filters out and returns all elements from a list that do not contain the letter 'e', using regular expressions (regex).

## Algorithm
Import the re module.
Initialize an empty list l1 to store results.
Define a list of words:
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
Iterate through each word in the list:
Use re.search(r"e", i) to check if the word contains 'e'.
If not, append the word to l1.
Print the final filtered list.
## Program
```
import re
l1 = []
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
for i in items:
    if not re.search(r"e", i):
        l1.append(i)

print("Words without 'e':", l1)
```
## Output
<img width="1445" height="441" alt="Screenshot 2026-06-01 174505" src="https://github.com/user-attachments/assets/2bc3102e-2db9-4c2f-b681-c0d666e110ca" />
## Result
Thus , the program has been executed successfully.

## Strings-Remove Nth Index Character from a String
## Aim
To write a Python program that accepts a string and removes the character at a specified index.

## Algorithm
Define a function named remove that takes the input string as an argument.
Read the index n from the user input.
Initialize an empty string a to store the new string.
Iterate over each index of the string using a for loop.
Check if the current index i is not equal to n.
If i != n, append the character at index i to string a.
After the loop, return the modified string a.
Print the final result.
## Program
```
s = input("Enter a string: ")
n = int(input("Enter the index to remove: "))
if 0 <= n < len(s):
    result = s[:n] + s[n+1:]
    print("String after removing character:", result)
else:
    print("Invalid index")
```
## Output
<img width="1447" height="383" alt="Screenshot 2026-06-01 175418" src="https://github.com/user-attachments/assets/7e4881d1-566b-41ce-be78-01317f8eb11b" />

## Result
Thus , the program has been executed successfully.

## Strings-Palindrome Check in Python (Without Built-in Functions)
## Aim
To write a Python program to check whether the string "google" is a palindrome or not, without using built-in palindrome checking functions.

## Algorithm
Assign the string "google" to a variable.
Reverse the string manually using slicing ([::-1]).
Compare the original string with the reversed string.
If they are equal, print that the string is a palindrome.
Otherwise, print that it is not a palindrome.
Execute the program.
## Program
```
string = input()
reverse = ""
for i in string:
    reverse = i + reverse
if string == reverse:
    print("Palindrome")
else:
    print("Not a Palindrome")
```
## Output
<img width="1207" height="347" alt="Screenshot 2026-06-01 175643" src="https://github.com/user-attachments/assets/19039cfb-7d88-4ab8-b2e1-1ff28e228c32" />

## Result
Thus , the program has been executed successfully.

## Tuple in Python: Check Element Existence
## Aim
To write a Python program that checks if the element 'n' and the element 8 exist within a given tuple.

## Algorithm
Define a tuple x with some letters and numbers.
Use the in operator to check if the string 'n' exists within the tuple.
Use the in operator to check if the integer 8 exists within the tuple.
Print the results.
## Program
```
numbers = (10, 20, 30, 40, 50)
item = int(input())
if item in numbers:
    print("Element exists in the tuple")
else:
    print("Element does not exist in the tuple")
```
## Output
<img width="1260" height="275" alt="Screenshot 2026-06-01 180056" src="https://github.com/user-attachments/assets/fcb56419-d04f-4a0e-adfb-4c9f4b47a4e8" />

## Result
Thus , the program has been executed successfully.

