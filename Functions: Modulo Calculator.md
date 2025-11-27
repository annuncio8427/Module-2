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

def result(a, b):
    print("Modulo =", a % b)

x = int(input("Enter first value: "))
y = int(input("Enter second value: "))

result(x, y)


## Output

Enter first value: 10
Enter second value: 3
Modulo = 1

## Result
Thus, the Python program successfully performs the modulo operation using a user-defined function.
