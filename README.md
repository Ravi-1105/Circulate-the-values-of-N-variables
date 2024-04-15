# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the N variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Define a function named circulate.
### Step 2: 
Get list from the user.
### Step 3: 
Get the value from the user for the number of rotation.
### Step 4: 
Using the slicing concept circulate the list
### Step 5: 
Finally print the result
## Program:
```
#Program to circulate n values.
#Developed by: RAVIVARMAN G S
#RegisterNumber: 212223100044

def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result) 
```
## Output:
![op1](https://github.com/Ravi-1105/Circulate-the-values-of-N-variables/assets/139841688/f5b699b5-47fb-497c-bff9-f10ea0f8cda3)
![op2](https://github.com/Ravi-1105/Circulate-the-values-of-N-variables/assets/139841688/efc08d79-5497-4f95-94ce-0f152402e127)
![image](https://github.com/Ravi-1105/Circulate-the-values-of-N-variables/assets/139841688/b908c8de-180c-4668-b2bf-525288036e3a)

## Result:
Thus the list has been circulated with N values.
