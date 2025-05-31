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
# Register No:212224240117
# Developed By:Prathik TS
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: DILLI BABU K
RegisterNumber: 212224110015
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
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
![Screenshot 2025-04-26 144806](https://github.com/user-attachments/assets/114e8b17-d406-4000-8258-a0aac4c9c208)


### 2-Norm of a Matrix
![Screenshot 2025-04-26 144817](https://github.com/user-attachments/assets/6c79be5a-310d-4303-82ff-10adf7159c55)


### Infinity Norm of a Matrix
![Screenshot 2025-04-26 144827](https://github.com/user-attachments/assets/43a3bf3f-4296-4321-ad06-c0ec436b19a8)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
