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
def generate_pascals_triangle(n):
    for i in range(n):
        num = 1
        for j in range(i + 1):
            print(num, end=" ")
            num = num * (i - j) // (j + 1)
        print()
rows = int(input("Enter the number of rows: "))
print("Pascal's Triangle:")
generate_pascals_triangle(rows)
~~~

## Sample Output
<img width="1311" height="342" alt="image" src="https://github.com/user-attachments/assets/60a078ac-d22e-4099-84c3-13cfff9e0899" />

## Result
The code is executed successfully.

