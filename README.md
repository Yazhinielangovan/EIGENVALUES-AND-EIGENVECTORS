## EXPERIMENT NO. : 04 
## DATE : 23.04.2024

# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors.
## Equipment’s required:
1. 	Hardware – PCs.
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner.
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation.
### Step 2: 
Prepare the lists from each equations and assign in np.array().
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program.
## Program:
```
Developed by : YAZHINI E
Register number : 2305002028
import numpy as np
A = np.array([[2,2],[1,3]])
values,vectors = np.linalg.eig(A)
print('The Eigenvalues are {} and Eigenvectors are {}'.format(values,vectors))
```
## Output:
![Screenshot 2024-04-08 102220](https://github.com/Yazhinielangovan/EIGENVALUES-AND-EIGENVECTORS/assets/155508323/cfb6d209-eac4-4f3b-9f86-98969787c9a1)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program.
