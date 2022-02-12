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
Open file using open().

### Step 3:
Use for loop.

### Step 4:
Use len to count number of words.

### Step 5:
Give print.

## PROGRAM:
```
##Developed by :B.PAVIZHI
##Register number :212221230077

import sys

with open(sys.argv[1],'r') as f:
    num_words =0
    for i in f:
        word =i.split()
        num_words += len(word)
print("Number of words={}".format(num_words))
```

### OUTPUT:
![output](./wordcount.png)
![output](./wordcount2.png)




## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
