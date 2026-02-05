# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from the given matrix and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: END the progrram

## Program:
~~~
#Program to find the eigen values and eigen vectors.
#Developed by:ABHINAV GURU R
#RegisterNumber:212225040009
import numpy as np
A=np.array([[2,4],[4,2]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
~~~

## Output:

<img width="1287" height="784" alt="Screenshot 2026-02-05 230830" src="https://github.com/user-attachments/assets/be626e56-bf90-4b9d-ad47-05c5d4dcaea1" />
<img width="1315" height="273" alt="Screenshot 2026-02-05 230845" src="https://github.com/user-attachments/assets/086523df-96ca-4d3e-9718-f2a044aa95c6" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
