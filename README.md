# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No:
# Developed By:
# 1-Norm of a Matrix

import numpy as np
A=np.array(eval(input()))
norm1=np.linalg.norm(A,1)
print(f"{norm1:.2f}")



# 2-Norm of a Matrix

import numpy as np
A=np.array(eval(input()))
norm2=np.linalg.norm(A,2)
print(f"{norm2:.2f}")


# Infinity Norm of a Matrix

import numpy as np
A=np.array(eval(input()))
res=np.linalg.norm(A,np.inf)
print(f"{res:.2f}")



```
## Output:
### 1-Norm of a Matrix

<img width="1599" height="899" alt="image" src="https://github.com/user-attachments/assets/ce89e98f-6713-4dd6-87df-5e9114af9622" />


### 2-Norm of a Matrix

<img width="1599" height="899" alt="image" src="https://github.com/user-attachments/assets/f7bbaad7-64d7-41e9-8bbb-dec7fa0368df" />

### Infinity Norm of a Matrix


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
