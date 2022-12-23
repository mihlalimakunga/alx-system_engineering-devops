su betty: Switches the current user to the user betty.
id -un: Prints the effective username of the current user.
groups: Prints all the groups the current user is part of.
sudo chown betty hello: Changes the owner of the file hello to the user betty.
touch hello: Creates an empty file called hello.
chmod 744 hello: Adds execute permission to the owner of the file hello.
chmod 754 hello: Adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
chmod ugo+x hello: Adds execution permission to the owner, the group owner and the other users, to the file hello.
chmod 007: Sets the permission to the file hello as follows: owner has no permissions at all, group has no permissions at all and all other users have all the permissions.
chomd 753 hello: Sets the mode of the file hello to -rwxr-x-wx.
chmod --reference=olleh hello: Sets the mode of the file hello the same as olleh’s mode.
