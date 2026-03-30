# Exp.No:2b  
## FUNCTIONS - PERFECT NUMBER

### AIM  
To write a Python program to check if a number is a Perfect number using the concept of functions.

---

### ALGORITHM

1. Begin the program.  
2. Read the number `n` from the user using `input()`.  
3. Convert the input to an integer.  
4. Define the function `perfectNumber(n)` with the following steps:  
    - Initialize a variable `factor_sum` to 0.  
    - Iterate through all numbers from 1 to `n//2` (as divisors of a number can't be greater than half of it).  
    - If a number `i` divides `n` perfectly (i.e., `n % i == 0`), add `i` to `factor_sum`.  
    - If `factor_sum` is equal to `n`, then print the number is a perfect number. Otherwise, print it's not a perfect number.  
5. Terminate the program.

---

### PROGRAM
```
# Reg.No- 212222060008
# Name- AISHWARYA K
def primeNumber(n):
    if n <= 1:
        print("Given number", n, "is not a Prime Number")
        return
    for i in range(2, n // 2 + 1):
        if n % i == 0:
            print("Given number", n, "is not a Prime Number")
            return
    print("Given number", n, "is a Prime Number")

n = int(input())
primeNumber(n)

```
### OUTPUT
<img width="870" height="204" alt="image" src="https://github.com/user-attachments/assets/9aaf129d-9d4b-4d09-9bde-62b6957b25ab" />

### RESULT
Thus, the Python program to check if a number is a Prime number using the concept of functions has been successfully executed and the output is verified.
