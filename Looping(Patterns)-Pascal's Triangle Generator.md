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
```
n=int(input())
for r in range(0,n):
    val=1
    for sp in range (1,(n-r)):
        print(" ",end="")
    for c in range(0,r+1):
        print(val , end=" ")
        val=val*(r-c)//(c+1)
    print()
```

## Sample Output
<img width="606" height="513" alt="530459199-1269fcf1-bbfe-4441-a39b-e1b3b525259f" src="https://github.com/user-attachments/assets/fa5bf993-929c-4d0d-a1ce-3c9e8d8f0d90" />



## Result
Thus, the program has been successfully executed
