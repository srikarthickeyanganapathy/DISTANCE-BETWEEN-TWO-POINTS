# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1:
Import the math module to use the built-in functions for calculation
### Step 2: 
take two lists containing the points as the element
### Step 3: 
Substitute the values in the distance formula  
![formula](./formula.png)
### Step 4: 
print the distance with two decimal places
### Step 5:
end the program 
### PROGRAM:
```
#Program to find the distance between two points.
#Developed by: Sri Karthickeyan Ganapathy
#RegisterNumber:22008592
import math
l2=[10,6]
l1=[4,2]
dist=math.sqrt(((l2[0]-l1[0])**2)+((l2[1]-l1[1])**2))
print("{:.2f}".format(dist))
```
  
### OUTPUT:
![OUTPUT](op3.png)

### RESULT:
Thus the program to distance between two points is executed successfully.
