# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1:

Open the file in read mode and handle it in test mood.

Step 2:

Read the text using read() function.

Step 3:

Split the text using space separator.We assume that words in a sentance are separted by a space character.

Step 4:

The length of the split list should equal the numbers of words in the test file.

Step 5:

You can refine the count by cleaning the string prior to splitting or validating the words after splitting.

Step 6:

End the program.

## PROGRAM:
```
Program to count the words in a file
Developed by: BALASUDHAN P
Register number: 212222240017

fname=input("Enter the file name:")
num_words=0
with open(fname,"r") as f:
  for line in f:
    words=line.split()
    num_words+=len(words)
print("Number of words:",num_words)
```
### OUTPUT:
![239798444-4787aade-4c9b-4696-8621-8ce908539a80](https://github.com/BALASUDHAN18/Word-count/assets/118807740/53333675-66e9-4861-9e42-69a0b73cb051)


## RESULT:
Thus the program is written to find the word count from a text.
