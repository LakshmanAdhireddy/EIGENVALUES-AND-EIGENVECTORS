# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step1 :
Import the numpy module to use the built-infunctions for calculation

Step 2:
Prepare the lists from each linear equations and assign in np.array{}

Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

Step 4:
End the program 

## Program:
~~~
#Program to find the eigen values and eigen vectors.
#Developed by:Lakshman reddy 
#RegisterNumber:22004423
import numpy as np
A=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
~~~

## Output:
![Screenshot (27)](https://user-images.githubusercontent.com/118707265/213906320-0758c7ef-e5e2-442a-89c2-7f3fce64f926.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
