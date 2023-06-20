# COMMAND-LINE-ARGUMENTS-TO-COUNT-WORD
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 

### Step 1:Import sys module

### Step 2: Open the file with sys.argv[1]
 
### Step 3: Use the for loop to select the content in file

### Step 4: Use split function to to separate the file content into words or strings

### Step 5: Count the length of the words using len

### Step 6: Print the number of words

## PROGRAM:
Program for getting the word count from the contents of a file using command line arguments

Developed by: S.ANUSHARON

RegisterNumber: 212222240010

import sys
fp=open(sys.argv[1],"r")
d={}
for i in fp:
  for w in i.split():
    if w not in d.keys():
      d[w]-1
  else:
       d[w]+=1
  print(d)



### OUTPUT:

![Screenshot (326)](https://github.com/Anusharonselva/command-line-arguments-to-count-word/assets/119405600/207e660c-a1c6-4466-ba75-45eecbc3b295)

![Screenshot (326) 1](https://github.com/Anusharonselva/command-line-arguments-to-count-word/assets/119405600/4475fb66-180e-4c8d-9127-3754577f2bb5)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
