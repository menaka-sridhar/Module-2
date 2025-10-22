# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program
~~~
def find_modulo(a, b):
    return a % b
num1 = int(input("Enter first number: "))
num2 = int(input("Enter second number: "))

result = find_modulo(num1, num2)
print("The modulo of", num1, "and", num2, "is:", result)

~~~
## Output
<img width="1407" height="273" alt="image" src="https://github.com/user-attachments/assets/cdf34f01-1f2f-4448-af8c-0315aaa75eaa" />

## Result
The code is executed successfully.
