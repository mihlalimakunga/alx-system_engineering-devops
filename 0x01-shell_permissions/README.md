su betty: Switches the current user to the user betty.
id -un: Prints the effective username of the current user.
groups: Prints all the groups the current user is part of.
sudo chown betty hello: Changes the owner of the file hello to the user betty.
touch hello: Creates an empty file called hello.
chmod 744 hello: Adds execute permission to the owner of the file hello.
chmod 754 hello: Adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
chmod ugo+x hello: Adds execution permission to the owner, the group owner and other users, to the file hello.
chmod 007 hello: Sets no permission for user and group at all, sets all the permissions for other users.
chmod 753 hello: User has all permissions, group can only read and execute hello file and other users can write and execute hello file.    
