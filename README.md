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
#Developed by: Mukesh Kumar S
#RegisterNumber:212223240099
import numpy as np
a=np.array([[1,-3],[3,1]])
b=np.array([0,10])
rank=np.linalg.solve(a,b)
print (rank)
```
# Output:
![Screenshot 2024-04-08 210813](https://github.com/mukeshkumar1110/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/152305679/a697c36b-0cb8-413a-9b4c-86e60710a83b)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program
