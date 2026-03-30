# Exp.No:2d
## LOOPING PATTERNS - PRINTING PATTERN

---

### AIM  
To write a Python program to print a triangular star pattern using loops.

---

### ALGORITHM

1. Begin the program.  
2. Read the integer `n` from the user using `input()`. This will determine the number of rows in the pattern.  
3. Initialize a variable `i = 0`. This will help adjust the spacing before the stars.  
4. Loop through rows from `0` to `n - 1`:  
   - For each row, calculate the number of spaces to print using the formula: `((n - rows - 1) * 2) + i`.  
   - Print the calculated number of spaces using `print(" ", end="")`.  
   - Increment `i` by 1 after each row.  
   - Print stars using a nested loop: the number of stars in each row is `rows + 1`, printed using `print("*", end="  ")`.  
   - Print a newline after each row using `print("")` to move to the next line.  
5. Terminate the program.

---

### PROGRAM
```
# Reg.No- 212222060008
# Name- AISHWARYA K
n = int(input())
for i in range(1, n + 1):
    for j in range(1, n + 1):
        print(max(i, j), end=" ")
    print()

```

### OUTPUT
<img width="560" height="567" alt="image" src="https://github.com/user-attachments/assets/44711be7-6397-43ab-98f6-39af1ac02777" />

### RESULT
Thus, the Python program to print a square pattern of numbers using loops has been successfully executed and the output is verified.
