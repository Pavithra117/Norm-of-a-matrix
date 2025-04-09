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
# Register No: pavithra k
# Developed By: 212224240112
# 1-Norm of a Matrix

import numpy as np
m=np.array(eval(input()))
a=np.linalg.norm(m,1)
n="{:.2f}".format(a)
print(n)




# 2-Norm of a Matrix

import numpy as np
m=np.array(eval(input()))
a=np.linalg.norm(m,2)
n="{:.2f}".format(a)
print(n)




# Infinity Norm of a Matrix

import numpy as np
m=np.array(eval(input()))
a=np.linalg.norm(m,np.inf)
n="{:.2f}".format(a)
print(n)




```
## Output:
### 1-Norm of a Matrix

![Screenshot 2025-04-09 111458](https://github.com/user-attachments/assets/2f92eac6-ba25-4fbf-88ff-1bc3197455e1)

### 2-Norm of a Matrix

![Screenshot 2025-04-09 111514](https://github.com/user-attachments/assets/b29b6279-5438-43c2-832b-5440093249b9)

### Infinity Norm of a Matrix

![Screenshot 2025-04-09 111528](https://github.com/user-attachments/assets/6442f636-0eef-471a-a589-98396181351e)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
