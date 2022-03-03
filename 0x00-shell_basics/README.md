#Shell Basics

- 0-current\_working\_directory script file has command that prints the absolute path name of the current working directory
- 1-listit script file has the command that display the contents list of your current directory
- 2-bring\_me\_home script file that changes the working directory to the user’s home directory
- 3-listfiles script file that display current directory contents in a long format
- 4-listmorefiles script file that display current directory contents, including hidden files (starting with .). Use the long format.
- 5-listfilesdigitonly script file that display current directory contents in long format with user group IDs in numerical formats and any hidden files.
- 6-firstdirectory script file to Create a script that creates a directory named my\_first\_directory in the /tmp/ directory
- 7-movethatfile script file to Move the file betty from /tmp/ to /tmp/my\_first\_directory
- 8-firstdelete script file to delete the file betty from /tmp/my\_first\_directory/betty
- 9-firstdirdeletion script file to delete the directory /tmp/my\_first\_directory
- 10-back script file that changes the working directory to the previous one
- 11-lists script file that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format
- 12-file\_type script file that prints the type of the file named iamafile. The file is in /tmp
- 13-symbolic\_link script file that Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.
- 14-copy\_html script file that Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
- 100-lets\_move script file that Create a script that moves all files beginning with an uppercase letter to the directory /tmp/u
- 101-clean\_emacs script file that Create a script that deletes all files in the current working directory that end with the character ~
- 102-tree script file that Create a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.
- 103-commas script file that Write a command that lists all the files and directories of the current directory, separated by commas (,).

Directory names should end with a slash (/)
Files and directories starting with a dot (.) should be listed
The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning
Only digits and letters are used to sort; Digits should come first
You can assume that all the files we will test with will have at least one letter or one digit
The listing should end with a new line
- school.mgc script file that Create a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.

