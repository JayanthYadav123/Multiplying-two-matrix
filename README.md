# Multiplying-two-matrix

## AIM:To find the product of two arrays using numpy by using python programming.

## ALGORITHM:
Step 1:
Import Numpy as np.

Step 2:
Get input from the user.

Step 3:
Create empty lists l1 and l2.

Step 4:
Use for loop to append the values into the list created.

Step 5:
Print the product of two arrays.


## PROGRAM: 
~~~
Developed by:G.jayanth
Registration no:21005806
import numpy as np
array1 = []
array2 = []
n= int(input())
for i in range(n):
    array1.append(int(input()))
for i in range(n):
    array2.append(int(input()))
value1= np.array(array1)
value2= np.array(array2)
result = value1*value2
print("Product of two arrays is:",result)
~~~
## OUTPUT:
![OUTPUT](logo.png)

## RESULT:
Thus the program to find the product of two arrays using numpy has been verfied successfuly using python programming.


