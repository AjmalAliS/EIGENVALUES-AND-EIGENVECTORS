# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the required library NumPy for matrix operations.
### Step 2: Define the given matrix using np.array().
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Display the eigenvalues and eigenvectors using the print() function.

## Program:

```
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np 
a = np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors = np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:

<img width="1495" height="943" alt="image" src="https://github.com/user-attachments/assets/49c7b92a-898c-46d8-b612-5555bb9b625f" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
