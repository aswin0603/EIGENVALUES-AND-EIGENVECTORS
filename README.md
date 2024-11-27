# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :  Import the numpy module to use the built-in functions for calculation.
### Step 2: Prepare the matrix using np.array() for the calculation.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the Result and End the Program.

## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by: ASWIN B
#RegisterNumber: 24900642

import numpy as np
a = np.array([[2,2],[1,3]])
values,vectors = np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![Record 04](https://github.com/user-attachments/assets/dd14ed2a-8fa4-4c16-af98-b46bc217abc7)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
