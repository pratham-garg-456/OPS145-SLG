### Q1. What is a directory?
Ans. A folder in linux Operating system is called directory.<img width="52" alt="Directory" src="https://github.com/pratham-garg-456/OPS145-SLG/assets/81003075/7cca2a5c-19e0-4146-a10f-d1fb2797c6f3">

### Q2. What is a path or pathname in context to directories or file system?
Ans.  filename that includes information about the directory in which the file is stored.
<img width="954" alt="Screenshot 2024-01-20 120810" src="https://github.com/pratham-garg-456/OPS145-SLG/assets/81003075/91a563e9-a95f-4e3f-b173-403e65cb332f">



### Q3.
<img width="362" alt="tree" src="https://github.com/pratham-garg-456/OPS145-SLG/assets/81003075/b9e33036-2cea-469e-9cb7-37e0dbf19814">

### Write the path from your current directory to who.txt
Ans. OPS145/Week3/Revision/who.txt

### Q4. Write the command to create OPS145 directory
Ans. mkdir OPS145

### Q5. Write a single command to create Revision directory and Week3 directory together and Revision directory is inside Week3 directory
Ans. mkdir -p OPS145/Week3/Revision

### Q6. 
<img width="464" alt="FileType" src="https://github.com/pratham-garg-456/OPS145-SLG/assets/81003075/dd1c27c9-a4e5-45b3-a188-3fc94a84d1e2">

### What is the meaning of the first character on the left of the output of ls -l command.
Ans. File type

d : directory

'-' : regular file

b or c : device file

### Q7. 
<img width="287" alt="Screenshot 2024-01-20 131705" src="https://github.com/pratham-garg-456/OPS145-SLG/assets/81003075/4254343f-b8d2-417d-b0b4-90bc4ab30319">

### Go inside Revision directory and write a single command to create all these text files.
Ans. touch cd.txt date.txt exit.txt ls.txt man.txt pwd.txt who.txt

### Q8. 
<img width="350" alt="vi" src="https://github.com/pratham-garg-456/OPS145-SLG/assets/81003075/eea83b81-a0fd-4737-ac08-03e7df22af67">

### Using vi text editor put the following text shown by my cat comand in exit.txt file.
Ans. vi exit.txt -> type i to go insert mode -> type the text -> click ESC to go in command mode -> type ":wq"

### Q9. Now write a single command to copy the content of exit.txt to a new file logout.txt
Ans. cp exit.txt logout.txt

### Q10. Create Week2 directory in OPS145 directory
Ans. mkdir ~/OPS145/Week2 OR mkdir /home/(your username)/OPS145/Week2

### Q11. 


