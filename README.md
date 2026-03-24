# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End  the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by :Pradeep.M
#RegisterNumber:212225220071

import numpy as np
A=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(A)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")
```
## Output:
<img width="930" height="153" alt="Screenshot 2026-03-24 101638" src="https://github.com/user-attachments/assets/f5a6b0fc-7248-4ab3-9733-0f4e0bf693b8" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
