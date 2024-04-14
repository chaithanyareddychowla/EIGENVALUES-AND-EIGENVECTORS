# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
importing the numpy library
### Step 2: 
define the given matrix A
### Step 3: 
using the np.linalg.eig(),we get two results (first is eigenvalue and second eigenvector) of the given matrix.
### Step 4:
print and end the program

## Program:
```
 import numpy as np
 A=np.array([[2,2],[1,3]])
 values,vectors=np.linalg.eig(A)
 print('The eigenvalues and eigenvectors for the given matrix is\n',values,vectors)
```

## Output:
![image](https://github.com/chaithanyareddychowla/EIGENVALUES-AND-EIGENVECTORS/assets/165985172/cc268195-9bd8-4a49-ae03-014ab721add1)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
