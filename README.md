# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import numpy as np.
### Step 2: Assign np.array() in eigen values and eigen vectors.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print both the values and vectors, then end the program.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: N.Kishore
#RegisterNumber: 212222240049
import numpy as np
A=np.array([[2,2],[1,3]])
evalues,evector=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(evalues,evector))
```

## Output:
![Screenshot 2023-05-09 154732](https://github.com/nkishore2210/EIGENVALUES-AND-EIGENVECTORS/assets/118707090/7816f95c-5080-4a4f-8796-2e2ea2927bb1)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
