# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Import numpy module.
2. Get the input matrix using np.array()   
3. Find the 2-norm of the matrix using np.linalg.norm()
       1. np.linalg.norm(a,1) for 1-Norm
       2. np.linalg.norm(a,2) for 2-Norm
       3. np.linalg.norm(a,np.inf) for Infinity-Norm
4. Print the norm of the matrix in two decimal places.
## Program:
```
# Register No: 212222230168
# Developed By: VASUNDRA SRI R
# 1-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,1)
norm="{:.2f}".format(soln)
print(norm)



# 2-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,2)
norm="{:.2f}".format(soln)
print(norm)




# Infinity Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,np.inf)
norm="{:.2f}".format(soln)
print(norm)




```
## Output:
### 1-Norm of a Matrix


![norm 1](https://user-images.githubusercontent.com/119393983/236690386-0a25dcbd-fd85-42f3-97a2-eb675eb94d2f.png)


### 2-Norm of a Matrix


![norm 2](https://user-images.githubusercontent.com/119393983/236690399-3a338c8d-9f16-491a-87ea-e740cd96abc2.png)


### Infinity Norm of a Matrix


![norm 3](https://user-images.githubusercontent.com/119393983/236690413-151ec8ce-95fc-4e3f-8e08-c13252ee26f8.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
