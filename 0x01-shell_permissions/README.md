su betty: Switches the current user to the user betty.
id -un: Prints the effective username of the current user.
groups: Prints all the groups the current user is part of.
sudo chown betty hello: Changes the owner of the file hello to the user betty.
touch hello: Creates an empty file called hello.
chmod 744 hello: Adds execute permission to the owner of the file hello.
chmod 754 hello: Adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
chmod ugo+x hello: Adds execution permission to the owner, the group owner and the other users, to the file hello.
chmod 007: Sets the permission to the file hello as follows: Owner has no permission at all, Group has no permission at all and Other users have all the permissions.
chmod 753: Sets the mode of the file hello to -rwxr-x-wx.
chmod --reference=olleh hello: Sets the mode of the file hello the same as olleh’s mode.
chmod ugo+x ./*: Adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files are not changed.
mkdir -m 751 my_dir: Creates a directory called my_dir with permissions 751 in the working directory.
chgrp school hello: Changes the group owner to school for the file hello.
chown vincent:staff ./*: Changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.
chwon -h vincent:staff _hello: Changes the owner and the group owner of _hello to vincent and staff respectively.
chown --from=guillaume betty hello: Changes the owner of the file hello to betty only if it is owned by the user guillaume.
telnet towel.blinkenlights.nl: Plays the StarWars IV episode in the terminal.
