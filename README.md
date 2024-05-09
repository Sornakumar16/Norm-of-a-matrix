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
#Developed By:SORNAKUMAR S
#Register number:212223230210
import numpy as np
mat= eval(input())
a=np.linalg.norm(mat,1)
print("%0.2f"%a)




# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: SORNAKUMAR S
RegisterNumber:212223230210
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_mat="{:.2f}".format(ans)
print(norm_mat)




# Infinity Norm of a Matrix
'''
Program to find the Infinity of a matrix
Developed by:SORNA KUMAR S
Register number:212223230210
'''
import numpy as np
mat=eval(input())
a=np.linalg.norm(mat,np.inf)
print("%0.2f"%a)




```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/Sornakumar16/Norm-of-a-matrix/assets/138849327/e800e6dc-a500-495a-b006-87d688d4a6dd)


### 2-Norm of a Matrix
![image](https://github.com/Sornakumar16/Norm-of-a-matrix/assets/138849327/a15e7ad3-317f-4c29-b4b6-d682370fcdc9)


### Infinity Norm of a Matrix
![image](https://github.com/Sornakumar16/Norm-of-a-matrix/assets/138849327/9f8cfbba-6fca-4373-9cc3-63533f764d39)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
