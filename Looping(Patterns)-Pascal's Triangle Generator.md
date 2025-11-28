# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.


## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.



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
```python
def fact(n):
    if n == 0:
        return 1
    return n * fact(n - 1)

rows = int(input("Enter number of rows: "))

for i in range(rows):
    print(" " * (rows - i), end="")
    for j in range(i + 1):
        val = fact(i) // (fact(j) * fact(i - j))
        print(val, end=" ")
    print()
```

## Sample Output
```python
Enter number of rows: 5
      1 
     1 1 
    1 2 1 
   1 3 3 1 
  1 4 6 4 1
```
## Result
Thus, the Python program successfully generates Pascal's Triangle using loops and factorial-based binomial coefficient calculation.
