
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
# Register No: 23013347
# Developed By: kamaleshawr kv
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
![image](https://github.com/Kamaleshwa/Norm-of-a-matrix/assets/144980199/8902b3aa-9c32-4640-86f1-3676930dfd12)

### 2-Norm of a Matrix
![image](https://github.com/Kamaleshwa/Norm-of-a-matrix/assets/144980199/031294c3-5980-45e5-bb44-b4516f7b780e)


## Infinity Norm of a Matrix
![image](https://github.com/Kamaleshwa/Norm-of-a-matrix/assets/144980199/73e4d876-9c8b-45ba-8bc9-49933a0eafe2)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
