# Chapter 2: Introduction to Python for Matrix Manipulation

In this chapter, we will introduce Python as a powerful tool for matrix manipulation. We will use the NumPy library, a popular Python library, for numerical computations.

## Python and NumPy

Python is a high-level programming language known for its clear syntax and readability. NumPy (Numerical Python) is a Python library that supports large, multi-dimensional arrays and matrices and a collection of mathematical functions to operate on these arrays.

To use NumPy, we first need to import it:

```Python
import numpy as np
# create a 2x2 matrix
matrix = np.array([[1, 2], [3, 4]])
print(matrix)
```

## Matrix Creation

You can create a matrix in NumPy using the array function:

```Python
# create a 2x2 matrix
matrix = np.array([[1, 2], [3, 4]])
print(matrix)
```

## Adding Matrices

To add two matrices, we simply use the + operator. Let's say we have two matrices, A and B, where:

$$
A=\left[\begin{array}{ll}
1 & 2 \\
3 & 4
\end{array}\right]
$$

And

$$
B=\left[\begin{array}{ll}
5 & 6 \\
7 & 8
\end{array}\right]
$$

The sum of these matrices, C = A + B, is:

$$
\begin{aligned}
C & =\left[\begin{array}{ll}
1+5 & 2+6 \\
3+7 & 4+8
\end{array}\right] \\
& =\left[\begin{array}{ll}
6 & 8 \\
10 & 12
\end{array}\right]
\end{aligned}
$$


In Python, you can add these matrices as follows:

```Python
A = np.array([[1, 2], [3, 4]])
B = np.array([[5, 6], [7, 8]])
C = A + B
print(C)
```

