# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Represent the given linear equations as a matrix of coefficients (a) and a matrix of constants (b).
### Step 2: 
Apply a method (like np.linalg.solve) that can find the solution for matrices a and b.
### Step 3: 
The solver will calculate and return the values of the unknowns (like x and y) that satisfy both equations.
### Step 4: 
print the final solution,showing the values of the variables
## Program:
``` python
#Program to find the solution for the given linear equations.
#Developed by: Rithika R
#RegisterNumber:212224240136

import numpy as np

a=[[1,3],[2,5]]
b=np.array([5,-3])
c=np.linalg.solve(a,b)
print(c)
```

## Output:
![image](https://github.com/user-attachments/assets/a3d7df1c-8a53-4741-847c-efc3ceba2821)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

