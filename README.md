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
# Register No:
# Developed By:
# 1-Norm of a Matrix
'''
Program to find 1-norm of a matrix.
Developed by: Yadhav.G.P
RegisterNumber: 23004895
'''
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))


# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: Yadhav.G.P
RegisterNumber: 23004895
'''
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))


# Infinity Norm of a Matrix
'''
Program to find Infinity-norm of a matrix.
Developed by: Yadhav.G.P
RegisterNumber: 23004895
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
![Alt text](1st.png)

### 2-Norm of a Matrix
![Alt text](2nd.png)

### Infinity Norm of a Matrix
![Alt text](3rd.png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
