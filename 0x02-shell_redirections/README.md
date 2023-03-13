
Discriptions

0. Command echo prints out Hello, World to the standard output
1. Command echo prints out a confused smiley, but we have to exit the escape characters.
2. Command cat displays the content of the /etc/passwd file.
3. Command cat displays the content of the file /etc/passwd and /etc/hosts.
4. Command tail displays the last 10 lines of /etc/passwd file.
5. Command head displays the first 10 lines of /etc/passwd file.
6. Command head -3 iacta | tail -1 displays the third line of the iacta file.
7. Command echo creates a file named \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text "Best school", but we have to escape the special characters in the file name.
8. Command ls -l with a >> writes into the file ls_cwd_content without overwritting it.
9. Command tail -1 iacta >> iacta duplicates the last line of the iacta file
10. Command find . -type f -name "*.js" -delete deletes all the regular files  but not the directories with a .js extentions that are present in the current directory and all its subfolders.
11. Command find -type d -not -name '.' | wc -l writes a script that counts the number of directories and sub-directories in the current directory12. Command ls -t1 | head Creates a script that displays the 10 newest files in the current directory.
13. command sort | uniq -u Creates a script that takes a list of words as input and prints only words that appear exactly once.
14. Command grep -i "root" /etc/passwd displays lines containing the pattern “root” from the file /etc/passwd.
15. Command grep -i "bin" /etc/passwd |wc -l displays the number of lines that contain the pattern “bin” in the file /etc/passwd
16. Command egrep -A 3 'root' /etc/passwd displays lines containing the pattern “root” and 3 lines after them in the file /etc/passwd. 
17. Command grep -v "bin" /etc/passwd displays all the lines in the file /etc/passwd that do not contain the pattern “bin”.
18. Command grep -i '^[a-z]' /etc/ssh/sshd_config displays all lines of the file /etc/ssh/sshd_config starting with a letter.
19. Command tr "A" "Z" | tr "c" "e" Replace all characters A and c from input to Z and e respectively.
20. Command tr -d "Cc" Creates a script that removes all letters c and C from input.
21. Command rev Writes a script that reverse its input.
22. Command cut -f 1,6 -d ':' /etc/passwd | sort Writes a script that displays all users and their home directories, sorted by users.
23. Command find . -empty | rev | cut -d '/' -f 1 | rev Writes a command that finds all empty files and directories in the current directory and all sub-directories.
24. command find -type f -name "*.git" | rev | cut -d -f 1 | cut -d '.' 2- | rev | LC_ALL-C sort -f Writes a script that lists all the files with a .gif extension in the current directory and all its sub-directories
25. Command cut -c 1 | paste -s -d '' creates a script that decodes acrostics that use the first letter of each line.
26. Command tail -n +2 | cut -f -1 sort -k 1 | uniq -c sort -rn1 | head -n 11 | rev |cut -d  -f -1 | rev writes a script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests. 
