## Date:
# Exp-04 EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Step 1: get the input from user
## Step 2: import math and initialise the two values
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
## Step 4:print the values in format

## Program:
```
import numpy as np
matrix = np.array([[4, 2], [2, 4]])
eigenvalues, eigenvectors = np.linalg.eig(matrix)
print(f"Eigen values are {eigenvalues} and Eigen Vectors are {eigenvectors}")
```
## Output:
![Screenshot 2024-09-24 223105](https://github.com/user-attachments/assets/cdf11efa-b28d-4cee-ae5a-b9521e20f3cf)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
