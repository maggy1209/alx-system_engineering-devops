1. Task 0: Script that prints “Hello, World”, followed by a new line to the standard    output.

        echo Hello, World
2. Task 1: Script that displays a confused smiley `(Ôo)`.

        echo "\"(Ôo)'"
3. Task 2: Script that displays the content of the `/etc/passwd` file.
        
        cat /etc/passwd
4. Task 3: Script that displays the content of `/etc/passwd` and `/etc/hosts`

        cat /etc/passwd /etc/hosts
5. Task 4: Script that displays the last 10 lines of `/etc/passwd`.

        ls -lt | tail /etc/passwd
6. Task 5: Script that displays the first 10 lines of `/etc/passwd`.

        ls -lt | head /etc/passwd
7. Task 6: Script that displays the third line of the file `iacta`.

        head -n 3 iacta | tail -n 1
8. Task 7: Script that creates a file named exactly `\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)`  containing the text `Best School` ending by a new line.

        echo "Best School" > '\*\\'\''"Best School"\'\''\\*$\?\*\*\*\*\*:)'
10. Task 9: Script that duplicates the last line of the file `iacta`.

        tail -n 1 iacta >> iacta  
11. Task 10: Script that deletes all the regular files with a `.js` extension  present in the current dir and its subfolders.

        find . -name '*.js' -type f -delete  
12. Task 11: Script that counts the number of directories and sub-directories in the current directory.

        find ./* -type d -print | wc -l
13. Task 12: Script that displays the 10 newest files in the current directory.

        ls -t | head
14. Task 13: Script that takes a list of words as input and prints only words that appear exactly once.
    * Input format: One line, one word
    * Output format: One line, one word
    * Words are sorted.

          sort | uniq -u
16. Task 15: Script that displays the number of lines that contain the pattern “bin” in the file `/etc/passwd`

        grep bin /etc/passwd | wc -l   
15. Task 14: Script that displays lines containing the pattern “root” from the file `/etc/passwd`

        grep "root" /etc/passwd
17. Task 16: Script that displays lines containing the pattern “root” and 3 lines after them in the file `/etc/passwd`.

        grep -A 3 root /etc/passwd
18. Task 17: Script that displays all the lines in the file `/etc/passwd` that do not contain the pattern “bin”.

        grep -v bin /etc/passwd
19. Task 18: Script that displays all lines of the file `/etc/ssh/sshd_config` starting with a letter. Including capital letters.

        grep "^[[:alpha:]]" /etc/ssh/sshd_config 
Task 19: Script that replaces all characters `A` and `c` from input to `Z` and `e` respectively.

        tr "Ac" "Ze"
9. Task 8: Script that writes into the file `ls_cwd_content` the result of the command `ls -la`.If the file `ls_cwd_content` already exists, it is overwritten.              If the file ls_cwd_content does not    exist, it's created.

        ls -la > ls_cwd_content
21. Task 20: Script that removes all letters `c` and `C` from input.

        tr -d [cC]
22. Task 21: Script that reverses its input.

        rev


