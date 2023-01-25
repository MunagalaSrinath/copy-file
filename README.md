# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:First we need to open the required file form which we need to copy the text.Again using the with keyword to open the empty file.

### Step 2: Using keyword "with" to open the requied file.


 
### Step 3: Again using the with keyword to open the empty file.

### Step 4: The empty file is open by using 'W' which is used to write only. 

### Step 5: The four function is used to take each line from the main file.



### Step 6: The four function is used to take each line from the main file.

## PROGRAM:
```
developde by: M Srinath
registered number: 22000990
with open("git.txt","r") as f1:
    with open("MyFile.txt","a") as f2:
        for line in f1:
            f2.write(line)

## OUTPUT:

![214654707-d421820c-cedd-4226-8bdb-b915f03ef6d5](https://user-images.githubusercontent.com/118678482/214665012-b67deae9-034a-456c-a466-b40fec69c075.png)


![214654839-ddf1e414-1a51-4a08-8000-6bdceaa83180](https://user-images.githubusercontent.com/118678482/214665180-1c1653ce-4b29-440e-aa9f-634a2286f1c0.png)


![214654937-d52d6e5c-ed88-42cd-88e3-e6c33d70decc](https://user-images.githubusercontent.com/118678482/214665293-0a9b8e89-ebe5-41e2-83ef-fbff73f2567f.png)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
