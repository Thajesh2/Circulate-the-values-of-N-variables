# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get the two values from the user
### Step 2: 
Assing the valuesbof second variables to a temporary variable
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Print both the values it would be interchanged
### Step 6: 
End the proogram
## Program:
```
#Program to circulate N values.
#Developed by: thajesh k
#RegisterNumber: 23004042

def circulate():
 l=eval(input())
 n=int(input())
 l=l[n:]+l[:n]
 print("After circulating the values are:",l)
```
## Output:

![Screenshot 2023-11-14 111613](https://github.com/Thajesh2/Circulate-the-values-of-N-variables/assets/139841959/4d9a5938-103c-4413-abed-672e3a31b4c2)


## Result:
Thus the circulate the values of N variable is succesfully executed
