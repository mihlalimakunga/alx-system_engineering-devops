#!/bin/bash
echo "Hello, World": Prints "Hello, World" followed by a new line to the standard output.
"(Ôo)': Displays a confused smiley
cat /etc/passwd :Displays the contents of the file name /etc/passwd.
cat /etc/passwd /etc/hosts : Displays the contents of both files /etc/passwd and /etc/hosts.
tail -n10 /etc/passwd : Displays the last 10 lines of the file /etc/passwd.
head -n10 /etc/passwd : Displays the first 10 lines of the file /etc/passwd.
head -n 3 iacta|tail -1 : Displays the third line of the file name iacta.
echo "Best School" > "\*\\\'\"Best School\"\'\\\*$\?\*\*\*\*\*:)": Creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.
ls -la > ls_cwd_content : Redirects the standard output of ls -la to the ls_wcd_content file.
cat ./iacta | tail --lines=1 >> iacta : Duplicates the last line of file iacta into iacta_last_line_duplicate file.
find . -name "*.js" -type f -delete : Deletes all the regular files (not directories) with .js extension in the current directory and its subfolders.
find . -mindepth 1 -type d | wc -l : Counts the number of directories, sub directories and hidden directories in the current directory excluding the current directory itself.
ls -t | head -10 : Lists the 10 newest files in the current directory from newest to the oldest.
sort | uniq -u : Takes a list of words as input, sorts them out and prints only words that appear exactly once.
grep ^root /etc/passwd : Displays lines containing the pattern "root" from the file /etc/passwd.
grep -c bin /etc/passwd : Displays the number of lines that have the pattern "bin" in the file /etc/passwd.
grep -A 3 "root" /etc/passwd : Displays lines containing the pattern "root" followed by 3 lines after them in the file /etc/passwd.
grep -v bin /etc/passwd : Displays all the lines that exclude "bin" pattern in them in the file /etc/passwd.
cat /etc/ssh/sshd_config | grep "^[[:upper:]]" : Displays all lines of the file /etc/ssh/sshd_config starting with a letter and including capital letters.
tr Ac Ze : Replaces all the characters A and c from input to Z and e respectively.
tr -d 'cC' : Removes all letters c and C from input.
rev : Reverses its input.
cat /etc/passwd | sort -k1 | cut -d ':' -f1,6 : Displays all users and their home directories, sorted by users.
find . -empty -printf '%f\n' : Finds all empty files and directories in the current directory and all sub-directories.
