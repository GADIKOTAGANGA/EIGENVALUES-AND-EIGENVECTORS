# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : get the input from user
### Step 2: import math and initialise the two values
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: print the values in format

## Program:
#Program to find the eigen values and eigen vectors.
#Developed by:G.GANGA DEVI 
#RegisterNumber:24002379

```import numpy as np
A=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors)
```
## Output:
![Screenshot (144)](https://github.com/user-attachments/assets/f27c3ee8-fd1b-4d2f-855d-d556eb5d5a9a)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
