# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation

### Step 2:
Prepare the lists from each linear equations and assign in np.array()

### Step 3:
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.

### Step 4:
End the program

## Program:
```python
#Program to find the rank of a matrix.
#Developed by: MOHAMED AZEEM N
#RegisterNumber:22007405
import numpy as np 
A=np.array([[1,2,3],[3,6,9]])
B=np.linalg.matrix_rank(A)
print(B)
```
## Output:

![rank](https://user-images.githubusercontent.com/121040764/210395516-428b48de-f7da-4ab3-863e-9a25ef7607d0.png)


## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

