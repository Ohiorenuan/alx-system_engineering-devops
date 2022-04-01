0-current_working_directory prints the absolute path name of the current working directory
1-list displays the contents of your current directory
2-bring_me_home changes the working directory to the user's home directory
3-listfiles displays the current contents in a long format
4-listmorefiles display ALL directory contents
5-listfilesdigitonly display ALL current directory contents in long format, with user and group IDs displayed numerically
6-firstdirectory creates the directory my_first_directory in /tmp/
7-movethatfile moves the file betty from /tmp/ to /tmp/my_first_directory
8-firstdelete deletes /tmp/my_first_directory/betty
9-firstdirdeletion deletes /tmp/my_first_directory/
10-back changes the working directory to the previous one
11-lists lists ALL files in the current directory, the parent of the working directory and /boot in this order, long format
12-file_type prints the type of the file named iamafile in /tmp directory
13-symbolic_link creates a symlink to /bin/ls named __ls__ in the current working directory
14-copy_html copies all the HTML files from the working directory to the parent of the working directory not existing or newer than the versions in the parent of the working directory
100-lets_move moves all files beginning with an uppercase letter to the directory /tmp/u/
101-clean_emacs deletes all files in the current working directory that end with the character ~
102-tree creates the directories welcome/, welcome/to and welcome/to/school
103-commas lists ALL the files and directoris of the current directory seperated by commas, directories end with slash, listing is alpha ordered with digits and letters used to sort
school.mgc is used with the command file to detect School data files. School data fies always contain the string SCHOOL at offset 0