# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Prompt the user to provide:
The name of the existing file to be copied (stored in the variable fname).
The desired name for the new file to be created (stored in the variable newfile).
### Step 2: 
Copy Content:

Open the existing file (fname) in read mode ('r').
Open the new file (newfile) in write mode ('w'), creating it if it doesn't exist.
Read the entire content of the existing file into a variable (data1).
Write the content from the variable (data1) into the new file.
### Step 3: 
 Close Files:

Ensure proper closure of both files to release system resources.
The with open(...) construct automatically handles this for you in Python.
 

## PROGRAM:
```
#python program for copying the contents from one file to another file.
#Developed by: P PARTHIBAN
#Register Number: 23007965

def copy (fname, newfile) :
    with open (fname, 'r')as fp:
        with open (newfile, 'w' )as fpl:
            datal=fp.read()
            fpl.write (data1)
fname=input ("Enter an existing file: ")
newfile=input ("Enter a name for new file: ")
copy (fname, newfile)
```
### OUTPUT:
![image](https://github.com/23007965/copy-file/assets/138971238/6776a3d9-2e9a-4b98-919f-0eb46f422506)


![Screenshot 2024-01-01 011416](https://github.com/23007965/copy-file/assets/138971238/326cadac-e60e-4178-9291-fbe467b18381)
![Screenshot 2024-01-01 011424](https://github.com/23007965/copy-file/assets/138971238/3f83b15d-e718-4133-bfae-f0d28e7e4c75)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
