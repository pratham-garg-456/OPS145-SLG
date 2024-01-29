#### Q1. The user wants to know about all the CS (Computer Science) related courses. Write a command to view all the course files that start with ‘cs’ in the ‘Courses’ directory (including all the sub directories).
Ans. find /home/user/Courses -name “cs*”

#### Q2. There are two files ‘cs102.txt’ and ‘cs445.txt’ in the ’Sem1’ directory. How can you compare both the files and know the differences between both the courses?
Ans. diff /home/user/Courses/Sem1/cs102.txt    /home/user/Courses/Sem1/cs445.txt

#### Q3. There has been a mistake in the ‘cs667.txt’ file. Instead of using the word ‘cs667’ or ‘CS667’ in the file, the word ‘cs668’ or ‘CS668’ have been used repeatedly. The user wants to find out all the lines which contain the word ‘cs668’ or ‘CS668’, so that the user can correct those lines. Can you provide a solution?
Ans. grep -i “cs668” /home/user/Courses/Sem3/cs667.txt

#### Q4. The ‘htm334.txt’ contains the list of topics that need to be taught in this course. The format of file is:
 ![image](https://github.com/pratham-garg-456/OPS145-SLG/assets/81003075/e59662e3-f2be-405d-aee9-e2e2499b73b5)

#### Above are just random topics listed. All the topic names are in lower case. Surprisingly, the course is such that all the topics need to be taught in a reverse alphabetical order (the topic that starts with 'z' is taught first than that starts with 'a'). The topic names in the file are mixed up. Is there any way you can make it easy for the instructor to search for the topics to be taught? (Maybe think of sorting !!!)
#### Follow up: Can you provide a solution if topic names are in mixed case (upper and lowercase both)?

Ans. sort -r /home/user/Courses/Sem3/htm334.txt
Follow up: Discuss in the next session.
