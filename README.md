# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys module
### Step 2: 
Open the file with sys.argv[1]
### Step 3: 
Use the for loop to select the content in file
### Step 4:  
Use split function to to separate the file content into words or strings
### Step 5: 
Count the length of the words using len 
### Step 6: 
Print the number of words
## PROGRAM:
```
Program for getting the word count from the contents of a file using command line arguments
Developed by:Maheswaran.K
Register Number: 212222110023
import sys
fp=open(sys.argv[1],'r')
count=0
for line in fp:
    words=line.split()
    count+=len(words)
print("Number of words in a file",count)

```

### OUTPUT:

![5b1](https://github.com/Vanitha-SM/command-line-arguments-to-count-word/assets/119557985/da3b6883-df48-42b5-94c3-18e3c839b5e4)
![5b2](https://github.com/Vanitha-SM/command-line-arguments-to-count-word/assets/119557985/9eb94059-430c-4476-9306-1b4a970e8010)
![5b3](https://github.com/Vanitha-SM/command-line-arguments-to-count-word/assets/119557985/de23efbd-c08f-42f9-b9a3-aca38a661ec3)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
