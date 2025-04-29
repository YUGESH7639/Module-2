# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
~~~
import math

def pascal_triangle(rows):
    for n in range(rows):
        print(" " * (rows - n - 1), end="")
        
        for k in range(n + 1):
            value = math.comb(n, k)
            print(value, end=" ")
        print() 
num_rows = int(input())
pascal_triangle(num_rows)

~~~
## Sample Output
![Screenshot (181)](https://github.com/user-attachments/assets/9bb38f3d-235d-4497-8f25-3be35a63f722)

## Result
Therefore,the given python program is successfully verified
