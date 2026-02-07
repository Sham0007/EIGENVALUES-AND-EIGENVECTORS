# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : First IMport Numpy Using import
### Step 2: Then Convert The List of Matrix Into Array using np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Lastly print the eigen values and eigen vectors.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: SARAVANAN SHAM PRAKASH
#RegisterNumber: 212224230254

import numpy as np
A=np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(A)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")

```
## Output:
<img width="1447" height="995" alt="image" src="https://github.com/user-attachments/assets/a6d565f8-3864-48a7-b97a-15e0ae9d4f6d" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
