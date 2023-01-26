# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Use open function to open the file in which we want to copy from and access it in read mode.

### Step 2: 
Read the file and store in a variable.

### Step 3: 
Now create a new file in which we want to paste the content using write access mode.

### Step 4:  
Use write function to copy the read file that has been stored in the variable.



### Step 5: 
The content in the original file will be copied in the new file.



### Step 6: 
End the program.

## PROGRAM:
```
Developed by: C Saravanan
Ref.no: 22008175
with open("copy.txt", "r") as firstfile:
    with open("text.txt", "a") as secondfile:
        for line in firstfile:
            secondfile.write(line)

### OUTPUT:
![image](/https://user-images.githubusercontent.com/121395849/214924605-83b3c7e3-5901-472b-93c9-ff26fd201099.jpg)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
