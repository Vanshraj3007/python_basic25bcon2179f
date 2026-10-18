# Fibonacci Series Generator in Python

## 📌 Overview

This project demonstrates how to generate the Fibonacci series using Python. It uses a `for` loop to print the first `n` terms of the sequence, where each term is the sum of the two preceding terms.

## 🚀 Features

- Simple and beginner-friendly Python code.
- Generates the Fibonacci sequence iteratively.
- Demonstrates loops, variables, and arithmetic operations.
- Allows easy modification of the number of terms.

## 🛠️ Technologies Used

- **Programming Language:** Python 3
- **Platform:** Google Colab / Python IDE

## 📂 Code

```python
n = 10
a = 0
b = 1

for i in range(n):
    print(a, end=" ")
    next = a + b
    a = b
    b = next
```

## 🧠 How It Works

1. **Initialize the number of terms:** Set `n = 10` to generate the first ten terms.
2. **Initialize the first two terms:** Set `a = 0` and `b = 1`.
3. **Iterate using a loop:** The `for` loop executes `n` times.
4. **Print the current term:** Print the value of `a`.
5. **Calculate the next term:** Add `a` and `b` and store the result in `next`.
6. **Update the variables:** Assign `b` to `a` and `next` to `b` to continue the sequence.

## ▶️ Example Output

```text
0 1 1 2 3 5 8 13 21 34
```

## 📖 Mathematical Concept

The Fibonacci series is a sequence in which each number is the sum of the two preceding numbers, starting with `0` and `1`.

The sequence begins as follows:

\[
0, 1, 1, 2, 3, 5, 8, 13, 21, 34, \ldots
\]

The recurrence relation is:

\[
F(n) = F(n-1) + F(n-2)
\]

with initial terms:

\[
F(0) = 0,\quad F(1) = 1
\]

## ⚙️ How to Run

1. Clone or download this repository.
2. Open the Python file in Google Colab or any Python IDE.
3. Run the program.
4. Change the value of `n` to generate a different number of terms.

## 🔮 Possible Improvements

- Accept the number of terms as user input.
- Validate input to ensure the number of terms is non-negative.
- Implement the Fibonacci series using recursion.
- Calculate the time complexity of different implementations.

## ⏱️ Complexity Analysis

- **Time Complexity:** \(O(n)\), because the loop runs `n` times.
- **Space Complexity:** \(O(1)\), because only a constant number of variables are used.

## 👨‍💻 Author

**Vanshraj Singh**

## 📄 License

This project is intended for educational purposes and for learning fundamental Python programming concepts.
