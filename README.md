# copy-file
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
#Python program for copying the contents from one file to another file.
#Developed by: Kathir Anand S
#Register Number: 212223100018
def copy(fname, newfile):
    with open(fname, 'r')as fp:
        with open(newfile, 'w') as fp1:
            data1=fp.read()
            fp1.write(data1)
fname=input("Enter an existing file: ")
newfile=input("Enter a name for new file: ")
copy(fname, newfile)
```
### OUTPUT:
![Screenshot 2024-01-02 082106](https://github.com/Skathiranand/copy-file/assets/147141136/0e78c668-1e1b-4ecd-b507-40d4c434cb0b)

## EXISTING FILE:
![Screenshot 2024-01-02 082056](https://github.com/Skathiranand/copy-file/assets/147141136/0cbdc0c9-6da5-4b05-9afe-5b95e7df7f3c)

## NEW FILE:
![Screenshot 2024-01-02 082119](https://github.com/Skathiranand/copy-file/assets/147141136/92a20879-be6e-4d69-a976-cff0f46a944f)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
