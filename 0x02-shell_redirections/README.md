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

