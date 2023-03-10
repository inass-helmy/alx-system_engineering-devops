su betty :  a script that switches the current user to the user betty
whoami: a script that prints the effective username of the current user
groups: a script that prints all the groups the current user is part of
chown betty hello: script that changes the owner of the file hello to the user betty
touch hello: a script that creates an empty file called hello
chmod u+x hello: script that adds execute permission to the owner of the file hello
chmod 754 hello: adds execute permission to the owner and the group owner, and read permission to other users, to the file hello
chmod 007 hello :Write a script that sets the permission to the file hello as follows: Owner: no permission at all, Group: no permission at all, Other users: all the permissins
chmod ugo+x hello:a script that adds execution permission to the owner, the group owner and the other users, to the file hello
chmod 753 hello : giv -rwxr-x-wx to hello
chmod --reference=olleh hello: a script that sets the mode of the file hello the same as olleh’s mode.
chmod -R ugo+x : script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users
