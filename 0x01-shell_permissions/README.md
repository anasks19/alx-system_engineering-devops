On this readme file all the permissions scripts used are explained 

The 0-iam_betyy is an executable file. Once the script is running, it switches from the current user to another user nammed betty

The 1-who_am_i is an executable file. The script of 1-who_am_i allow to print te effective username of the current user

The 2-groups file is an executable file that contains a script that prints all the groups the current user is part of

The 3-new_owner is an executable file. The Script inside allow to change the owner file hello to the user betty

The 4-empty file contains an script that creates an empty file called hello, once the script is running.

The 5-execute is an executable file containing a script. Once the script is running, it adds an execute (x) permession to the owner of the file.

The 6-mutiple_execute is an executable file. The script inside the file, allows to change permessions to files; including read (r), write (w) and execute (x) permessions for owner (u), group owner (g) and other users (o)

The 7-everybody file contains a script that adds execution permission to owner, group owenr and other users 

The 8-James_Bond file contains a Script. Once the script run, it gives full permission to others user and takes all permissions from Owner and group. (The script include hello file).

The 9-John_Doe is an executable file that sets the permissions of the hello file using octal notation method.

The 10-mirror_permissions is an executable file containing a script. This script once is running, it sets the mode of file hello the same as olleh's mode. (Setting permissions of hello's file as olleh's file).

The 11-directories_permissions is an executable file. The script in this file, adds execute (x) permession to all subdirectories of the wd for all users (owner, group and others).

The 12-directory_permissions contains a script that creates a directory named my_dir with -m option which allows us to specifie the mode (or permissions) of the directory.

The 13-change_group is an executable file. Once the script run, it change the group owner of hello file from root to school.

The 100-change_owner_and_group is an executable file. This command uses chown (short for "change owner") to change the owner and group owner for all files 
and directories in the current working directory (.). The -R option makes the operation recursive (i.e., it applies to all files and directories in subdirectories as well). 
The vincent:staff argument specifies the new owner and group owner, and the .* argument selects all files and directories in the current working directory (excluding hidden 
files and directories starting with .). The sudo command is used to run the command as a superuser (i.e., with root privileges) 
in case the current user doesn't have permission to change the owner or group owner.

The 101-symbolic_link_permissions is an executable file. This script will allow you to change the owner and the group owner of a symbolic link in your directory.

The 102-if_only is an executable file, containing a script that changes the current owner of a file only if it mathches the current owner of the specific file; in our case, the script 
changes the owner of hello file to betty only if it matches guillaume as the name if the current owner of the file.

The 103-Stars_Wars is an executable file using telnet protocol to desplay the SatrWars IV in the terminal once the script is running. 
