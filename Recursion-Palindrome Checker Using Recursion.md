# 🔁 Recursion:Sum of Square of first n Natural Using Recursion in Python

## 🎯 AIM:
To Write a Python program to find the sum of square of a first n Natural Numbers using recursion

---

## 🧠 ALGORITHM:

1. Start
2. Input a number n.
3. Define a recursive function sum_of_squares(n):
         Base case: If n == 0, return 0.
         Recursive case: Return (n * n) + sum_of_squares(n - 1).
4. Call the function with n.
5. Print the result.
6. Stop

---

## 💻 PROGRAM:
def sum_sq_numbers(n):
   
    if(n<=0):
       
        return 0
    
    return((n*n)+sum_sq_numbers(n-1))

n = int(input())

print('Result is',sum_sq_numbers(n))

## OUTPUT
<img width="836" height="274" alt="image" src="https://github.com/user-attachments/assets/90ae7e41-7bbb-4136-a248-35f2085c16c4" />


## RESULT
thus, the program is excuted and verified.

