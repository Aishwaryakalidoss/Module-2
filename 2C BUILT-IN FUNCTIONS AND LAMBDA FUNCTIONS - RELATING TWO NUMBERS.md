# Exp.No:2c
## BUILT-IN FUNCTIONS AND LAMBDA FUNCTIONS - RELATING TWO NUMBERS

---

### AIM  
To write a Python program to check the relation between two numbers — whether one number is greater than, equal to, or lesser than another — using a lambda function.

---

### ALGORITHM

1. Begin the program.  
2. Use `eval()` to get two numbers (`num1` and `num2`) from the user.  
3. Define a lambda function `max` that takes two arguments `x` and `y`.  
4. The lambda function compares the numbers and prints:
   - If `x > y`, then it prints: "`num2` is smaller than `num1`".
   - Otherwise, it prints: "`num1` is smaller than `num2`".
5. Call the lambda function by passing `num1` and `num2` as arguments.  
6. Terminate the program.

---

### PROGRAM

```
# Reg.No- 212222060008
# Name- AISHWARYA K
x = int(input())
y = int(input())
z = int(input())
expression = lambda x, y, z: (x + 10) + (y + 2) * z
print(expression(x, y, z))
```

### OUTPUT

<img width="365" height="276" alt="image" src="https://github.com/user-attachments/assets/8807e29f-0baa-4447-a016-f56be7c11ceb" />


### RESULT
Thus, the Python program to calculate the value of the expression (x + 10) + (y + 2) * z using a lambda function has been successfully executed and the output is verified.

