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
# Register No: 212224230267
# Developed By: V.Shriyha
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix

# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2025-04-21 223644](https://github.com/user-attachments/assets/8d3136e8-0e1b-45b7-ba12-e56573975b5f)

### 2-Norm of a Matrix
![Screenshot 2025-04-21 223653](https://github.com/user-attachments/assets/808fd6b2-9d91-4716-a06a-068bcd5c591c)

### Infinity Norm of a Matrix
![Screenshot 2025-04-21 223701](https://github.com/user-attachments/assets/dad9d533-49c3-4dad-8c32-16c2b2587924)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
