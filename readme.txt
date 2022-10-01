**This folder contains the following files:

---->makefile
---->File_System.cpp : cpp program file
___________________________________________________________________________________


**To compile and run File_System.cpp :

---->open this folder in ubuntu terminal
---->write the command "make" or "make run" in the terminal without quotes and press enter

The program will now run.

___________________________________________________________________________________


Commands:

--> mf file-name filecontents : Should create the file with the given file-name and file 
contents.

--> df file-name : delete the file from the directory.

--> rf file-name1 file-name2 :  rename the file from file1 to file2.

--> pf file-name : display all the contents of the file.

--> ls : Should display all the file-names and their inode number correctly.

___________________________________________________________________________________


**Sample input/output :

Enter command (To exit , enter "EXIT" without quotes): mf file1 this is file1
File Created!

Enter command (To exit , enter "EXIT" without quotes): mf file2 this is file2
File Created!

Enter command (To exit , enter "EXIT" without quotes): df file1
File deleted!

Enter command (To exit , enter "EXIT" without quotes): df file1
This file doesnot exists

Enter command (To exit , enter "EXIT" without quotes): rf file2 file3
file2 has been renamed to file3

Enter command (To exit , enter "EXIT" without quotes): pf file2
This file doesnot exist

Enter command (To exit , enter "EXIT" without quotes): pf file3
this is file2
Enter command (To exit , enter "EXIT" without quotes): mf file1 file1 returns
File Created!

Enter command (To exit , enter "EXIT" without quotes): mf file2 file2 returns
File Created!

Enter command (To exit , enter "EXIT" without quotes): ls


            FILENAME  INODE NUMBER
========================================
             file1       334
________________________________________
             file2       500
________________________________________
             file3       467
________________________________________


Enter command (To exit , enter "EXIT" without quotes): EXIT

