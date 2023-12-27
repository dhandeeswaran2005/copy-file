# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a file.
### Step 2: 
Write some lines in that file 
### Step 3: 
Create a python file.
### Step 4:  
Write a code to copy the content of the file to a new file.
### Step 5: 
Run the program.
### Step 6: 
Display the output.
## PROGRAM:
```
'''
#Program to copy the file.
#Developed by: Dhandeeswaran selvakumar
#RegisterNumber: 23006838
'''
print("Enter the name of source file: ")
sFile=input()
print("Enter the name of target file: ")
tFile=input()
fileHandle=open(sFile, "r") texts=fileHandle.readlines(
fileHandle.close()
fileHandle=open(tFile, "w")
for s in texts:
fileHandle.write(s)
fileHandle.close()
print("\nFile Copied Successfully!")
```
### OUTPUT:
![Screenshot 2023-12-27 155404](https://github.com/dhandeeswaran2005/copy-file/assets/147139188/4a67cdd1-12a3-4707-b35c-762c6e16ce5b)

![Screenshot 2023-12-27 155413](https://github.com/dhandeeswaran2005/copy-file/assets/147139188/0509cfa4-0441-4e30-b145-dd98d5008e49)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
