# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text file in a specific loaction of interest.
### Step 2: 
On the same location as the text file, create a python program file.
### Step 3: 
In python Program, import sys and open a text file with argument "sys.argv[1]"
### Step 4:  
 using read() and split(), split the lines in the file into a sequence of words.
### Step 5: 
using len() count the number of words in the text file.
### Step 6: 
In command prompt, initiate python followed by program name and text file name to get the output.
## PROGRAM:
```
'''
python program for getting the word count from the contents of a file using command line arguments.
Develpoed By: Maheswaran.K
RegisterNumber:212222110023
'''
fname=input("Enter the file name:")
num_word=0
with open(fname,'r') as f:
  for line in f:
    words=line.split()
    num_word+=len(words)
print('Number of words: ',num_word)
```

### OUTPUT:
[E5.pdf](https://github.com/MAHESWARAN2004/command-line-arguments-to-count-word/files/11513669/E5.pdf)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
