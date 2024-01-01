# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
get the file name to create user
### Step 2:
give a new file name to create a copy of a file content
### Step 3:
read the file and close the file
### Step 4:
now the content in the new file
### Step 5:
when done print"File Copied Successfully"
### Step 6:
end the program
## PROGRAM:
'''
Program to copy the file.
#Developed by: Harini.S
#RegisterNumber:23004240
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
### OUTPUT:
1.![image](https://github.com/Hariniii21/copy-file/assets/147140423/94855fab-99d2-4ff2-a2cc-53afe505192e)
2.![image](https://github.com/Hariniii21/copy-file/assets/147140423/dd04fe18-4cb7-4013-a181-37c5f4309fb5)
## RESULT:
Thus the program is written to copy the contents from one file to another file.
