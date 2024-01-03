# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
fname to represent the file name given
### Step 2: 
 with open function to open a file
### Step 3: 
text files words are splitted using split()
### Step 4:  
using for loop to count the char
### Step 5: 
char has been counted and output has been printed

## PROGRAM:
```
#Program to find the Word Count using command line arguments
#Developed by : Allen Joveth P
#Register Number : 23009582
fname=input("enter the file name")
num_words=0
with open(fname,'r') as f:
    for line in f:
        words=line.split()
        num_words+=len(words)
print('Number of words: ',num_words)
```
### OUTPUT:

![Screenshot 2024-01-03 171611](https://github.com/allenjoveth/command-line-arguments-to-count-word/assets/139422287/a2885ce8-5ed7-44e8-91cc-8b93bc757ba4)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
