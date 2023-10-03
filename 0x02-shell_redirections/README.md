This README.md contains all the scripts for the "0x02. Shell, I/O Redirections and filters" project

Below, you will find the different scripts:

0-hello_world : prints “Hello, World”, followed by a new line to the standard output

1-confused_smiley : displays a confused smiley "(Ôo)'

2-hellofile : Displays the content of the /etc/passwd file

3-twofiles : Displays the content of /etc/passwd and /etc/hosts

4-lastlines : Displays the last 10 lines of /etc/passwd

5-firstlines : Displays the first 10 lines of /etc/passwd

6-third_line : Displays the third line of the file iacta

7-file : Creates a file named exactly '\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)' containing the text Best School

8-cwd_state : Writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it overwrites it. If the file ls_cwd_content does not exist, it creates it

9-duplicate_last_line : Duplicates the last line of the file iacta

10-no_more_js : Deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders

11-directories : Counts the number of directories and sub-directories (even hidden ones) in the current directory and without taking into account the curent and parent directories

12-newest_files : Displays the 10 newest files in the current directory one file at a time, from newest to oldest

13-unique : Takes a list of words as input and prints only words that appear exactly once

14-findthatword : Displays the lines containing the pattern “root” from the file /etc/passwd

15-countthatword : Displays the number of lines that contain the pattern “bin” in the file /etc/passwd

16-whatsnext : Displays the lines containing the pattern “root” and 3 lines after them in the file /etc/passwd

17-hidethisword : Displays all the lines in the file /etc/passwd that do not contain the pattern “bin”

18-letteronly : Displays all lines of the file /etc/ssh/sshd_config starting with a letter

19-AZ : Replaces all characters A and c from input to Z and e respectively

20-hiago : Removes all letters c and C from input

21-reverse : Reverses the input

22-users_and_homes : Displays all users of the /etc/passwd file and their home directories, sorted by users

100-empty_casks : Finds all empty files and directories in the current directory and all sub-directories. Only the names of the files are displayed, Hidden files are listed, Prints one file per line.

101-gifs : Lists all the regular files with a .gif extension in the current directory and all its sub-directories, listing hidden files aswell,the extensions are not displayed, the files are sorted by byte value and case insensitive, listing one file per line

102-acrostic : Decodes acrostics that use the first letter of each line

103-the_biggest_fan : parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests, from most active host to least active
