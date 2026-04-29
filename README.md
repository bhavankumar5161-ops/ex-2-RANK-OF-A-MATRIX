# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Write the matrix
### Step 2: Make leading element of Row 1 as pivot.​
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: Count non-zero rows
  There are 2 non-zero rows
## Program: 
import numpy as np

A = np.array([[3,2,5],
              [1,1,2],
              [3,3,6]])

print(np.linalg.matrix_rank(A))

## Output:
<img width="1549" height="908" alt="Screenshot 2026-04-29 133854" src="https://github.com/user-attachments/assets/81de04c4-0488-46d1-a8f5-c8563a93382b" />
## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

