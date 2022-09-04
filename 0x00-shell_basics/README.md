0-current_working_directory- A Script that prints the absolute path name of the current working directory.

1-listit- A Script that displays the contents list of the current directory.

2-bring_me_home- A Script that changes the working directory to the user’s home directory. You are not allowed to use any shell variables.

3-listfiles- A Script that displays current directory contents in a long format.

4-listmorefiles- A Script that displays current directory contents, including hidden files (starting with .). Use the long format.

5-listfilesdigitonly- A Script that displays current directory contents in long format, with user & group IDs displayed numerically and hidden files (starting with .)

6-firstdirectory- A Script that creates a directory named my_first_directory in the /tmp/ directory.

7-movethatfile- A Script that moves the file betty from /tmp/ to /tmp/my_first_directory.

8-firstdelete- A Script that deletes the file betty. The file betty is in /tmp/my_first_directory.

9-firstdirdeletion- A Script that deletes the directory my_first_directory that is in the /tmp directory.

10-back- A Script that changes the working directory to the previous one.

11-lists- A Script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.

12-file_type- A Script  that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script. Note that depending on the file, the output of your script will be different.

13-symbolic_link- A Script that creates a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.

14-copy_html- A Script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory. You can consider that all HTML files have the extension .html

100-lets_move- A Script that moves all files beginning with an uppercase letter to the directory /tmp/u. You can assume that the directory /tmp/u will exist when we will run your script

101-clean_emacs- A Script that deletes all files in the current working directory that end with the character ~.

102-tree- A Script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory. You are only allowed to use two spaces (and lines) in your script, not more.


103-commas- A command that lists all the files and directories of the current directory, separated by commas (,). Directory names should end with a slash (/). Files and directories starting with a dot (.) should be listed. The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning. Only digits and letters are used to sort; Digits should come first. You can assume that all the files we will test with will have at least one letter or one digit. The listing should end with a new line

school.mgc- Create a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.
