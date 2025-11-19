# Exp.No:3e
## SEB - STRING SLICING

---

### AIM  
To write a Python function that accepts a string and forms a new string by reversing the characters from the **4th position to the 10th position** with **alternate characters**, and then prints the new string.

---

### ALGORITHM

1. Begin the program.  
2. Accept a string as input.  
3. Take a slice of the input string from index **2** to **10** (Python uses 0-based indexing, so index 2 refers to the 3rd character, i.e., the 4th character in natural terms).  
4. Reverse the sliced substring.  
5. Extract every second character from the reversed substring using slicing (`[::2]`).  
6. Print the final processed string.  
7. Terminate the program.

---

### PROGRAM

```
# Reg.No: 212223060057
# Name: DINESH KUMAR A
# Program to perform string slicing and create a new string

def slice(x):
    print(f"The reversed string is '{x[9:1:-2]}'")

```

### OUTPUT
<img width="1031" height="247" alt="image" src="https://github.com/user-attachments/assets/1035bd0f-796c-49f5-854f-8c70733adbb1" />


### RESULT
Thus, the Python program to perform string slicing and reverse the characters from the 4th to 10th position with alternate characters was successfully executed and verified.
