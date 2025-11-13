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

# Get input string from user
str1 = input("Enter a string: ")

# Define the regex pattern
pattern = r"a{1}b{2,3}"

# Check for match
if re.match(pattern, str1):
    print("Found a match!")
else:
    print("Not matched!")

```
### OUTPUT
```
Enter a string: abb
Found a match!

Enter a string: abbb
Found a match!

Enter a string: ab
Not matched!

```

### RESULT
Thus, the Python program to match a string containing an 'a' followed by two to three 'b' characters using regular expressions was successfully executed and verified
