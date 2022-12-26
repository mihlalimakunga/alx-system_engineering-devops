alias ls="rm *" : Script that creates an alias with the name "ls" and value "rm *".

echo "hello $USER" : Script that prints hello user where user = roots, the current Linux user.

export PATH=$PATH:/action : Adds /action to the PATH. /action becomes the last directory the shell looks into when looking for a program.

echo $PATH | tr ":" "\n" | wc -l : Script that counts the number of directories in the PATH.

printenv : Script that lists environment variables.

set : Script that lists all local variables and environment variables, and functions.

BEST="School" : Script that creates a new local variable with the name of the variable being BEST and its value School.

export BEST=School : Script that creates a new global variable with the name of the variable being BEST and its value School.

echo $((128 + $TRUEKNOWLEDGE)) : Script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.

echo $(($POWER/$DEVIDE)) : Script that prints the result of POWER divided by DIVIDE, followed by a new line.
