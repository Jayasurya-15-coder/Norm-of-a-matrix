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
# Register No: 212224100026
# Developed By: JAYASURYA B

# 1-Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


# 2-Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


```
## Output:
### 1-Norm of a Matrix

<img width="850" height="863" alt="Screenshot 2025-09-22 090929" src="https://github.com/user-attachments/assets/b7d2652b-689f-48e2-8840-c3659b22b966" />

### 2-Norm of a Matrix

<img width="819" height="942" alt="Screenshot 2025-09-22 090949" src="https://github.com/user-attachments/assets/e6429c53-bdc8-4d8d-9158-e910dd6ba4e1" />


### Infinity Norm of a Matrix

<img width="853" height="937" alt="Screenshot 2025-09-22 091002" src="https://github.com/user-attachments/assets/43e507e4-019e-4ff6-bb07-ab43468134dc" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
