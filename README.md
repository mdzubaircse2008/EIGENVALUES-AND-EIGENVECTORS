# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Mohammed Zubair R 
#RegisterNumber: 212225040252(25017722)
import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
value,vector=np.linalg.eig(a)
print(f"Eigen values are {value} and Eigen Vectors are {vector}")
```
## Output:
<img width="1235" height="343" alt="image" src="https://github.com/user-attachments/assets/3671494d-faa7-4803-b22b-b98fe9c6be3d" />
<img width="1253" height="370" alt="image" src="https://github.com/user-attachments/assets/fdf1e5b4-7327-49d3-9ed0-dad20dcbe831" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
