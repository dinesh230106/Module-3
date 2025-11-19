# Exp.No:3b  
## REGEX - PATTERN MATCHING USING REGEX

---

### AIM  
To write a Python program that matches a string containing an `'a'` followed by **two to three `'b'` characters** using regular expressions.

---

### ALGORITHM

1. Begin the program.  
2. Accept a string `str1` from the user.  
3. Define the regular expression pattern as `r"[a]+b{2,3}"`.  
4. Use the `re.match()` function to check if the string `str1` matches the pattern.  
5. If a match is found, print `"Found a match!"`.  
6. If no match is found, print `"Not matched!"`.  
7. Terminate the program.

---

### PROGRAM

```
# Reg.No: 212223060057
# Name: DINESH KUMAR A
# Program to match a string containing 'a' followed by two to three 'b's

import re
str=input()
pattern='^[a(b*)]+$'
x=re.search(pattern,str)
if x:
    print("Found a match!")
else:
    print("Not matched!")

```
### OUTPUT
<img width="638" height="309" alt="image" src="https://github.com/user-attachments/assets/d93e2594-3829-45bd-bb2e-5407242edefa" />


### RESULT
Thus, the Python program to match a string containing an 'a' followed by two to three 'b' characters using regular expressions was successfully executed and verified
