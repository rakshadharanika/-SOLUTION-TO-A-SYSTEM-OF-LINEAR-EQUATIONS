# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## NAME   : V RAKSHA DHARANIKA
## REF.NO : 212223230167
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
#Developed by: V RAKSHA DHARANIKA,
#RegisterNumber:21223230167.
import numpy as np
a = np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]]) 
b = np.array([-9,4,-1]) 
c=np.linalg.solve(a,b)
print(c)


```

## Output:
![Screenshot (111)](https://github.com/rakshadharanika/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/149348380/bed40465-0f3d-43dd-bbfb-f01cbb80a11b)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

