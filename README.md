# Square Root Finder using Bisection Method

This is a simple Python program that finds the square root of a number using the **bisection method**.

## 📌 How It Works

The bisection method is a root-finding technique that repeatedly narrows the interval where the square root lies. The process continues until the result is accurate within a specified tolerance.

## ✅ Features

- Works for any non-negative number
- Adjustable tolerance and iteration limit
- Handles edge cases like 0 and 1
- Raises error for negative inputs

## 📄 Example

```python
square_root_bisection(16)
# Output: The square root of 16 is approximately 4.0
```
🔧 Function Parameters

square_target: The number you want the square root of

tolerance: Precision of the result (default is 1e-7)

max_iterations: Safety limit for iterations (default is 100)

📁 File
main.py: Contains the full implementation

🧠 License
This project is open-source and free to use.
