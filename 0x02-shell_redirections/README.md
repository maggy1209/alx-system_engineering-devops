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
16. Task 15: Script that displays the number of lines that contain the pattern “bin” in the file `/etc/passwd`

        grep bin /etc/passwd | wc -l   
