# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
```
#Program to find the solution for the given linear equations.
#Developed by:Harshavardhan.K.B
#RegisterNumber:212224240054
import numpy as np
A=[[1,3],[2,5]]
B=np.array([5,-3])
C=np.linalg.solve(A,B)
print(C)
```
## Output:
![Screenshot 2025-04-26 110014](https://github.com/user-attachments/assets/91679aaf-0bdc-4e17-a2ba-a73b37c0a275)



## Result: 
Thus the solutions for the linear equations are successfully solved using python program

