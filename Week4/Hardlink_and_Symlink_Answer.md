#### Q1. The user uses the ‘mkdir.txt’ file quite frequently. It is difficult for the user to access the ‘mkdir.txt’ file as the user needs to go through the path ‘/home/user/MyPC/Documents/Week2/DirectoryManagement/mkdir.txt’ to access the file. Can you help the user to create a shortcut of the ‘mkdir.txt’ file in the ‘Desktop’ directory with the name ‘mkdirSt’ so that user can access the file easily.
Ans. ln -s /home/user/MyPC/Documents/Week2/DirectoryManagement/mkdir.txt   /home/user/MyPC/Desktop/mkdirSt

#### Q2. As the ‘mkdir.txt’ file is important, create a backup of the file ‘mkdir.txt’ and name it as ‘mkdirBk’ in the ‘Backups’ directory as shown in the below diagram. (If the ‘mkdir.txt’ file content is modified, it’s automatically reflected in the ‘mkdirBk’ and vice-versa).
Ans. ln  /home/user/MyPC/Documents/Week2/DirectoryManagement/mkdir.txt  /home/user/MyPC/Backups/mkdirBk

#### Q3. As we already have a backup, remove the ‘mkdir.txt’ file from the ‘DirectoryManagement’ directory and try to access it through the shortcut ‘mkdirSt’ and through the backup ‘mkdirBk’. Record the differences and the reasons behind them.
Ans. To remove the ‘mkdir.txt’ file from the ‘DirectoryManagement’ directory, use the command:
       rm /home/user/MyPC/Documents/Week2/DirectoryManagment/mkdir.txt

When we try to access the file through the shortcut ‘mkdirSt’, we will not be able to access the file as this was a shortcut pointing to the location of the original file and the original file ‘mkdir.txt’ has been deleted.

When we try to access the file through the file ‘mkdirBk’, we will see the same content as it was in the original ‘mkdir.txt’ file. The backup file ‘mkdirBk’ has the same i-node number as the original ‘mkdir.txt’ file. Even if the original file is deleted, the backup file's content remains.

#### Q4. As the directory management commands will be used again and again, create a shortcut to the ‘DirectoryManagement’ directory in the ‘Desktop’ folder and name it as 'DirectoryManagementSt'.
Ans. ln -s  /home/user/MyPC/Documents/Week2/DirectoryManagement  /home/user/MyPC/Desktop/DirectoryManagementSt

#### Q5. Create a backup of the ‘DirectoryManagement’ directory in the ‘Backups’ directory and name it as ‘DirectoryManagementBk’ (If we change the content of the ‘DirectoryManagement’, it should automatically be reflected in the ‘DirectoryManagementBk’ directory).
Ans. We can’t create directory backups using the hard links. Other ways may be possible and search on your own and we will discuss in the next sessions.
