# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Define a function named circulate that takes no arguments.
### Step 2: 
Inside the function, use input to get a string representation of a list from the user and evaluate it to get the actual list.
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Print the circulated list l with the message "After circulating the values are:"

## Program:
                              def circulate():
                                  l=eval(input())
                                  n=int(input())
                                  l=l[n:] + l[:n]
                                  print("After circulating the values are:",l)
                                  
## Output:
![Screenshot 2024-03-21 140022](https://github.com/SadhanaShreee/Circulate-the-values-of-N-variables/assets/144517664/cc0556aa-cda3-4ea6-83b9-8bd8f25a31b5)


## Result:
Hence,the values are circulated successfully.
