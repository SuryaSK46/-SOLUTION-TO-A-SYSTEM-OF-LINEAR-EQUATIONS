## EX NO: 1 -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## DATE:
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
#Developed by: Surya SK
#RegisterNumber: 212222100052
import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
B=np.array([-9,4,-1])
result=np.linalg.solve(A,B)
print(result)
```

## Output:
![Screenshot 2023-06-10 022701](https://github.com/SuryaSK46/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/127716537/95e5c2a5-7116-46f8-bd3b-4f003bfbadf2)


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

