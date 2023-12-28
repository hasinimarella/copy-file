# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
First we need to open the required file from which we need to copy the text.Again using the with keyword to open the empty file.
### Step 2: 
 Using keyword "with" to open the empty file.
### Step 3: 
Again using the with keyword to open the empty file.
### Step 4:  
The empty file is open by using "w" which is used to write only.
### Step 5: 
The four function is used to take each line from the main file.
### Step 6: 
Print the program.
## PROGRAM:
```
#Program to copy the file.
#Developed by: MARELL HASINI
#RegisterNumber: 212223240083
'''
print("Enter the name of source file: ")

sFile=input()

print("Enter the name of target file: ")

tFile=input()

fileHandle=open(sFile,"r")

texts=fileHandle.readlines()

fileHandle.close()

fileHandle=open(tFile, "w")

for s in texts:

    fileHandle.write(s)

fileHandle.close()

print("\nFile Copied Successfully!")
```
### OUTPUT:
![OUTPUT](<copy file-1.png>)
![OUTPUT](<copy file 1.png>)
![OUTPUT](<copyfile 2.png>)
## RESULT:
Thus the program is written to copy the contents from one file to another file.
