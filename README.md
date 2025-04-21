
# INVERSE OF A MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
```
step1: Import the numpy module to use the built-in functions for calculation
step2: Prepare the lists from the matrix and assign in np.array()
step3: Use the np.linalg.inv() fun
step4: End the program.
```

## Program:
```
Program developed by: Iniya E
Reg no: 212224230096

import numpy as np
matrix = np.array([[6, 2, 3],
                   [3, 1, 1],
                   [10, 3, 4]])


determinant = np.linalg.det(matrix)

inverse_matrix = np.linalg.inv(matrix)
print(inverse_matrix)
```

## Output:

![Screenshot 2025-04-21 101401](https://github.com/user-attachments/assets/f0c79cf7-bed3-442e-b9d7-833d8268d50e)

## Result:
Thus the inverse of given matrix is successfully solved using python program

