# Shell Permissions

## My name is Betty

- Script File that switches the current user to the user ```betty```


## Who am I
- Script file that prints the effective username of the current user.


## Groups
- Script file that prints all the groups the current user is part of.

## New owner
- Script file that changes the owner of the file ```hello``` to the user betty.

## Empty!
- Script file that creates an empty file called ```hello```.

## Execute
-  Script file that adds execute permission to the owner of the file ```hello```. 
-  Considering that the file ```hello``` exists in the current directory.

## Multiple permissions
- Script file that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.

## Everybody!
- Script file that adds execution permission to the owner, the group owner and the other users, to the file ```hello```
- The file ```hello``` will be in the working directory
- You are not allowed to use commas for this script

## James Bond
- Script file that sets the permission to the file ```hello``` as follows:
- Owner: no permission at all
- Group: no permission at all
- Other users: all the permissions

##  John Doe
- Script that sets the mode of the file ```hello``` to this:
- ```rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello```
- The file hello will be in the working directory
- You are not allowed to use commas for this script

##  Look in the mirror
- Script file that sets the mode of the file hello the same as olleh’s mode.

##  Directories
- Script file that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.

## More directories
- Create a script that creates a directory called ```my_dir``` with permissions 751 in the working directory.

## Owner and group
- Script file that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.

## Symbolic links
-  script that changes the owner and the group owner of _hello to vincent and staff respectively.
-  The file _hello is in the working directory
-  The file _hello is a symbolic link

## If only
- Script file that changes the owner of the file hello to betty only if it is owned by the user guillaume.
- The file hello will be in the working directory

## Star Wars
-  Script file that will play the StarWars IV episode in the terminal.





