# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using np.linalg.inv(),we can find the inverse of a matrix
### Step 4: End the program

## Program:'''import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np 
A=np.array([[6,2,3],[3,1,1],[10,3,4]])
r=np.linalg.inv(A)
print(r)'''
## Output:
<img width="1339" height="656" alt="{F0870B9D-9C79-4539-9522-CF553D8663FE}" src="https://github.com/user-attachments/assets/a4e441b6-6eb7-4a2c-a185-a9b6f75a67ee" />

<img width="942" height="359" alt="{34699935-88F5-43A5-BC48-0FDA8E86B302}" src="https://github.com/user-attachments/assets/c411dd00-7ced-4911-bc28-2e03b2c72275" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

