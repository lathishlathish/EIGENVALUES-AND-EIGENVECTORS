# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Step1 :
import numpy as np
## Step 2:
put the given values in the np.array command
## Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
## Step 4:
print the program and get the output

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: LATHISH KANNA.M
#RegisterNumber:21222220073
import numpy as np
A=np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}". format(values,vectors))
```

## Output:
![image](https://user-images.githubusercontent.com/120359170/226881901-40846991-481d-4f2b-858a-d13d196daa69.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
