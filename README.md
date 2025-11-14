# NumPy-Matrix-Utility-Tool
CLI tool for:  Generate random matrix  Add, subtract, multiply  Row-wise sum  Transpose  Max/min finder
import numpy as np

A = np.random.randint(1, 50, (3, 3))
B = np.random.randint(1, 50, (3, 3))

print("Matrix A:\n", A)
print("\nMatrix B:\n", B)

print("\nA + B:\n", A + B)
print("\nA * B (element wise):\n", A * B)
print("\nRow-wise sum of A:\n", A.sum(axis=1))
print("\nMax value in A:", A.max())
print("\nTranspose of B:\n", B.T)
