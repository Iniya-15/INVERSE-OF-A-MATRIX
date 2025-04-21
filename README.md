# Name: Iniya E
# Reg.No: 212224230096
# INVERSE OF A MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## step1: Import the numpy module to use the built-in functions for calculation
## step2: Prepare the lists from the matrix and assign in np.array()
## step3: Use the np.linalg.inv() fun
## step4: End the program.
## Program:
```
import numpy as np


matrix = np.array([[6, 2, 3],
                   [3, 1, 1],
                   [10, 3, 4]])


determinant = np.linalg.det(matrix)

inverse_matrix = np.linalg.inv(matrix)
print(inverse_matrix)
```

## Output:
![Screenshot 2025-03-02 231423](https://github.com/user-attachments/assets/b99a7435-ab37-4804-bcde-4a1af9fccd5a)

## Result:
Thus the inverse of given matrix is successfully solved using python program

