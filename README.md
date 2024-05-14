
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Define the function as copy with arguements as existing file name and new file name.

### Step 2:
Open the existing file to read.

### Step 3:
Open the new file to write.

### Step 4:
Copy the contents from existing file to new file.

### Step 5:
Get the inputs from the user for existing file and new file. Call the function.

### Step 6:
End the program.

## PROGRAM:
```
Write a python program for copying the contents from one file to another file.
Develop bY: R.Sabarinath
Register no: 212223100048
with open("text.txt",'r') as fp:
    msg1=fp.read()
with open("copy.txt",'w') as fp1:
    fp1.write(msg1)
```
### OUTPUT:
![11 1](https://github.com/Sabari-2005/Copy-File/assets/139338709/2c79b2bf-1e1d-45f5-8d0e-2a5d3070a393)
![11 2](https://github.com/Sabari-2005/Copy-File/assets/139338709/64e11b03-7251-4c25-9a8b-ea0ac7528b56)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
