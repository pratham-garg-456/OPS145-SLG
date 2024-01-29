##### Hard and Symbolic links commands and different options related to it: ln, ln -s	

## Assume the home directory is ‘/home/user’. The below diagram shows the file structure of the ‘MyPC’ directory which is in the home directory.
### Answer the questions assuming the current working directory is unknown.

 ![image](https://github.com/pratham-garg-456/OPS145-SLG/assets/81003075/6b11454b-c111-45b7-90f1-b68d2bb11324)

Questions:
#### 1.	The user uses the ‘mkdir.txt’ file quite frequently. It is difficult for the user to access the ‘mkdir.txt’ file as the user needs to go through the path ‘/home/user/MyPC/Documents/Week2/DirectoryManagement/mkdir.txt’ to access the file. Can you help the user to create a shortcut of the ‘mkdir.txt’ file in the ‘Desktop’ directory with the name ‘mkdirSt’ so that user can access the file easily.

#### 2.	As the ‘mkdir.txt’ file is important, create a backup of the file ‘mkdir.txt’ and name it as ‘mkdirBk’ in the ‘Backups’ directory as shown in the below diagram. (If the ‘mkdir.txt’ file content is modified, it’s automatically reflected in the ‘mkdirBk’ and vice-versa).
 ![image](https://github.com/pratham-garg-456/OPS145-SLG/assets/81003075/94f19fdc-a34e-49c9-be97-eb188ca94a2b)

#### 3.	As we already have a backup, remove the ‘mkdir.txt’ file from the ‘DirectoryManagement’ directory and try to access it through the shortcut ‘mkdirSt’ and through the backup ‘mkdirBk’. Record the differences and the reasons behind them.
 ![image](https://github.com/pratham-garg-456/OPS145-SLG/assets/81003075/7da9075e-4ce9-42f7-909d-14726407ae84)

#### 4.	As the directory management commands will be used again and again, create a shortcut to the ‘DirectoryManagement’ directory in the ‘Desktop’ folder and name it as 'DirectoryManagementSt'.
In the below diagram relative path ‘../Documents...’ is used, use the one taught in session ‘/home/user...’
 ![image](https://github.com/pratham-garg-456/OPS145-SLG/assets/81003075/7b85cb5d-d7e6-4c9b-8b1c-1723322a271a)

#### 5.	Create a backup of the ‘DirectoryManagement’ directory in the ‘Backups’ directory and name it as ‘DirectoryManagementBk’ (If we change the content of the ‘DirectoryManagement’, it should automatically be reflected in the ‘DirectoryManagementBk’ directory).	
