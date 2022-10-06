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
![Screenshot from 2022-10-06 11-38-17](https://user-images.githubusercontent.com/113497333/194227481-968ed892-4128-4f37-bbd4-ca236a320d5d.png)

![Screenshot from 2022-10-06 11-38-25](https://user-images.githubusercontent.com/113497333/194227534-3cb4347d-388f-4900-a497-3d02aa241673.png)






## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
