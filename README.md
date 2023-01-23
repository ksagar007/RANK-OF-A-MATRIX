# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array().
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: Finally, print the value of the rank of the matrix.
## Program:
```
#Program to find the rank of a matrix.
#Developed by:K SAGAR KRISHNA
#RegisterNumber:22006940
import numpy as np
a=np.array([[1,2,3],[3,6,9]])
rank=np.linalg.matrix_rank(a)
print(rank)
```
## Output:

![Screenshot from 2023-01-23 23-41-05](https://user-images.githubusercontent.com/121165786/214117708-a1ce64e5-f09a-4abf-b8f6-477c0c9a99d4.png)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

