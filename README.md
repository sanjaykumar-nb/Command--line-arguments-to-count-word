# Command--line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import sys module to use command line arguments.
### Step 2: 
Create a file pointer and open the file which is passed in command line.
### Step 3: 
Initialize word count as zero.
### Step 4:  
For each line in file, split it into words and find number of the words in every line.
### Step 5: 
Sum the number of words in each line.
### Step 6: 
Display the total words in the file.
## PROGRAM:
```
#program to find the number of words in a text file
#Developed by : SANJAYKUMAR N B
#Register number : 212223230189

import sys
count = 0
with open (sys.argv[1],'r') as fl:
    for line in fl:
        word = line.split()
        count += len(word)
print("word count in file = ",count)
```
### OUTPUT:
![alt text](<Screenshot 2024-05-12 141109.png>)
## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
