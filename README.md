# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step 1:

Import the NumPy module to access linear algebra functions.

Step 2:

Create a matrix using np.array() with the desired rows and columns.

Step 3:

Use np.linalg.matrix_rank() to compute the rank of the matrix.

Step 4:

Display the rank using a print statement.
## Program:
```
#Program to find the rank of a matrix.
#Developed by: Saravana Kumar S
#RegisterNumber:212224220090

import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
sol=np.linalg.matrix_rank(A)
print(sol)
```
## Output:
<img width="395" height="215" alt="Screenshot 2025-08-14 094520" src="https://github.com/user-attachments/assets/ae62c4bf-1a77-40ea-aa87-f1a52266341a" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

