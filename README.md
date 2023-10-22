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
# Register No:Surothaaman R
# Developed By:23008504
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
print("{:.2f}".format(ans))




# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: SUROTHAAMAN R
RegisterNumber: 23008504
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
print("{:.2f}".format(ans))




# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))





```
## Output:
### 1-Norm of a Matrix
![Screenshot (34)](https://github.com/surothaaman/Norm-of-a-matrix/assets/133313653/1802a039-adca-4311-bb37-66138eeb8553)


### 2-Norm of a Matrix
![Screenshot (35)](https://github.com/surothaaman/Norm-of-a-matrix/assets/133313653/75c693d8-4b03-4c2e-bca6-2f4f00bbcb44)


### Infinity Norm of a Matrix
![Screenshot (36)](https://github.com/surothaaman/Norm-of-a-matrix/assets/133313653/e9bb9003-8ffc-4d5e-9219-2eda784a46c0)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
