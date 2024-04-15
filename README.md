# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in function for calculation.
### Step 2:
Prepare the list for each linear equation and assign in np.array()
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: PRAJAN P
#RegisterNumber:212223240121
import numpy as np
matrix=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
eigval,eigvect=np.linalg.eig(matrix)
print("Eigen values are",eigval,"and Eigen Vectors are",eigvect)
```
## Output:
![Screenshot 2024-04-15 212251](https://github.com/PRAJAN-23013995/EIGENVALUES-AND-EIGENVECTORS/assets/150313345/ab636591-561e-4124-9573-01017ce02764)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
