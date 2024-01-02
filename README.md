# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
To write a python program for getting the word count from a text file.

### Step 2:
Open the required file by using the function "with"
 
### Step 3:
Then use the laptop to assign the i value in the file

### Step 4:  
Using split function to spilt the words

### Step 5:
Finding the given length of the words by using len() fuction.

### Step 6: 
Calling the function and Printing the number of words.

## PROGRAM:
```python
'''
Program to count the no. of words in a file.
Developed by: Neethiventhan.N
Reg.no:23006643
'''
fname=input("Enter the file name:")
num_words=0
with open(fname,"r") as f:
  for line in f:
    words=line.split()
    num_words+=len(words)
  print("Number of words:",num_words)

### OUTPUT:
![image](https://github.com/Neethiventhan123/Word-count/assets/148514848/59d66c2f-4a50-49a0-a968-69c95240cd12)

## RESULT:
Thus the program is written to find the word count from a text.
