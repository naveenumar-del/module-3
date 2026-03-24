Regex in Python: Filter Words Without the Letter 'e'

Aim:

To write a Python program that filters out and returns all elements from a list that do not contain the letter 'e', using regular expressions (regex).

Algorithm:

Import the re module.

Initialize an empty list l1 to store results.

Define a list of words:

items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']

Iterate through each word in the list:

Use re.search(r"e", i) to check if the word contains 'e'.

If not, append the word to l1.

Print the final filtered list.

Program:

Add code here

import re

new_list=[]

items=['goal', 'new', 'user', 'sit', 'eat', 'dinner'] 

for i in items:

   if not re.search(r"e",i):
   
      new_list.append(i)
      
print(new_list)

Output

<img width="361" height="130" alt="image" src="https://github.com/user-attachments/assets/c2fbd1c5-f429-4438-bdad-654a5ae4133c" />


Result

Thus,the program has been executed successfully.
