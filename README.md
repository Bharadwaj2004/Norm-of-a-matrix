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
```
# Register No: B.venkata bharadwaj
# Developed By:22003979
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```
```
# 2-Norm of a Matrix
# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```
```
# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![image](https://user-images.githubusercontent.com/119560345/214867047-9f0f54f6-c0b4-4b1c-87db-71056133634f.png)

### 2-Norm of a Matrix
![image](https://user-images.githubusercontent.com/119560345/214866918-a94468e2-65de-4ff2-a07d-ac3f5800b0ad.png)

### Infinity Norm of a Matrix
![image](https://user-images.githubusercontent.com/119560345/214866772-33e2f4ce-b6ee-4c6b-9856-adf9db1db82d.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
