0-current_working_directory- prints the absolute path name of the current working directory.
1-listit- Displays the contents list of my current directory.
2-bring_me_home- changes the working directory to the user’s home directory.
3-listfiles- Displays current directory contents in a long format.
4-listmorefiles- Displays current directory contents, including hidden files (starting with .). It uses the long format.
5-listfilesdigitonly- Display current directory contents.
Long format
with user and group IDs displayed numerically
And hidden files (starting with .)
6-firstdirectory- Creates a script that creates a directory named my_first_directory in the /tmp/ directory.
7-movethatfile- Move the file betty from /tmp/ to /tmp/my_first_directory
8-firstdelete- Delete the file betty.
The file betty is in /tmp/my_first_directory
9-firstdirdeletion- Delete the directory my_first_directory that is in the /tmp directory.
10-back- Write a script that changes the working directory to the previous one.
11-lists- Writes a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
12-file_type- Writes a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.
13-symbolic_link- Creates a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.
14-copy_html- Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory. assuming HTML files have a .html extension.
100-lets_move- Create a script that moves all files beginning with an uppercase letter to the directory /tmp/u. Assuming /tmp/u is already available.
101-clean_emacs- Creates a script that deletes all files in the current working directory that end with the character ~
102-tree- Creates a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.
103-commas- command that lists all the files and directories of the current directory, separated by commas (,).
school.mgc- Creates a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.
