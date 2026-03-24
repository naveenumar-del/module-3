Strings-Remove Nth Index Character from a String

Aim:

To write a Python program that accepts a string and removes the character at a specified index.

Algorithm:

Define a function named remove that takes the input string as an argument.

Read the index n from the user input.

Initialize an empty string a to store the new string.

Iterate over each index of the string using a for loop.

Check if the current index i is not equal to n.

If i != n, append the character at index i to string a.

After the loop, return the modified string a.

Print the final result.

Program:

Add Code Here

def remove(s):

    n = int(input())
    
    a = ""
    
    for i in range(len(s)):
    
        if i != n:
        
            a += s[i]
            
    return a

s = input()

print(remove(s))

Output

<img width="641" height="237" alt="image" src="https://github.com/user-attachments/assets/43f91b8b-1db1-457e-9389-4ff9d98b7371" />


Result:

Thus,the program has been executed successfully.
