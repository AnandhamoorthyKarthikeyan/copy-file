# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: Open the file f1 in read mode.

### Step 2: Open the file f2 in append mode.
 
### Step 3: Copy the contents using write() with the for loop.

### Step 4: End the program.
## PROGRAM:
```
#Developed By: anandhamoorthy.k
#Register No: 212222100004
with open('f1.txt','r') as f1:
    with open ('f2.txt','a') as f2:
        for line in f1:
            f2.write(line)
```
### FILE :
![Screenshot 2023-06-15 224253](https://github.com/AnandhamoorthyKarthikeyan/copy-file/assets/119475998/d0dc2b72-fbb2-4bda-9edf-503171341c51)
![Screenshot 2023-06-15 224306](https://github.com/AnandhamoorthyKarthikeyan/copy-file/assets/119475998/b3232bba-7ed7-412d-91d5-cb11a88a0d13)
### OUTPUT
![Screenshot 2023-06-15 224320](https://github.com/AnandhamoorthyKarthikeyan/copy-file/assets/119475998/fb79fa89-5cb2-4fc5-aa64-c45f1115fbe0)
## RESULT:
Thus the program is written to copy the contents from one file to another file.
