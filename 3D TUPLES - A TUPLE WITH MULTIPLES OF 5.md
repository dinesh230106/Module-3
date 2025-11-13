# Exp.No:3d  
## TUPLES - A TUPLE WITH MULTIPLES OF 5

---

### AIM  
To write a Python program to create a tuple containing all multiples of 5 up to a given number **N**.

---

### ALGORITHM

1. Begin the program.  
2. Accept an integer `N` from the user.  
3. Use a generator expression inside the `tuple()` function to create a tuple `multiples_of_5` with values starting from `5` up to `N - 1`, stepping by `5`.  
4. Return the tuple `multiples_of_5`.  
5. Print the resulting tuple.  
6. Terminate the program.

---

### PROGRAM

```
# Reg.No: 212223060057
# Name: DINESH KUMAR A
# Program to create a tuple with multiples of 5 up to N

# Get input from the user
N = int(input("Enter the limit: "))

# Create a tuple of multiples of 5
multiples_of_5 = tuple(i for i in range(5, N, 5))

# Display the tuple
print("Tuple containing multiples of 5 up to", N, "is:", multiples_of_5)

```

### OUTPUT
```
Enter the limit: 30
Tuple containing multiples of 5 up to 30 is: (5, 10, 15, 20, 25)

```

### RESULT
Thus, the Python program to create a tuple containing all multiples of 5 up to a given number N was successfully executed and verified.
