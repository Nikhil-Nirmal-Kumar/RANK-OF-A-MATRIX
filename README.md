# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: End the program

## Program:
```
#Program to find the rank of a matrix.
#Developed by: Nikhil Nirmal Kumar
#RegisterNumber: 212225230201
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
rank=np.linalg.matrix_rank(A)
print(rank)
```

## Output:
<img width="1158" height="843" alt="image" src="https://github.com/user-attachments/assets/5edd1109-c957-43e9-9074-61ee31b36a99" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

