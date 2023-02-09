0-iam_betty (su betty) a script that switches the current user to the user betty

1-who_am_i (whoami) a script that prints the effective username of the current user

2-groups (groups)  a script that prints all the groups the current user is part of

3-new_owner (sudo chown betty hello) a script that changes the owner of the file hello to the user betty

4-empty (touch hello) a script that creates an empty file called hello

5-execute (chmod u+x hello) a script that adds execute permission to the owner of the file hello

6-multiple_permissions (chmod 554 hello) a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello

7-everybody (chmod 711 hello)  a script that adds execution permission to the owner, the group owner and the other users, to the file hello

8-James_Bond (chmod 007 hello)  a script that sets the permission to the file hello as follows owner no permission at all, Group no permission at all and Other users all the permission

9-John_Doe (chmod 753 hello) a script that sets the mode of the file hello to give the owner full permission, the group owner read and execute permissions and the other users the write and execute permissions

10-mirror_permissions (chmod --reference=olleh hello) a script that sets the mode of the file hello the same as olleh’s mode

11-directories_permissions (chmod -R ugo+X .) a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed

12-directory_permissions (mkdir -m 751 my_dir)  a script that creates a directory called my_dir with permissions 751 in the working directory

13-change_group (chgrp hello hello) a script that changes the group owner to school for the file hello

100-change_owner_and_group (chown -hR vincent:staff .) a script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory

101-symbolic_link_permissions (chown -hR vincent:staff _hello)  a script that changes the owner and the group owner of _hello to vincent and staff respectively

102-if_only () a script that changes the owner of the file hello to betty only if it is owned by the user guillaume

103-Star_Wars (telnet towel.blinkenlights.nl) a script that will play the StarWars IV episode in the terminal
