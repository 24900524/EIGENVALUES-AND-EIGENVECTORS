# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step 1: get the input from user
Step 2: import math and initialise the two values
Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue andsecond is eigenvector) of the given matrix.
Step 4:print the values in format

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Dharshini S N
#RegisterNumber:212224230062
import numpy as np
A=np.array([[2,2],[1,3]])
eig_values,eig_vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(eig_values,eig_vectors))
```
## Output:

<img width="1919" height="1139" alt="image" src="https://github.com/user-attachments/assets/d39a54cd-9ce6-4670-89c6-6895f1be44a5" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program.
