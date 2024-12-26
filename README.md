# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in function for calculation 
### Step 2: 
Prepare the lists from each equations and assign in np.aaray()
### Step 3:
Using the np.linalg.solve(),we can find the solutions. 
### Step 4: 
End the program

## Program:
```
#Program to find the inverse of a matrix.
#Developed by:RAGUL K.R 
#RegisterNumber:24900660
import numpy as np
a=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
res=np.linalg.inv(a)
print(res)
```
## Output:
![alt text](1.png)

## Result:

Thus the inverse of given matrix is successfully solved using python program

