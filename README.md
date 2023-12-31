# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## Algorithm
## Step 1:
Get the file name and location from the user.

## Step 2:
Give a new file name to create a copy of a file content.

## Step 3:
Read the file and close the file.

## Step 4:
Now write the content in the new file.

## Step 5:
When done print"File copied successfully".

## Step 6:
End of the program

## PROGRAM:
```python
#To write a program for coping the contents from one to another file.
#Developed by : Mugil
#RegisterNumber:212223230127
with open("file1.txt","r") as f:
    x=f.read()
with open("file2.txt","w") as f1:
    f1.write(x)
```
## OUTPUT:
![image](https://github.com/mugil25/copy-file/assets/148515771/f2deb594-2a6f-4081-b6ad-311c59ce32eb)
![image](https://github.com/mugil25/copy-file/assets/148515771/d046d7f7-509a-4353-9293-2abee8e8c8fe)
![image](https://github.com/mugil25/copy-file/assets/148515771/718f94b6-a4e8-4881-b884-3c20744a3eec)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
