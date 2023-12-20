# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
start the program
### Step 2: 
get the input from the user using eval(input())
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
using concatenation operation display the entire rotated
### Step 6: 
stop the program

## Program:
```
#Program to circulate N values.
#Developed by: OVIYA P
#RegisterNumber:23013207
def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)
```

## Output:
![OUTPUT](https://github.com/Oviya24032K6/Circulate-the-values-of-N-variables/assets/147139999/8b3768c8-76b6-414c-9568-aa122b8efdbb)


## Result:
Thus the python program for circulate the values of n variables is executed successfully
