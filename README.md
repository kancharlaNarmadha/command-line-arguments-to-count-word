# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 

# Step 1: Import sys module to use command line arguments.

# Step 2: Use the open() by getting the file name with "sys.argv[1]" which means the first index of given argument

# Step 3: Iterate the content of the file using for loop.

# Step 4: Split the contents into each line using .split() function.

# Step 5: Iterate the list of lines and increment the value of variable (word) each time.

# Step 6: Run the program by giving "python prgm.py EX12.txt" on the terminal.


## PROGRAM:

```
#Developed By: KANCHARLA NARMADHA

#Register No: 21222110016

import sys
fp=open(sys.argv[1],'r')
count=0
for line in fp:
    words=line.split()
    count+=len(words)
print("Number of words in a file",count)

```


### OUTPUT:

![PYTHON 51](https://github.com/kancharlaNarmadha/command-line-arguments-to-count-word/assets/119559316/52ffb693-3434-4dbe-ac6b-7d2298ab34eb)

![PYTHON 52](https://github.com/kancharlaNarmadha/command-line-arguments-to-count-word/assets/119559316/783ab6e8-54e7-4b2f-8d71-ca30348df20d)

![PYTHON 53](https://github.com/kancharlaNarmadha/command-line-arguments-to-count-word/assets/119559316/40a33a13-746f-430b-a839-9cfcb284ef9c)




## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
