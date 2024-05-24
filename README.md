# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
```
1. Get the input matrix using np.array()   
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
```
## Program:
```
Register No:2305002026
Developed By: Supraja B
1-Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

2-Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np. linalg.norm(mat, 2)
Norm_of_matrix = "{:.2f}".format (ans)
print(Norm_of_matrix)

Infinity Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)




```
## Output:
![image](https://github.com/Supraja0510/Norm-of-a-matrix/assets/155217478/85cba108-e9c7-4a53-872a-143211582e32)
![image](https://github.com/Supraja0510/Norm-of-a-matrix/assets/155217478/dbfc183e-632c-4eb4-b8ac-c1e4ef9d673c)
![image](https://github.com/Supraja0510/Norm-of-a-matrix/assets/155217478/fee515cc-f272-40bb-9f1a-f035f26cc661)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
