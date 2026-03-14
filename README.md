# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step1 :
Import the numpy module to use the built-in functions for calculation

Step 2:
Prepare the lists from each linear equations and assign in np.array()

Step 3:
Using np.linalg.inv(),we can find the inverse of a matrix

Step 4:
End the program

## Program:
~~~ python
#Program to find the inverse of a matrix.
#Developed by: suvetha.k
#RegisterNumber:25014616
import numpy as np
A=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
x=np.linalg.inv(A)
print(x)
~~~
## Output:
<img width="650" height="348" alt="Screenshot 2026-02-05 161821" src="https://github.com/user-attachments/assets/77a415bb-e7b2-44ca-8573-9e783354035b" />


