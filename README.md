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
import numpy as np
a = np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
b = np.array([-9,4,-1])
solution=np.linalg.solve(a,b)
print(solution)
```
## Output:
![Screenshot 2023-09-26 002656](https://github.com/Preetha-Senthamilan/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/119390282/bbb8958e-b5cb-4c8b-ab77-baeb91ab4637)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program.

