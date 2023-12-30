# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file in read mode and handle it in test mood.
### Step 2: 
Read the text using read() function.
### Step 3: 
Split the text using space separator.We assume that words in a sentance are separted by a space character.
### Step 4:  
The length of the split list should equal the numbers of words in the test file.
### Step 5: 
You can refine the count by cleaning the string prior to splitting or validating the words after splitting.
### Step 6: 
End the program.
## PROGRAM:
```
#Program to find the number of words in a txt file.
#Developed by:Bhuvanesh.S.R
#Reg no:212223240017
num=0
with open("file.txt","r") as f1:
  for i in f1:
    word=i.split()
    num+=len(word)
print("The number of words in the file is ",num)
```
### OUTPUT:
![5a1](https://github.com/Bhuvanesh-Suresh/Word-count/assets/145742661/05d9ce36-ca5d-4958-ac80-76fc61b24cd8)
![5a2](https://github.com/Bhuvanesh-Suresh/Word-count/assets/145742661/d0785bb0-3118-463b-8366-d074f240842a)

## RESULT:
Thus the program is written to find the word count from a text.
