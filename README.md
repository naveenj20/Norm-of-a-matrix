# Norm of a matrix
## Aim

To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.

## Equipment’s required:

1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner
   
## Algorithm:

1. Get the input matrix using np.array()   
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
   
## Program:
```
# Register No: 24001290
# Developed By: Naveen Jaisanker
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat, 1)
x="{:.2f}".format(ans)
print(x)


# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat, 2)
x="{:.2f}".format(ans)
print(x)


# Infinity Norm of a Matrix


import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat, np.inf)
x="{:.2f}".format(ans)
print(x)


```
## Output:
### 1-Norm of a Matrix

![Screenshot 2024-12-02 215624](https://github.com/user-attachments/assets/597fe315-20d6-4956-8f60-e4b636e2568b)


### 2-Norm of a Matrix

![Screenshot 2024-12-02 215633](https://github.com/user-attachments/assets/bcf77025-ce2d-47a2-8726-32ac61706d68)


### Infinity Norm of a Matrix

![Screenshot 2024-12-02 215640](https://github.com/user-attachments/assets/7dbb4e66-43ee-48c4-8d00-8808a5d7a002)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
