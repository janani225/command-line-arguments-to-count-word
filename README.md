# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import sys

### Step 2: 
Open file using commandline arguments.
 
### Step 3: 
Using for loop find the word count from the contents of a file.

### Step 4:
Use len to count number of words.

### Step 5: 
Give print statement.
### Step 6: 
End the program.

## PROGRAM:
```
#Developed by:JANANI V S
#Registration no:22003192

import sys
count=0
with open(sys.argv[0],'r') as f:
    for line in f:
        word=line.split()
        count += len(word)
print("Word Count in file =",count)
```


### OUTPUT:


![zia file](https://user-images.githubusercontent.com/113497340/194223216-a8af6726-081f-4fb3-a4ee-6719d43ad92f.png)





## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
