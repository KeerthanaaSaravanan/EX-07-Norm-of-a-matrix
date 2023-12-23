# EX-07: Norm of a matrix
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
'''
Program to find 1-norm of a matrix.
Developed by: KEERTHANA S
Register Number: 23013398
'''
import numpy as np
array=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: KEERTHANA S
RegisterNumber: 23013398
'''
import numpy as np
array1=([[1,2],[3,4]])
array2=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# Infinity Norm of a Matrix
'''
Program to find infinity of a matrix.
Developed by:KEERTHANA S
Register Number: 23013398
'''
import numpy as np
array1=([[-1, 3],[3, -4],[1, 7]])
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-12-23 150613](https://github.com/KeerthanaaSaravanan/EX-07-Norm-of-a-matrix/assets/145742596/51d68f15-3a9a-4aab-b9fd-47223fedc323)

<br>

### 2-Norm of a Matrix
![Screenshot 2023-12-23 150623](https://github.com/KeerthanaaSaravanan/EX-07-Norm-of-a-matrix/assets/145742596/101ecee5-da67-43d1-8f92-5c1a7f8bbc1c)

<br>

### Infinity Norm of a Matrix
![Screenshot 2023-12-23 150644](https://github.com/KeerthanaaSaravanan/EX-07-Norm-of-a-matrix/assets/145742596/d4aae1df-a9c7-4efd-8e51-910ce55afea1)

<br>


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
