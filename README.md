# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: Create a text1.txt with some content in it
### Step 2: Open the text1.txt file in read mode
### Step 3: Create a copy.txt file using write mode
### Step 4: Copy the content of text1.txt file to copy.txt using write function
## PROGRAM:
```
#Program for copying the contents from one file to another file
#Programmed By:M HIMAVATH
#RegisterNumber: 23010121

with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```
### OUTPUT:
![WhatsApp Image 2023-12-29 at 20 18 18_5f0e5c9c](https://github.com/Himavath08/copy-file/assets/139110631/29a58a34-7bc4-49d8-bc5c-9545d411628a)

![256283754-c0c0f8db-f8f4-411b-bfea-c43185615dde](https://github.com/Himavath08/copy-file/assets/139110631/0afcb078-5156-47bd-ad3a-6058448d6a74)
![256283827-86883382-968c-4e14-8729-1b71c7705997](https://github.com/Himavath08/copy-file/assets/139110631/57cd067b-2af9-4003-a685-60fe14c39c8e)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
