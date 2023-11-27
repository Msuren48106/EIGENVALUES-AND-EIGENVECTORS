# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
start the program
### Step 2: 
Assign np.array() in eigen values and eigen vectors.
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
print both the values and vectors,then end the program.
## Program:
#Program to find the eigen values and eigen vectors.
#Developed by: M.suren.
#RegisterNumber: 23005055
import numpy as np
A=[[4,2],[2,4]]
values,vectors=np.linalg.eig(A)
print("Eigen values are",values,"and Eigen Vectors are",vectors)
## Output:

![Screenshot 2023-11-27 203426](https://github.com/Msuren48106/EIGENVALUES-AND-EIGENVECTORS/assets/150503875/008305a4-0a3a-46f7-8acb-7d627c962318)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
