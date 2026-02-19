# NumPy Array Basics

This project demonstrates fundamental operations using the NumPy library in Python.  
It covers array creation, properties, mathematical operations, and statistical functions.

---

## Overview

The script includes examples of:

- Creating 1-D and 2-D arrays
- Checking array shape and dimensions
- Inspecting data types and memory usage
- Creating special matrices (zeros and identity)
- Generating number sequences
- Performing arithmetic operations
- Calculating statistical values (mean, median, min, max, sum)

---

## Requirements

Make sure you have Python installed (3.x recommended).

Install NumPy using:

```bash
pip install numpy
```

---

## How to Run

Save the script as:

```bash
numpy_basics.py
```

Then run:

```bash
python numpy_basics.py
```

---

## Concepts Covered

### 1. Array Creation

- `np.array()` for creating arrays
- 1-D Array
- 2-D Array

### 2. Array Properties

- `shape` → Dimensions of array  
- `ndim` → Number of dimensions  
- `dtype` → Data type  
- `itemsize` → Size of each element (in bytes)

### 3. Special Matrices

- `np.zeros((3,3))` → 3×3 zero matrix  
- `np.eye(3)` → Identity matrix  

### 4. Number Sequences

- `np.arange(start, stop, step)`
- `np.linspace(start, stop, num_values)`

### 5. Arithmetic Operations

- Adding a scalar to an array  
- Multiplying arrays by a scalar  

### 6. Statistical Functions

- `np.mean()` → Average  
- `np.median()` → Middle value  
- `np.max()` → Maximum  
- `np.min()` → Minimum  
- `np.sum()` → Total sum  

---

## Example Output

```
a = [  1  10  20  30  40  50 500]
b =
[[1 2 3]
 [4 5 6]]

a.shape = (7,)
b.shape = (2, 3)

a.ndim = 1
b.ndim = 2

a.dtype = int64
b.dtype = int64

a.itemsize = 8
b.itemsize = 8

zeros matrix:
 [[0. 0. 0.]
 [0. 0. 0.]
 [0. 0. 0.]]

identity matrix:
 [[1. 0. 0.]
 [0. 1. 0.]
 [0. 0. 1.]]

arange(1,10,2) = [1 3 5 7 9]

linspace(0,10,5) = [ 0.   2.5  5.   7.5 10. ]

Adding with the number 5 in matrix
 [  6  15  25  35  45  55 505]
Multiplying with the number 2 in matrix
 [[ 2  4  6]
 [ 8 10 12]]

The value of the mean   is 93.0
The value of the median is
 30.0

Maximum value: 500

Minimum value: 1

Sum of all values: 651
```


---

## Author

Bhomik v Keshi 

