0-iam_betty (su betty) a script that switches the current user to the user betty

1-who_am_i (whoami) a script that prints the effective username of the current user

2-groups (groups)  a script that prints all the groups the current user is part of

3-new_owner (sudo chown betty hello) a script that changes the owner of the file hello to the user betty

4-empty (touch hello) a script that creates an empty file called hello

5-execute (chmod u+x hello) a script that adds execute permission to the owner of the file hello

6-multiple_permissions (chmod 554 hello) a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello

7-everybody (chmod 711 hello)  a script that adds execution permission to the owner, the group owner and the other users, to the file hello
