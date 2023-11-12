# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import nmpy as np
### Step 2:
Inlitilize a variable 'A' as an array from the np module
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Now print the value

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: PRADEEP.E
#RegisterNumber:23013416
import numpy as np 
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors = np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output: 
![eignen values and eigen vectors png](https://github.com/pradeeprajeswari/EIGENVALUES-AND-EIGENVECTORS/assets/145743112/7141f79e-50cf-4525-91a9-f0c89fcdd2cd)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program

