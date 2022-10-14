#EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import numpy
### Step 2:
Assign value for array
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
print the eigen values and eigen vectors

## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by: sharangini
#RegisterNumber:22003363
import numpy as np
A=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(A)
print('Eigen values are {} and Eigen Vectors are {}'.format(values,vectors))
```

## Output:
![Screenshot from 2022-09-19 20-38-13](https://user-images.githubusercontent.com/113497340/191050527-4421b067-2746-4f58-ab39-1345162ebac9.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
