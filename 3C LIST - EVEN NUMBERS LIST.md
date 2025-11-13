# Exp.No:3c
## LIST - EVEN NUMBERS LIST

---

### AIM  
To write a Python function that accepts a number **N** and creates a list containing all even numbers up to **N**.

---

### ALGORITHM

1. Begin the program.  
2. Accept an integer `a` from the user.  
3. Create an empty list `l`.  
4. Use a `for` loop to iterate through numbers from `1` to `a - 1`:  
   - For each number `i`, check if it is even using `i % 2 == 0`.  
   - If it is even, append `i` to the list `l`.  
5. Print the final list `l` containing all the even numbers.  
6. Terminate the program.

---

### PROGRAM

```
# Reg.No: 212223060057
# Name: DINESH KUMAR A
# Program to create a list of even numbers up to N

# Get input from the user
a = int(input("Enter a number: "))

# Create an empty list
l = []

# Loop through numbers from 1 to a-1
for i in range(1, a):
    if i % 2 == 0:
        l.append(i)

# Display the list of even numbers
print("List of even numbers up to", a, "is:", l)

```

### OUTPUT
```
Enter a number: 10
List of even numbers up to 10 is: [2, 4, 6, 8]

```

### RESULT
Thus, the Python program to create a list of even numbers up to N was successfully executed and verified.
