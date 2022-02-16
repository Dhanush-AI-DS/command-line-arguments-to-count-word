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
~~~
# Developed by : Dhanush. S
# Reg no: 212221230020
# To write a program for getting the word count from the contents of a file using command line arguments.

import sys

with open(sys.argv[1],'r') as f:
    num_of_words =0
    for i in f:
        word =i.split()
        num_of_words += len(word)
print("Number of words={}".format(num_of_words)) 
~~~

### OUTPUT:
![CLAT](https://user-images.githubusercontent.com/95356096/154283817-f8b866a1-2800-482b-a70d-79e9f5ab8e5d.png)
![clap](https://user-images.githubusercontent.com/95356096/154281684-7d5f13c5-0464-41bb-89cf-d5f334bd5cce.png)





## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
