#!/bin/bash
echo "Hello, World": Prints "Hello, World" followed by a new line to the standard output.
"(Ôo)': Displays a confused smiley
cat /etc/passwd :Displays the contents of the file name /etc/passwd.
cat /etc/passwd /etc/hosts : Displays the contents of both files /etc/passwd and /etc/hosts.
tail -n10 /etc/passwd : Displays the last 10 lines of the file /etc/passwd.
head -n10 /etc/passwd : Displays the first 10 lines of the file /etc/passwd.
head -n 3 iacta|tail -1 : Displays the third line of the file name iacta.
echo "Best School" > \*\\'"Best School"\'\\*$\?\*\*\*\*\*:)
ls -la > ls_cwd_content : Redirects the standard output of ls -la to the ls_wcd_content file.
tail -n 1 iacta >> iacta_last_line_duplicate : Duplicate the last line of file iacta into iacta_last_line_duplicate file.
find . -name "*.js" -type f -delete : Deletes all the regular files (not directories) with .js extension in the current directory and its subfolders.
find . -mindepth 1 -type d | wc -l : Counts the number of directories, sub directories and hidden directories in the current directory excluding the current directory itself.
ls -t | head -10 : Lists the 10 newest files in the current directory from newest to the oldest.
sort | uniq -1 : Takes a list of words as input, sorts them out and prints only words that appear exactly once.
grep ^root /etc/passwd : Displays lines containing the pattern "root" from the file /etc/passwd.
grep -n bin /etc/passwd : Displays the number of lines that have the pattern "bin" in the file /etc/passwd.
