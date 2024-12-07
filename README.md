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
'''
Developed by: ABINAYA.A
RegisterNumber: 24900474
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)




# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: ABINAYA.A
RegisterNumber: 24900474
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)





# Infinity Norm of a Matrix
'''
Developed by: ABINAYA.A
RegisteredNumber: 24900474
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)





```
## Output:
### 1-Norm of a Matrix


![exp 07 iii](https://github.com/user-attachments/assets/4881d0de-7bf4-4fda-9a7c-439543612837)
![exp 07 i](https://github.com/user-attachments/assets/ef3d164b-4a1b-415c-b0ca-9ac8e16bfb62)


### 2-Norm of a Matrix

![exp 07 ii](https://github.com/user-attachments/assets/9a492a88-0775-4878-adf2-ab9f3c0d4dc2)



### Infinity Norm of a Matrix

![exp 07 iii](https://github.com/user-attachments/assets/4881d0de-7bf4-4fda-9a7c-439543612837)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
