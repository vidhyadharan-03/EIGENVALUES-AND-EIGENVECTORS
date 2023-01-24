# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Importing numpy library
### Step 2: 
Giving input as matrix using array
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Printing the eigen values and eigen vectors using 
print statement

## Program:
~~~py
#Program to find the eigen values and eigen vectors.
#Developed by: R.Vidhyadharan
#RegisterNumber: 22008663
import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
value,vector=np.linalg.eig(a)
print(f'Eigen values are {value} and Eigen Vectors are {vector}')
~~~

## Output:
![eigen values expected](/Eigen%20value.png)
![eigen values got](/Eigen%20values%202.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
