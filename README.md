# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Use open function to open the file in which we want to copy from and access it in read mode.
### Step 2: 
 Read the file and store in a variable.
### Step 3: 
Now create a new file in which we want to paste the content using write access mode.
### Step 4:  
Now create a new file in which we want to paste the content using write access mode.
### Step 5: 
 The content in the original file will be copied in the new file.
### Step 6: 
 End the program.
## PROGRAM:
```
Developed by: LOKESH RAHUL V V
Register no: 22004702

print("Enter the Name of Source File: ")
sFile = input()
print("Enter the Name of Target File: ")
tFile = input()
fileHandle = open(sFile, "r")
texts = fileHandle.readlines()
fileHandle.close()

fileHandle = open(tFile, "w")
for s in texts:
    fileHandle.write(s)
fileHandle.close()

print("\nFile Copied Successfully!")
``` 
### OUTPUT:

![rec 1](https://user-images.githubusercontent.com/118423842/214763512-726a8706-45d0-4c46-8927-2d72dbae7e6c.jpg)
![rec2](https://user-images.githubusercontent.com/118423842/214763552-8e81c92e-dbe1-4b23-b071-c2957557a6f4.jpg)
![rec3](https://user-images.githubusercontent.com/118423842/214763575-1207f1d2-d702-4e47-b58d-63ba85789c44.jpg)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
