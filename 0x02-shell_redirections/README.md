This file contains tutorial on Shell, I/O Redirections and filters

It contains information about the function of each sript-file in this directory does

0-hello_world		prints "Hello, World".
1-confused_smiley	displays a confused smiley.
2-hellofile		displays a the content of the /etc/passwd file.
3-twofiles		displays the content of /etc/passwd and /etc/hosts.
4-lastlines		displays the last 10 lines of /etc/passwd.
5-firstlines		displays the last 10 lines of /etc/passwd.
6-third_line		displays the third line of the file iacta.
7-file			creates a file exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.
8-cwd_state		writes into the file ls_cwd_content the result of the command ls -a. if the file ls_cwd_content already exists, it shoud be overwritten. If the file ls_cwd_conten does not exist, it creates it.
9-duplicate_last_line	duplicates the last line of the file iacta.
10-no_more_js		deletes all the reqular files (not the directories) with a .js extension that are present in the current directory and all its subfolders
11-directories		counts the number of directories and sub-directories in the current directory.
				<>The current andp parent directories should not be taken into account.
				<>Hidden directories should be counted.
12-newest_files		displays the 10 newest files in the current directory.
13-unique		takes a list of words as input and prints only words that appear exactly once.
				<>Inpu format:One line, one word
				<>Output format: one line, one word
				<>Words should be sorted
14-findthatword			display lines containing the pattern "root" from the file /etc/passwd.
15-countthatword	display the number of lines that contain the pattern "bin in the file /etc/passwd.
16-whatsnext		displays lines containing the pattern "root" lines after them in the file /etc/passwd.
17-hidethisword		displays all the lines in the file /etc/passwd that do not contain the pattern "bin".
18-letteronly		displays all the lines in the file /etc/ssh/sshd_config starting with a letter.
				<>include capital letters as well	
19-AZ			replace all characters A and c from input to z and e respectively.
20-hiago		removes all letters c and C from the input.
21-reverse		reverse its input.
22-user_and_homes	displays all users and their home directories, sorted by users.
				<>based on the /etc/passwd file
