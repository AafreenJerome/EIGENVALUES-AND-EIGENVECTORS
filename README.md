# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the NumPy module using import numpy as np.
### Step 2: Create a NumPy array containing the elements of the given matrix.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the eigenvalues and eigenvectors, and end the program.

## Program:

Program to find the eigen values and eigen vectors.

Developed by: AAFREEN JEROME

RegisterNumber: 26007104

import os

os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])

values,Vectors=np.linalg.eig(A)

print("Eigen values are {} and Eigen Vectors are {}".format(values,Vectors))

## Output:

<img width="1270" height="817" alt="image" src="https://github.com/user-attachments/assets/ee241543-1f1f-4a22-9125-afc5d31bcb09" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
