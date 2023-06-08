# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
## Step 1:
Use open function to open the file in which we want to copy from and access it in read mode.

## Step 2:
Read the file and store in a variable.

## Step 3:
Now create a new file in which we want to paste the content using write access mode.

## Step 4:
Use write function to copy the read file that has been stored in the variable.

## Step 5:
The content in the original file will be copied in the new file.

## Step 6:
End the program
## PROGRAM:
```
#python program for copying a file
#developed by:ANANDHAMOORTHY.K
#registration number:212222100004
with open("sample1.txt", "r") as firstfile:
    with open("sample2.txt", "a") as secondfile:
        for line in firstfile:
            secondfile.write(line)  
```
### FILE :
![Screenshot 2023-06-08 104347](https://github.com/AnandhamoorthyKarthikeyan/copy-file/assets/119475998/977f31e3-5bd8-4899-b9f2-e9e6ae9b4f5c)

### OUTPUT
![Screenshot 2023-06-08 104401](https://github.com/AnandhamoorthyKarthikeyan/copy-file/assets/119475998/53bc41f7-5eec-41dd-a08f-f70d1fb1579d)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
