alias ls="rm *" : Script that creates an alias with the name "ls" and value "rm *".

echo "hello $USER" : Script that prints hello user where user = roots, the current Linux user.

export PATH=$PATH:/action : Adds /action to the PATH. /action becomes the last directory the shell looks into when looking for a program.

find $PATH -type d | wc -l : Script that counts the number of directories in the PATH.
