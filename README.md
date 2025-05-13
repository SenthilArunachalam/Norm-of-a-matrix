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
# Register No: 212224240147
# Developed By: P.Senthil Arunachalam
# 1-Norm of a Matrix

import numpy as np
mat =np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix='{:.2f}'.format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![output 1](https://github.com/user-attachments/assets/ba5a1c90-9d2a-4984-b671-18896f94732c)


### 2-Norm of a Matrix
![output 2](https://github.com/user-attachments/assets/1c0480c5-b4e6-4a9b-921a-ffce4c410853)


### Infinity Norm of a Matrix
![output 3](https://github.com/user-attachments/assets/94b33a86-3bb6-49b2-885a-86ba70ffe66a)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
