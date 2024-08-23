# ECE2112 - Advanced Computer Programming and Algorithms
## EXPERIMENT 1: INTRODUCTION TO PYTHON PROGRAMMING

### Custodio, Louise Angela G.
## 2ECE-D

**I. Intended Learning Outcomes**:
   1. To identify the basic codes and functions in Python Programming
   2. To be able to apply the different codes and functions in creating a Python program.


**II. Instructions**:
Write a Python script/code in the Jupyter Notebook to do the given problems.


## **Problems:** 


**ALPHABET SOUP PROBLEM**: Create a function that takes a string and returns a string with its letters
in alphabetical order.


**EMOTICON PROBLEM**: Create a function that changes specific words into emoticons. Given a sentence
as a string, replace the words smile, grin, sad, and mad with their corresponding emoticon.

![Screenshot 2024-08-23 003833](https://github.com/user-attachments/assets/1a033aa2-0960-4437-8663-a7dd19cd2255)

**UNPACKING LIST PROBLEM**: Unpack the list writeyourcodehere into three variables, being first, middle, and last, with middle being everything in between the first and last element. Then print all three
variables.


## How I did my code:

### **ALPHABET SOUP PROBLEM**

![Screenshot 2024-08-23 124552](https://github.com/user-attachments/assets/d73966e9-c448-4d0f-b087-6a26531b9d7b)


Step 1: Define the Function - I began by defining a function using the def keyword. The function is named alphabet_soup and takes one parameter called str, which represents the string that will be processed.

Step 2: Get User Input (Inside Function) - I utilized the ‘input()’ function to display a prompt asking the user to enter a word. It stores the user input in the variable ‘word’.

Step 3: Sort the Letters - I sorted the letters of the input string by applying the sorted() function to the word variable. This function returns a list of characters arranged in alphabetical order.

Step 4: Join the Sorted Letters - I utilized the .join() method to concatenate the sorted list of characters into a single string, ensuring there are no spaces between the characters.

Step 5: Print the Result - To display the final sorted string to the user, I used the print() function. This outputs the concatenated, sorted string.

Step 6: Call the Function - To execute the code, I attempted to call the alphabet_soup function with str as the argument. When the code runs, it prompts the user to type a word and then sorts the letters of that word alphabetically.

### **EMOTICON PROBLEM**

![Screenshot 2024-08-23 124631](https://github.com/user-attachments/assets/db6d77db-8248-4eb4-bbae-4ec0b24afe3d)

Step 1: Define the Function - I defined a function named ‘emotify’ using the ‘def’ keyword. The function takes one parameter called ‘str’, which represents the input string that will be processed.

Step 2: Check for Specific Words and Replace them - Inside the function, I used a series of if-elif statements to check for specific words in the input string and replace them with corresponding emoticons.

• Check for "smile": I used the condition ‘if("smile" in str)’ to see if the word "smile" is present in the string. If it is, it will replace with the emoticon ‘:)’.

• Check for "grin": If the word "grin" is found, it will replace with the emoticon ‘:D’.

• Check for "sad": If the word "sad" is present, it will replace with the emoticon ‘:(‘.

• Check for "mad": If the word "mad" is found, it will replace with the emoticon ‘>:(‘.

• Default Case: If none of the specific words are found, the else statement executes the pass keyword, which does nothing and leaves the string unchanged.

Step 3: Print the Result - After performing the replacements, I used the ‘print()’ function to display the modified string to the user.


Step 4: Call the Function with Various Inputs - To test the function, I called emotify with different strings to see how it handles various cases:

• This input contains the word "smile", so it should be replaced with ‘:)’.

• This input contains the word "grin", so it should be replaced with ‘:D’.

• This input contains the word "sad", so it should be replaced with ‘:(‘.

• This input contains the word "mad", so it should be replaced with ‘>:(‘.

### **UNPACKING LIST PROBLEM**

![Screenshot 2024-08-23 124713](https://github.com/user-attachments/assets/edbe16b0-e6c1-47ad-a811-71ceb1c8fbb2)

Step 1: Define the List - I started by defining a list named l that contains the integers from 1 to 6.

Step 2: Access and Print Elements - I used the ‘print()’ function to output specific elements and slices of the list. The ‘print()’ statement is designed to display: 

• First Element (‘1[0]’): Retrieves the element at index 0 of the list, which is the first item.

• Middle Elements (‘1[1:-1’]): Retrieves a slice of the list from index 1 up to, but not including, the last index. This effectively excludes the first and last elements.

• Last Element (‘1[-1]’): Retrieves the element at index -1, which is the last item in the list.

Step 3: Output the Result - The ‘print()’ function displays the retrieved elements and slices in a formatted string, showing the first element, the middle elements, and the last element.





