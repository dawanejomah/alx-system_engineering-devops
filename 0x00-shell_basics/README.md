1. pwd: a script that prints the absolute path name of the current working directory
2. ls: displays the contents list of your current directory
3. cd: a script that changes the working directory to the user’s home directory
4. ls -l:display current directory contents in a long format
5. ls -al: display current directory contents including hidden files
6. ls -aln: list files digit only
7. mkdir /tmp/my_first_directory: a script that creates a directory named my_first_directory in the /tmp/ directory
8. mv /tmp/betty /tmp/my_first_directory: Move the file betty from /tmp/ to /tmp/my_first_directory
9. rm /tmp/my_first_directory/betty: delete the file betty
10. rmdir /tmp/my_first_directory: delete the directory my_first_directory that is in the /tmp directory
11. cd - a script that changes the working directory to the previous one
12. ls -al . .. /boot a script that lists all files even ones with names beginning with a period charactern the current directory and the parent of the working directory and the /boot directory (in this order) in long format
13. file /tmp/iamafile a script that prints the type of the file named iamafile
14. ln -s /bin/ls __ls__ create a symbolic link to /bin/ls, named __ls__
15. cp -un *.html ../ a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
16. mv [[:upper:]]* /tmp/u a script that moves all files beginning with an uppercase letter to the directory /tmp/u
rm *~  a script that deletes all files in the current working directory that end with the character ~
17. mkdir -p welcome/to/school a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory
18. ls -amvp a command that lists all the files and directories of the current directory, separated by commas
19. 0 string SCHOOL School data
!:mime School creates a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0. 
