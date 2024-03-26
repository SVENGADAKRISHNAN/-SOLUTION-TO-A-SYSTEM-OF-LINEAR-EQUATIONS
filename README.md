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
#Developed by: S.VENGADA KRISHNAN
#RegisterNumber: 212223110061
import numpy as np# np is the identifier
a=np.array([[1,-3],[3,1]])
b=np.array([0,10])
solution=np.linalg.solve(a,b)#passing these arguements to the function
print(solution)
```
## Output:
![solving linear equation](https://github.com/SVENGADAKRISHNAN/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/147473084/5d3c6d55-b047-4297-9948-fe11f84dcc18)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

