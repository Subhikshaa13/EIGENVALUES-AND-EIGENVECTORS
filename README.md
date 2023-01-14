# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : To find inverse of a matrix using python programming

###Step 2: Import numpy as np

.###Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue and second is
eigenvector) of the given matrix.


###Step 4: Print result

## Program:
#Program to find the eigen values and eigen vectors
. #Developed by: Subhikshaa M
#RegisterNumber:2200103
import numpy as np
A=np.array([[2,2],[1,3]]) values,
vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors)

## Output:
![4](https://user-images.githubusercontent.com/118787344/212460716-7da5e258-739f-4cb9-b60c-00c2361cef99.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
