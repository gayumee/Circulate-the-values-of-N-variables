# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5:
End the program

## Program:
```
def circulate():
    l=eval(input())
    n=int(input())
    n=n%len(l)
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
circulate()
```
## Output:
['a','b','c','d','e','f']
2
After circulating the values are: ['c', 'd', 'e', 'f', 'a', 'b']
## Result:
Thus circulating the variables in python is done and executed successfully.
