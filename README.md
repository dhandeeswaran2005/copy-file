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
#Developed by: MOHAMED FAROOK S
#RegisterNumber: 23014058
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
![image](https://github.com/MOHAMEDFAROOK2005/copy-file/assets/150319482/70224991-f533-4177-aa9a-f3e362d537b2)

![image](https://github.com/MOHAMEDFAROOK2005/copy-file/assets/150319482/b499f17b-3bf9-4cd2-99b5-d8d9adbc821e)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
