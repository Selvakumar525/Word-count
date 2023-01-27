# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a new text file
### Step 2: 
 Open the file using open() in read mode
### Step 3: 
Initialize count is 0
### Step 4:  
for each line split the words and store in a list
### Step 5: 
add the length of the list to the count for each line
### Step 6: 
print the count
## PROGRAM:
```
write a program for getting the word count from a text.
Developed by: Dario G
RegisterNumber: 22008843

f=open("sample1.txt","r")
wc=0
for line in f:
    word=line.split(" ")
    wc=wc+len(word)
print("word count is:",wc)
f.close()
```

### OUTPUT:
![Screenshot_20230127_204303](https://user-images.githubusercontent.com/120643262/215120488-7c5ee72f-8e75-48dd-9657-44e0ae416f95.png)




## RESULT:
Thus the program is written to find the word count from a text.
