### Q1. Which of the lines from the file will be selected when using this command: grep "in" Week10.txt

//Week10.txt 

<img width="930" alt="image" src="https://github.com/pratham-garg-456/OPS145-SLG/assets/81003075/fc844471-91f8-48cc-9f49-077a5b98422c">

1. We are learning regular expression this week.
2. Regular expressions are used to search, edit and manupulate text. 
3. This can represent text contained in a file like this one or within a pipeline command for example: 
4. ls | grep ".txt" -> this command will display the text files in current directory.
5. regular expressions are used with commands that matches patterns contained in text such as:
6. grep, egrep, man, more, less, vi, sed and awk
7. The problem with simple regular expression is that only simple patterns are matched which we have seen through this question.


### Q2. Which of them are complex regular expression symbols:

1. Repetition {min, max}, ?, +
2. Single Character . 
3. negation [! ]
4. Character Class [], [^ ]
5. zero or More Occurence *
6. Grouping ( )
7. Any Character ?
8. Repetition {min, max}, ?, +
9. or Condition |
10.Anchors ^, $


### Q3. which of the symbols are Entended Regular expressions from the previous question


## Questions grep and egrep:


### 1. Write a Linux command to display all lines in the file called ~/week10_slg.txt that begins with an signed integer and ends with UPPERCASE letter. It can have any number of characters in the middle.

### 2. Write a Linux command to display all lines in the file called ~/week10_slg.txt that begins with 1 or more occurrences of a lowercase letter and ends with a digit and should have a [NEGATIVE or POSITIVE] sign in tenth's place (to be more clear, at second last positon). It can have any number of characters in the middle.

### 3. Write a Linux command to display all lines in the file called ~/week10_slg.txt that contains exactly 3 numbers !!

### 4. Write a Linux command to display all lines in the file called ~/week10_slg.txt that begins with exactly 3 occurrences of a lowercase letter and ends with a digit (5 or 3 or 2). It should have "X" (uppercase) in the middle. (USE egrep ore grep -E and not just grep command in this QUESTON)!!

### 5. Write a Linux command to display all lines in the file called ~/week10_slg.txt that begins with a signed/unsigned integer and must end with 0 or 1 occurence of a alphabet (lowecase or uppercase). It should have "-" or "+" symbol anywhere in the middle.

### 6. Write a Linux command to display all lines in the file called ~/week10_slg.txt that begins with just 1 occurrence of a lowercase or uppercase letter "z" and ends with a letter "f" (uppercase or lowercase). It should have MININUM 2 and MAXIMUM 4 digits or exactly two occurence of string "slg" anywhere in between.

### 7. Write a Linux command to display all lines in the file called ~/week10_slg.txt that begins with 1 or more occurrences of the word “the ” AND ends with minimum 1 and a maximum of 3 occurences of word "yes " or just the word “but ” (upper or lower case).
