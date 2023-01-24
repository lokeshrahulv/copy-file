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
with open("sample1.txt", "r") as firstfile:
    with open("sample2.txt", "a") as secondfile:
        for line in firstfile:
            secondfile.write(line)
``` 
### OUTPUT:

![image](https://user-images.githubusercontent.com/118423842/214330892-bddac5d7-59fb-4586-984d-d6a6cd3a2746.png)
![image](https://user-images.githubusercontent.com/118423842/214331618-a16d6382-bc52-4dce-b3e0-854148b76761.png)
![image](https://user-images.githubusercontent.com/118423842/214331789-bedb2058-0bd6-4dc3-943b-e8b77545c55c.png)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
