# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
From shutil import copyfile

From sys import exit

### Step 2: 
 
 Take users the name of source and destination files.
### Step 3: 

If the source there is a source file then copy the contents of source file to the destination file.
### Step 4:  
Read each line from the input file and write it into the output file.


### Step 5: 


Then print

### Step 6: 

End the program

## PROGRAM:

```

## DEVELOPED BY: virgil jovita.a
## REGISTER NUMBER: 212221240062
#Program to copy content from one file to another.
with open("file1.txt","r") as f1:
    content = f1.read()
with open("file2.txt","w") as f2:
    f2.write(content)

```

### OUTPUT:


![output](.//h1.png)



## RESULT:
Thus the program is written to copy the contents from one file to another file.