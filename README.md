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
# Register No:212225230170
# Developed By:MATHIYAZHAGAN.A
# 1-Norm of a Matrix

7) import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)


# 2-Norm of a Matrix
7) import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)



# Infinity Norm of a Matrix
7) import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix

![WhatsApp Image 2026-02-07 at 09 08 36](https://github.com/user-attachments/assets/53a09a65-dd76-47fb-a550-ed33e5d72516)


### 2-Norm of a Matrix

![WhatsApp Image 2026-02-07 at 09 08 37](https://github.com/user-attachments/assets/8956b62f-f26b-4e0d-96ee-0f3e6dae6cb6)


### Infinity Norm of a Matrix

![WhatsApp Image 2026-02-07 at 09 08 37 (1)](https://github.com/user-attachments/assets/42c2e432-8d8b-4054-b5f5-1aff315974c5)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
