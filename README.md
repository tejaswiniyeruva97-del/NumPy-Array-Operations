# NumPy-Array-Operations
## Project Overview
This project demonstrates basic mathematical operations using NumPy arrays in Python. It helps understand vectorized numerical operations using the NumPy library.

## Objective
To create two NumPy arrays and perform the following operations:
- Addition
- Subtraction
- Multiplication
- Division

## Tools and Technologies
- Python
- NumPy
- Jupyter Notebook

## Installation

Install NumPy using pip:

```bash
pip install numpy
```

## Project Code

```python
import numpy as np

# Create two NumPy arrays
arr1 = np.array([10, 20, 30, 40, 50])
arr2 = np.array([2, 4, 5, 8, 10])

# Display arrays
print("First Array:", arr1)
print("Second Array:", arr2)

# Check array shapes
print("Shape of Array 1:", arr1.shape)
print("Shape of Array 2:", arr2.shape)

# Addition
print("Addition:", arr1 + arr2)

# Subtraction
print("Subtraction:", arr1 - arr2)

# Multiplication
print("Multiplication:", arr1 * arr2)

# Division
print("Division:", arr1 / arr2)

# Vectorized operation
print("Vectorized Multiplication:", arr1 * 2)
```

## Expected Output

```text
First Array: [10 20 30 40 50]
Second Array: [ 2  4  5  8 10]
Shape of Array 1: (5,)
Shape of Array 2: (5,)
Addition: [12 24 35 48 60]
Subtraction: [ 8 16 25 32 40]
Multiplication: [ 20  80 150 320 500]
Division: [5. 5. 6. 5. 5.]
Vectorized Multiplication: [ 20  40  60  80 100]
```

## Key Concepts Learned
- Creating NumPy arrays using `np.array()`.
- Checking array dimensions using `shape`.
- Performing element-wise mathematical operations.
- Understanding vectorization.
- Performing numerical computations efficiently.

## What is Vectorization?
Vectorization is the process of performing operations on entire NumPy arrays without using explicit loops. It makes numerical computations easier and more efficient.

## Conclusion
Successfully created two NumPy arrays and performed addition, subtraction, multiplication, and division. Also understood vectorized operations using NumPy.

## Author
AI & ML Track - Daily Project
