alias ls="rm *" : Script that creates an alias with the name "ls" and value "rm *".

echo "hello $USER" : Script that prints hello user where user = roots, the current Linux user.

export PATH=$PATH:/action : Adds /action to the PATH. /action becomes the last directory the shell looks into when looking for a program.

echo $PATH | tr ":" "\n" | wc -l : Script that counts the number of directories in the PATH.

printenv : Script that lists environment variables.

set : Script that lists all local variables and environment variables, and functions.

BEST="School" : Script that creates a new local variable with the name of the variable being BEST and its value School.

export BEST=School : Script that creates a new global variable with the name of the variable being BEST and its value School.

echo $((128 + $TRUEKNOWLEDGE)) : Script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.

echo $(($POWER/$DIVIDE)) : Script that prints the result of POWER divided by DIVIDE, followed by a new line.

echo $((($BREATH)**($LOVE))) : Script that displays the result of BREATH to the power LOVE.

echo $((2#$BINARY)) : Script that converts a number from base 2 to base 10.

echo {a..z}{a..z} | tr ' ' '\n' | grep -v oo : Script that prints all possible combinations of two letters, except oo.

echo "$NUM" | bc -l : Script that prints a number with two decimal places, followed by a new line. The number will be stored in the environment variable NUM.

printf "%.2f \n" $NUM : Script that prints a number with two decimal places, followed by a new line. The number will be stored in the environment variable NUM.

printf '%x\n' $DECIMAL : Script that converts a number from base 10 to base 16. The number in base 10 is stored in the environment variable DECIMAL.

tr 'a-zA-Z' 'n-za-mN-ZA-N' : Script that encodes and decodes text using the rot13 encryption, assumming ASCII.
