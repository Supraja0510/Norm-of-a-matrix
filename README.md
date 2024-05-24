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
![image](https://github.com/Supraja0510/Norm-of-a-matrix/assets/155217478/b979de23-8e83-4cad-9c9a-81b183f18a7e)
![image](https://github.com/Supraja0510/Norm-of-a-matrix/assets/155217478/28e6d8f9-3483-4ec3-8ea7-6aa7ec800436)
![image](https://github.com/Supraja0510/Norm-of-a-matrix/assets/155217478/b71c569c-bdd4-4977-932e-3d11e7dda111)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
