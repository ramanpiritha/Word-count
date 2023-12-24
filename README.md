# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
```
PC
Anaconda - Python 3.7
```
## ALGORITHM: 
### Step 1:
Start the program

### Step 2: 
Get the text from the user
 
### Step 3: 
Write the function to count the words

### Step 4:  
Type the program to get the output

### Step 5: 
Print the number of words

### Step 6: 
End the program

## PROGRAM:
```
##Developed by:Piritharaman R
##Reference no:23013537

def count_words(text):
    words = text.split()
    return len(words)

if __name__ == "__main__":
   user_input = input("Enter a text: ")
   word_count = count_words(user_input)
   print(f"Word count: {word_count}")
```

### OUTPUT:

![exp 5a](https://github.com/ramanpiritha/Word-count/assets/147084116/120cfb93-354e-4b23-89b4-edf05732e93a)



## RESULT:
Thus the program is written to find the word count from a text.
