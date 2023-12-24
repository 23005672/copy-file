# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create the file.
### Step 2: 
Write some lines in that file.
### Step 3: 
Create python file.
### Step 4:  
Write a code to copy the content of the file to a new file.
### Step 5: 
Run the program.
### Step 6: 
Display the output.
## PROGRAM:
```PYTHON
#Developed by : RIYA P L
#Reference no : 23005672

def copy(filename,newfile):
    with open(filename,'r') as fp:
        with open(newfile,'w') as fp1:
            data1=fp.read()
            fp1.write(data1)
filename=input("Enter an Existing File:")
newfile=input("Enter a name for new file:")
copy(filename,newfile)

```
### OUTPUT:
<img width="351" alt="copyfile1" src="https://github.com/23005672/copy-file/assets/138971519/8d133ce1-ebfb-48bc-aab9-5db9be7043a7">
<img width="491" alt="copyfile2" src="https://github.com/23005672/copy-file/assets/138971519/5e238b8a-0dc9-46bc-94a7-af0d9de7877b">



## RESULT:
Thus the program is written to copy the contents from one file to another file.
