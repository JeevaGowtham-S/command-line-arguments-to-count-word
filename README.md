# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
## Step 1:

Open vscode.
## Step 2:

Type the program.
## Step 3:

save the python file.
## Step 4:

create a text file .
## Step 5:

Run the program in the vscode, in the terminal type the following commands.
## Step 6:

End the program.

## PROGRAM:
```
# Developed by: JEEVAGOWTHAM S
# Reference no: 22008760
import sys
count={}
a=sys.argv[1]
with open(a,'r') as f:
    for line in f:
        for word in line.split():
            if word not in count:
                count[word]=1
            else:
                count[word]+=1
print(count)
f.close()
```

### OUTPUT:

# TEXT FILE:
![Screenshot from 2023-01-26 16-45-32](https://user-images.githubusercontent.com/118042624/214823019-ee03a2ae-57e3-4c1a-a0e5-c5b11e8863d5.png)
![Screenshot from 2023-01-26 16-44-24](https://user-images.githubusercontent.com/118042624/214823074-e8060556-489c-470d-9f9a-c128a45c38f9.png)




## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
