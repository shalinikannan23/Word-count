# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Declare number of words as zero.

### Step 2: 
Open it with txt file.
 
### Step 3:
Give range for i.

### Step 4:  
Then split the words.
### Step 5: 
Count the number of words.
### Step 6: 
End the Program
## PROGRAM:
```
# Program to find Word count
# Developed by: Shalini.K
# Register no: 22008827

num_words =0
with open('file1.txt','r') as file1:
    for i in file1:
        word =i.split()
        num_words += len(word)
print("Number of words={}".format(num_words))
```
### OUTPUT:

![image](https://github.com/shalinikannan23/Word-count/assets/118656529/7073cc12-f034-47e4-8243-4f2e552fa8b6)


## RESULT:
Thus the program is written to find the word count from a text.
