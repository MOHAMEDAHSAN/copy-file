## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a file object and open it in 'w+' mode
### Step 2: 
Write the content into the file  
### Step 3: 
Move the cursor object to the start using seek() command 
### Step 4:  
Read the contents in the text file created
### Step 5: 
Create a new file object and open it in write mode
### Step 6: 
Write the contents read from the original text file
### Step 7:
Close both the file object/handle
## PROGRAM:
~~~Python
#Program to copy a text file
#Developed By : S MOHAMED AHSAN
#RegisterNumber: 23001044

f=open('Exp5c.txt','w+')
f.write('''BLACKPINK is a South Korean girl group formed by YG Entertainment
Consisting of members Jisoo, Jennie, Rose, and Lisa''')
f.seek(0)
r=f.read()
f1=open('Exp5c_clone.txt','w')
f1.write(r)
f.close()
f.close()
~~~
## OUTPUT:
#### Orginal Text File :
![org](/org.png)
#### Copy File :
![copy](/copy.png)

## RESULT:
Thus the program is written to copy the contents from one file to another file.