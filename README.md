# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Start the program
### Step 2: Get input from user
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: sriram R 
#RegisterNumber:23004952

import numpy as np
a= np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {} ". format(values,vectors))
```
## Output:
![output](https://github.com/Rsriram13/EIGENVALUES-AND-EIGENVECTORS/assets/145742823/e74dacdd-37a9-4d78-aeb4-4cdc3c6fd7f3)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
