# Documented linux commands

$ mkdir directory-name - used to create folder

$ touch file-name - primary function is to modify a timestamp, but I used it to create a file

$ ls – list directory contents

$ man command - manual on how to use command

$ ssh username@ip -p port - used to connect to ssh server

$ logout - used to close ssh connection

$ cat file-name - used to see content of file

$ cat ./- - used to check content of fiel named "-", to print it out we need to give path to that file instead of just name

$ cat "file name with spaces" - if we want to print content of file that has spaces in its name

$ cd directory-name - change current working directory

$ ls -a - list directory hidden content

$ ls -l - this shows a lot more information presented to the user than the standard command

$ file directoryname/\* - this is used to display all files filetypes in particular directory

$ find -readable -size 1033c ! -executable - finding file which is readable, is 1033 bytes and not executable

$ find / -type f -user bandit7 -group bandit6 -size 33c 2>/dev/null - find file type f, owned by user bandit8, owned by group bandit6 and is 33 bytes in size, 2>/dev/null hide permission denied error

$ grep - prints the matching lines.

$ sort data.txt | uniq -c | grep '^ \*1 ' - sort is sorting lines of text files, | is a pipeline, uniq - report or omit repeated lines,

$ strings - finds human-readable strings in files.

$ cat data.txt | base64 -d - encode data