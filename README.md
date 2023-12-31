# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: import sys

### Step 2: with the file with sys.argv
 
### Step 3: create a for loop for the process

### Step 4:  count the number of words in the text

### Step 5: print the value

### Step 6: In the command prompt give the text file as input

## PROGRAM:
import sys<br>
<br>
with open(sys.argv[1],'r') as value:<br>
    count=0<br>
    for i in value:<br>
        word=i.split()<br>
        count=len(word)<br>
print(f'Number of word :{count}')<br>        

### OUTPUT:
![image](https://github.com/sanjaysivaramakrishnan/command-line-arguments-to-count-word/assets/151629616/26fe4171-27a2-4b25-be54-c45fe507794b)
![image](https://github.com/sanjaysivaramakrishnan/command-line-arguments-to-count-word/assets/151629616/3f0f2c23-83cd-4896-83be-8e75014afcf2)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
