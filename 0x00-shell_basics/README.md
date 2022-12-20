pwd : A script that prints the absolute path name of the current working directory.
ls : A script that displays the contents list of your current directory.
cd : A script that changes the working directory to the user’s home directory.
ls -l : A script that displays current directory contents in a long format.
ls -l -a : A script that displays current directory contents, including hidden files (starting with .) using the long format.
ls -n -a : A script that displays current directory contents, including hidden files (starting with .) using the long format and with user and group IDs displayed numerically.
mkdir /tmp/my_first_directory : A script that creates a directory named my_first_directory in the /tmp/ directory.
mv /tmp/betty /tmp/my_first_director : A script that moves the file betty from /tmp/ to /tmp/my_first_directory.
rm /tmp/my_first_directory/betty : A script that deletes the file betty in /tmp/my_first_directory directory.
rm -r /tmp/my_first_directory : A script that deletes the directory my_first_directory that is in the /tmp directory.
cd - : A script that changes the working directory to the previous one.
ls -a -l . .. /boot : A script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
file /tmp/iamafile : A script that prints the type of the file named iamafile which is in the /tmp directory.
ln -s /bin/ls __ls__ : A script that creates a symbolic link to /bin/ls, named __ls__.
cp *.html /. /.. : a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
