# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import the numpy module to use the built-in functions for calculation
### Step 2: 
prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.inv(A),we can find the solutions.
### Step 4: 
End of the program

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: Renita Ireen G
#RegisterNumber:25008430

import numpy as np

# Given matrix
A = np.array([[6, 2, 3],
              [3, 1, 1],
              [10, 3, 4]])

# Calculate inverse
A_inv = np.linalg.inv(A)
print(A_inv)
```
## Output:
<img width="1474" height="797" alt="Screenshot 2025-12-14 173522" src="https://github.com/user-attachments/assets/44d3b4a9-a691-4f20-81f8-c4854e2085b9" />
<img width="1408" height="771" alt="Screenshot 2025-12-14 173538" src="https://github.com/user-attachments/assets/39f811b2-80ac-4091-8848-8396a2276ddc" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

